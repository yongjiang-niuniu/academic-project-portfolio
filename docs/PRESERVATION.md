# Project preservation and maintenance

## What a preserved project should contain

- A README explaining the problem, the files present, the actual contribution, and the project's current state.
- Source files and project-owned outputs that can be retained in the selected repository's visibility.
- Original licenses and attribution for dependencies, templates, and team contributions.
- Setup instructions grounded in the committed files, with missing dependencies or data stated explicitly.
- A record of where an imported project came from and which branch or commit was preserved.

Private classroom archives use an `ARCHIVE.md` or equivalent provenance record alongside the original learning material. A report-only project should say that the implementation is unavailable rather than present the report as a runnable application.

## Commit history

Original commits retain their authors and dates. New organization work receives current timestamps and specific messages that describe actual changes, such as adding project context, documenting reproduction steps, or recording archive provenance.

Do not backdate imports to simulate development history or create empty commits to increase a contribution count. Do not rewrite a group's original commits to claim individual authorship.

## Public and private copies

Public repositories are suitable for project material whose publication has been checked. Mixed teaching resources, team submissions, private feedback, and material with uncertain permission belong in private storage until reviewed.

GitHub visibility should be checked for each destination before uploading. A private source must not become public merely because it has been copied to a personal account. Credentials and unrelated personal records do not belong in either public or private project history.

## Durable backups

GitHub is one copy of the work, not a guarantee of permanent availability. Keep an independent copy on local storage and an additional backup device or service.

Start from a full repository clone. Check `git rev-parse --is-shallow-repository`; if it reports `true`, first run `git fetch --unshallow --tags origin`. A shallow checkout can produce a bundle that appears valid in the original checkout but cannot be restored independently because parent commits are missing.

For a complete repository available locally, a portable Git backup can be made with:

```sh
git fetch --all --tags
git bundle create project-backup.bundle --all
git bundle verify project-backup.bundle
```

Verify restoration in a separate directory as well:

```sh
git clone --bare project-backup.bundle restored-check.git
git -C restored-check.git fsck --full
```

The restored repository should have the expected commit and branches. Keep the verification copy separate from the working project.

A Git bundle contains committed Git objects and references. It does **not** include uncommitted files, external datasets, Git LFS object contents, release attachments, issues, pull-request discussions, or submodule repository contents. Back up those separately when they matter, with appropriate permissions and source records.

## Updating a project later

1. Fetch the latest state and preserve existing history.
2. Make one coherent change and document its purpose.
3. Check that README paths, commands, and claims still match the files.
4. Run checks appropriate to the change. Record whether results were reproduced or only inspected.
5. Commit and push without forcing over newer work.
6. Verify the destination commit and refresh the independent backup.

Completed archival work and unresolved recovery gaps should be recorded separately. A missing Blackboard submission or missing implementation remains an open recovery item, even when its project already has a README.

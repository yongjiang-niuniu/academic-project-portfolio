# YARL Software Reengineering

A **COM6523 Software Reengineering** team project at the University of Sheffield in 2026, working with the Python URL library [yarl](https://github.com/aio-libs/yarl).

## Project purpose

The team investigated an existing codebase, identified focused changes to its internal structure, and evaluated those changes using analysis evidence and regression tests. The work brings together repository evolution analysis, static analysis, dynamic analysis, refactoring, and a written evaluation.

## Work preserved in the project

- Extracted path, query, and fragment resolution from `URL.join()` into internal helpers.
- Separated child-path construction used by `URL.joinpath()` and the `/` operator.
- Added focused regression coverage for joining URLs and constructing child paths.
- Retained system-understanding notes, analysis outputs, before/after evidence, and the final team report.

The source and reports are kept in a private personal archive with original Git history and attribution. The recorded test and complexity results are historical project evidence; this preservation pass did not rerun the full test suite.

## My contribution and attribution

The project report credits **Yongjiang Liu** with coordination, requirements analysis, system understanding, integration, and report synthesis. This is a team project: its source history and report preserve the broader contribution record.

The underlying yarl library is an upstream open-source project. Its existing license, NOTICE, and contributor attribution remain applicable. Archiving this coursework does not claim authorship of the entire library.

## Related coursework

The private course collection also preserves weekly exercises covering Python/Git setup, understanding Black, repository mining, Pygame static analysis, yarl dynamic analysis, regression testing, code clones, refactoring, and responsibility redistribution. Each archive states which work is actually present; a teaching template is not presented as a completed implementation.

[Return to the portfolio](../README.md).

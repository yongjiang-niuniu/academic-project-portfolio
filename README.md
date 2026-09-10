# Yongjiang Liu — Academic Project Portfolio

A portfolio of university projects and research spanning high performance computing, machine learning, software engineering, optimization, and computer graphics. The collection connects project goals to their implementation, final reports, experiment evidence, and practical setup instructions.

**中文概述：** 这是我的学校项目索引，集中展示课程最终项目、研究成果和可复现性说明。小组作品保留团队归属；课程提交、课程数据和 EVRP 原始报告均按我的授权公开保留，原始材料和团队署名保持不变。

**[Papers and report versions](PAPERS.md)** — Direct PDF links for all ten projects, the September Overleaf review, and six undergraduate reports that still lack a corresponding course repository.

## Project overview

| Project | What is in the repository | Main technologies | Status |
| --- | --- | --- | --- |
| [Energy and Carbon Monitoring in HPC Systems](https://github.com/yongjiang-niuniu/Energy-and-Carbon-Monitoring-in-High-Performance-Computing-HPC-Systems) | Dissertation research materials, a 92-page September working draft, Slurm simulation configuration, analysis scripts, and selected simulation outputs | Slurm, Python, shell scripts, Docker | Research in progress; later manuscript differs from the early public code; energy values are model estimates |
| [eWaste Hub](https://github.com/yongjiang-niuniu/team) | Electronic-waste collection prototype with React frontend, Flask backend, official COM6103 report, and two complete GitLab source snapshots | React, TypeScript, Flask, SQLAlchemy, JWT | report-associated and latest source versions retained; 102 isolated backend tests, frontend build and lint passed |
| [Statistical Language Model](https://github.com/yongjiang-niuniu/COMP) | COM6516 Java application exploring word frequencies, n-gram prediction, hash functions, and collision-chain histograms, with its official submitted ZIP and student report | Java, Swing, custom hash table and linked nodes | official submission matched to existing code; source rebuild instructions documented |
| [CIFAR-100 Classification Experiments](https://github.com/yongjiang-niuniu/cifar-100) | ResNet and Vision Transformer notebooks, the recovered Deep Learning and Robotics paper, repaired ResNet-50 workflow, and offline checks | Python, PyTorch, torchvision, Jupyter | Offline execution checked on generated images; paper/notebook historical experiment differences documented |
| [Electric Vehicle Routing Research](projects/evrp.md) | Personal research comparing genetic algorithms, simulated annealing, and ant colony optimization under load and battery constraints | Python, combinatorial optimization, local search, feasibility analysis | PDF, LaTeX and March 2025 solver snapshot published with benchmark inputs; final experimental version still unverified |
| [YARL Software Reengineering](projects/yarl-reengineering.md) | COM6523 team study of URL operations, internal refactoring, regression tests, and before/after analysis | Python, pytest, repository mining, static and dynamic analysis | verified final Blackboard report, report-to-source guide, regression evidence, and updated project documentation |
| [Sentiment Analysis](https://github.com/yongjiang-niuniu/com6115-sentiment-analysis) | COM6115 comparison of Naive Bayes and lexicon-based sentiment classification, including submitted code, report and complete course data | Python, text processing, sentiment lexicons | original script rerun with recovered course data; fresh random split distinguished from report results |
| [Parallel Computing](https://github.com/yongjiang-niuniu/com6521-parallel-computing) | COM6521 OpenMP and CUDA implementations for glider counting, image histograms and embossing, with submitted report and restored course framework | C, C++, OpenMP, CUDA | source and build references verified; GPU benchmarks require a compatible NVIDIA environment |
| [3D Computer Graphics](https://github.com/yongjiang-niuniu/com6503-3d-computer-graphics) | COM6503 animated bee scene, plus a separate submitted study comparing photographs, Phong-style shading and PBR for statue materials in Blender | C++17, OpenGL 3.3, GLFW, GLM, Blender | both submitted attachments recovered; original Blender scenes and separate research assets are not available |
| [Natural Systems Modelling](https://github.com/yongjiang-niuniu/com6009-natural-systems-modelling) | COM6009 report examining Duffing dynamics, agent-based ecology and harvested Lotka–Volterra models | Dynamical systems, ecological modelling, simulation analysis | Report archive; original simulation code and raw experiment data not recovered |

Repository history and team attribution are retained. The former `cider-100` repository was renamed to **`cifar-100`** to match its dataset; it remains the same repository. Existing names such as `team` and `COMP` are explained by their project titles and README introductions.

## Getting started

1. Start with the project's README for its scope and file map.
2. Follow its setup guide and check the stated prerequisites before running code.
3. Treat saved outputs as historical evidence; distinguish those from results reproduced in a clean environment.
4. For team work, consult the original history and project attribution rather than assuming that every file is an individual contribution.

## Collection structure

This public repository is the entry point for ten project repositories. Its `projects/` pages introduce selected work and link directly to the repositories containing the reports and supporting materials. The [documentation guide](docs/README.md) links the maintenance policy and explains how to read the collection.

The separate [academic archive](https://github.com/yongjiang-niuniu/academic-project-archive) records all course coverage, submission sources, verified attachments, and current project revisions. My [GitHub profile](https://github.com/yongjiang-niuniu) provides a personal introduction and selected project links. The collection has 13 public repositories: ten projects, two indexes and the [profile repository](https://github.com/yongjiang-niuniu/yongjiang-niuniu).

## Submission coverage

The September 2026 recovery review checked the submission lists of all **11 accessible Blackboard courses**. Seven courses contain submitted project files and are represented above. The other four contain training or tests, saved drafts, or dissertation deliverables not yet submitted; they are not presented as recovered final projects.

All observed submitted project attachments have been recovered, including the COM6503 Assignment 2 paper from Turnitin. This establishes submission coverage, not complete experimental reproducibility: the graphics paper does not include its original Blender scenes or separate photos/material files. Natural Systems Modelling remains a report-only archive. EVRP now includes its editable report source and a recovered Python development snapshot with its upstream notices; the final experiment configuration remains unresolved. The HPC repository is research in progress, not a verified final dissertation submission.

For eWaste, both recovered GitLab ZIPs contain complete file snapshots. The original 249-commit GitLab history has not been imported; source commit references and the existing GitHub history are preserved. The nine personal COM6523 weekly-exercise repositories were removed after their independent backups were verified; the final YARL project is retained.

## Validation and current state

The project READMEs use a consistent English introduction with a short Chinese overview, followed by purpose, structure, setup, evidence, and attribution appropriate to each project. Documentation navigation was refreshed across the collection. Original submissions and earlier Git history are retained.

Verification is specific to each project. eWaste records an isolated backend test run and frontend build/lint checks; the sentiment project records a rerun with recovered data. HPC provides checked analysis command interfaces. CIFAR-100 now includes a passing offline ResNet-50 check for training, evaluation, checkpoint saving, and perturbation severity using generated fixtures. Those fixtures do not establish classification accuracy. GPU execution, full model training, and missing report-only implementations are not implied by a completed archive.

See [preservation and maintenance](docs/PRESERVATION.md) for source integrity, meaningful maintenance commits, and independent backups.

## Attribution

Portfolio owner: **Yongjiang Liu** ([yongjiang-niuniu](https://github.com/yongjiang-niuniu)).

Repository ownership is not a blanket claim of authorship or permission to redistribute every dependency, dataset, teaching resource, or team contribution. Each project's existing attribution and license information applies. This index does not grant a new license to linked materials.

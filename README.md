# Yongjiang Liu — Academic Project Portfolio

Selected final university projects and research in high performance computing, machine learning, software engineering, and data structures. Each linked repository documents the files it actually contains, the steps needed to use them, and any known gaps.

这是我的学校项目索引，集中展示课程最终项目、研究成果和可复现性说明。小组作品保留团队归属；含团队材料的最终提交和 EVRP 原始报告采用私有保存。

## Projects

| Project | What is in the repository | Main technologies | Status |
| --- | --- | --- | --- |
| [Energy and Carbon Monitoring in HPC Systems](https://github.com/yongjiang-niuniu/Energy-and-Carbon-Monitoring-in-High-Performance-Computing-HPC-Systems) | Dissertation research materials, Slurm simulation configuration, workload generation, analysis scripts, and selected simulation outputs | Slurm, Python, shell scripts, Docker | Research in progress; simulated energy estimates depend on documented assumptions |
| [eWaste Hub](https://github.com/yongjiang-niuniu/team) | Official COM6103 final report and March 2026 backend snapshot for accounts, authentication, collection requests, and administrative updates | Python, Flask, SQLAlchemy, JWT, Alembic | Official report preserved privately; available code is the March 2026 backend; complete final GitLab source still to be recovered |
| [Statistical Language Model](https://github.com/yongjiang-niuniu/COMP) | COM6516 Java application exploring word frequencies, n-gram prediction, hash functions, and collision-chain histograms | Java, Swing, custom hash table and linked nodes | Coursework implementation |
| [CIFAR-100 Classification Experiments](https://github.com/yongjiang-niuniu/cider-100) | Configurable ResNet training and Vision Transformer notebooks for image classification | Python, PyTorch, torchvision, Jupyter | Experimental notebooks; saved metrics and execution state require careful interpretation |
| [Electric Vehicle Routing Research](projects/evrp.md) | Research report comparing genetic algorithms, simulated annealing, and ant colony optimization under load and battery constraints | Combinatorial optimization, local search, feasibility validation | Report preserved privately; implementation and raw experiment files not yet recovered |
| [YARL Software Reengineering](projects/yarl-reengineering.md) | COM6523 team study of URL operations, internal refactoring, regression tests, and before/after analysis | Python, pytest, repository mining, static and dynamic analysis | Final archive version `71d868c9`; verified Blackboard report, report-to-source guide, and reproduction instructions |

The original repository names are retained so existing links and project history continue to work. The `cider-100` repository contains **CIFAR-100** experiments.

## How to explore

1. Start with the project's README for its scope and file map.
2. Follow its setup guide and check the stated prerequisites before running code.
3. Treat saved outputs as historical evidence; distinguish those from results reproduced in a clean environment.
4. For team work, consult the original history and project attribution rather than assuming that every file is an individual contribution.

## Coverage

This page focuses on final projects and research. The September 2026 recovery review has identified 11 accessible Blackboard courses and recovered the official final reports for COM6523 and COM6103. The remaining course submissions are being reviewed, so this page does not yet represent every university project. Team source and submission documents retain their attribution and appropriate private storage.

See [preservation and maintenance](docs/PRESERVATION.md) for how these projects are kept and updated.

## Attribution

Portfolio owner: **Yongjiang Liu** ([yongjiang-niuniu](https://github.com/yongjiang-niuniu)).

Repository ownership is not a blanket claim of authorship or permission to redistribute every dependency, dataset, teaching resource, or team contribution. Each project's existing attribution and license information applies. This index does not grant a new license to linked materials.

# Yongjiang Liu — Academic Project Portfolio

Selected final university projects and research in high performance computing, machine learning, software engineering, and data structures. Each linked repository documents the files it actually contains, the steps needed to use them, and any known gaps.

这是我的学校项目索引，集中展示课程最终项目、研究成果和可复现性说明。小组作品保留团队归属；课程提交、课程数据和 EVRP 原始报告采用私有保存。私有链接需要仓库访问权限。

## Projects

| Project | What is in the repository | Main technologies | Status |
| --- | --- | --- | --- |
| [Energy and Carbon Monitoring in HPC Systems](https://github.com/yongjiang-niuniu/Energy-and-Carbon-Monitoring-in-High-Performance-Computing-HPC-Systems) | Dissertation research materials, Slurm simulation configuration, workload generation, analysis scripts, and selected simulation outputs | Slurm, Python, shell scripts, Docker | Research in progress; simulated energy estimates depend on documented assumptions |
| [eWaste Hub](https://github.com/yongjiang-niuniu/team) | Electronic-waste collection prototype with React frontend, Flask backend, official COM6103 report, and two complete GitLab source snapshots | React, TypeScript, Flask, SQLAlchemy, JWT | Private; report-associated and latest source versions retained; 102 isolated backend tests, frontend build and lint passed |
| [Statistical Language Model](https://github.com/yongjiang-niuniu/COMP) | COM6516 Java application exploring word frequencies, n-gram prediction, hash functions, and collision-chain histograms, with its official submitted ZIP and student report | Java, Swing, custom hash table and linked nodes | Private; official submission matched to existing code; source rebuild instructions documented |
| [CIFAR-100 Classification Experiments](https://github.com/yongjiang-niuniu/cider-100) | Configurable ResNet training and Vision Transformer notebooks for image classification | Python, PyTorch, torchvision, Jupyter | Experimental notebooks; saved metrics and execution state require careful interpretation |
| [Electric Vehicle Routing Research](projects/evrp.md) | Research report comparing genetic algorithms, simulated annealing, and ant colony optimization under load and battery constraints | Combinatorial optimization, local search, feasibility validation | Report preserved privately; implementation and raw experiment files not yet recovered |
| [YARL Software Reengineering](projects/yarl-reengineering.md) | COM6523 team study of URL operations, internal refactoring, regression tests, and before/after analysis | Python, pytest, repository mining, static and dynamic analysis | Final archive version `71d868c9`; verified Blackboard report, report-to-source guide, and reproduction instructions |
| [Sentiment Analysis](https://github.com/yongjiang-niuniu/com6115-sentiment-analysis) | COM6115 comparison of Naive Bayes and lexicon-based sentiment classification, including submitted code, report and complete course data | Python, text processing, sentiment lexicons | Private; original script rerun with recovered course data; fresh random split distinguished from report results |
| [Parallel Computing](https://github.com/yongjiang-niuniu/com6521-parallel-computing) | COM6521 OpenMP and CUDA implementations for glider counting, image histograms and embossing, with submitted report and restored course framework | C, C++, OpenMP, CUDA | Private; source and build references verified; GPU benchmarks require a compatible NVIDIA environment |
| [3D Computer Graphics](https://github.com/yongjiang-niuniu/com6503-3d-computer-graphics) | COM6503 animated bee scene, plus a separate submitted study comparing photographs, Phong-style shading and PBR for statue materials in Blender | C++17, OpenGL 3.3, GLFW, GLM, Blender | Private; both submitted attachments recovered; original Blender scenes and separate research assets are not available |
| [Natural Systems Modelling](https://github.com/yongjiang-niuniu/com6009-natural-systems-modelling) | COM6009 report examining Duffing dynamics, agent-based ecology and harvested Lotka–Volterra models | Dynamical systems, ecological modelling, simulation analysis | Private report archive; original simulation code and raw experiment data not recovered |

The original repository names are retained so existing links and project history continue to work. The `cider-100` repository contains **CIFAR-100** experiments.

## How to explore

1. Start with the project's README for its scope and file map.
2. Follow its setup guide and check the stated prerequisites before running code.
3. Treat saved outputs as historical evidence; distinguish those from results reproduced in a clean environment.
4. For team work, consult the original history and project attribution rather than assuming that every file is an individual contribution.

## Coverage

The September 2026 recovery review checked the submission lists of all **11 accessible Blackboard courses**. Seven courses contain submitted project files and are represented above. The other four contain training or tests, saved drafts, or dissertation deliverables not yet submitted; they are not presented as recovered final projects.

All observed submitted project attachments have been recovered, including the COM6503 Assignment 2 paper from Turnitin. This establishes submission coverage, not complete experimental reproducibility: the graphics paper does not include its original Blender scenes or separate photos/material files. Natural Systems Modelling and EVRP remain report-only archives because their original implementations have not been recovered. The HPC repository is research in progress, not a verified final dissertation submission.

For eWaste, both recovered GitLab ZIPs contain complete file snapshots. The original 249-commit GitLab history has not been imported; source commit references and the existing GitHub history are preserved. The nine personal COM6523 weekly-exercise repositories were removed after their independent backups were verified; the final YARL project is retained.

See [preservation and maintenance](docs/PRESERVATION.md) for how these projects are kept and updated.

## Attribution

Portfolio owner: **Yongjiang Liu** ([yongjiang-niuniu](https://github.com/yongjiang-niuniu)).

Repository ownership is not a blanket claim of authorship or permission to redistribute every dependency, dataset, teaching resource, or team contribution. Each project's existing attribution and license information applies. This index does not grant a new license to linked materials.

# Electric Vehicle Routing Research

**Report title:** *Perturbation is All You Need*  
**Author:** Yongjiang Liu  
**Report date:** April 2025  
**Institution on the report:** University of Manchester, School of Computer Science

**中文概述：** 本研究探讨电动车路径规划中的扰动、局部搜索与可行性修复，比较遗传算法、模拟退火和蚁群算法。64 页原始报告及 LaTeX、图表已归档；另找回早期 Python 代码和部分实验结果，正在核对来源、个人贡献及其与最终论文的对应关系。

[Open the report repository](https://github.com/yongjiang-niuniu/evrp-perturbation-study).

## Research question

How can route perturbation, local search, and feasibility repair improve an initial solution to the Electric Vehicle Routing Problem while respecting vehicle capacity and battery constraints?

## Approach described in the report

The study starts from a multi-stage greedy route constructor and investigates three search methods:

- A genetic algorithm using evolutionary search and route refinement.
- Simulated annealing using neighborhood changes and temperature-controlled acceptance.
- Ant colony optimization using pheromone-guided construction and local search.

The report also describes a C++ validator that checks customer visits, depot boundaries, load, battery feasibility, and route distance. Evaluation is based on the IEEE WCCI 2020 EVRP benchmark family.

## What is available

The original 64-page report is preserved without modification in the project archive, together with its SHA-256 checksum and evidence notes. A September 2026 recovery also restored 58 editable report-source files from Overleaf, including LaTeX chapters, bibliography, figures and the license file supplied with that source package.

Five Python development snapshots from February-March 2025 have now been recovered locally from email attachments. The latest located snapshot, dated March 12, includes GA, SA, ACO and other methods, 17 benchmark files and partial saved results. A cloud-storage copy matches that attachment byte for byte. These recovered files contain upstream code and collaborative material; they are not included in the public repository while individual contributions and redistribution terms are being resolved.

The latest located snapshot is not a verified final implementation: its stored results do not reproduce the report's final comparison table, and the described C++ validator has not been found. The public repository remains a research archive rather than a tested solver release.

## Results and next recovery step

The report contains numerical comparisons and route visualizations, but those experiments have not been rerun during preservation. Some narrative descriptions and table labels need reconciliation against the original experiment files. This page does not assert a universal best algorithm or a verified improvement percentage.

The next step is to establish the recovered code's attribution and final-version lineage, then provide an environment description and a small reproducible example in a separately documented release. The original report and historical snapshots remain unchanged; recovery commits are dated when the recovery work occurs.

[Return to the portfolio](../README.md).

# Electric Vehicle Routing Research

**Report title:** *Perturbation is All You Need*  
**Author:** Yongjiang Liu  
**Report date:** April 2025  
**Institution on the report:** University of Manchester, School of Computer Science

**中文概述：** 刘勇江的个人 EVRP 研究项目，在已有贪心构造与遗传算法基础上，研究模拟退火和蚁群算法中的扰动、局部搜索与可行性修复。仓库已保留原始论文、LaTeX 图表、2025 年 3 月 Python 开发快照、17 个基准文件及历史输出；该快照尚未确认为最终论文全部实验所用版本。

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

Five Python development snapshots from February-March 2025 were recovered. The latest located snapshot, dated March 12, is now published in the project's [solver directory](https://github.com/yongjiang-niuniu/evrp-perturbation-study/tree/main/solver). It includes GA, SA, ACO and other methods, 17 benchmark files and partial saved results. Notebook execution metadata and operating-system caches were excluded from publication. The project belongs to Yongjiang Liu; its inherited baseline retains the attribution and MIT notice for Hien Vu / NeiH4207's EVRP-Python implementation.

The latest located snapshot is not a verified final implementation: its stored results do not reproduce the report's final comparison table, and the described C++ validator has not been found. Run instructions and any small execution checks are recorded separately from the historical experiments in the project repository.

## Results and next recovery step

The report contains numerical comparisons and route visualizations, but those experiments have not been rerun during preservation. Some narrative descriptions and table labels need reconciliation against the original experiment files. This page does not assert a universal best algorithm or a verified improvement percentage.

The next step is to recover the exact final experiment configuration and strengthen route validation before making new performance claims. The original report and historical snapshots remain unchanged; recovery commits are dated when the recovery work occurs.

[Return to the portfolio](../README.md).

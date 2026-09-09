# YARL Software Reengineering

A **COM6523 Software Reengineering** team project at the University of Sheffield in 2026, working with the Python URL library [yarl](https://github.com/aio-libs/yarl).

**中文概述：** 这是针对 Python URL 库 yarl 的软件再工程团队项目，包含结构分析、行为保持的重构、回归测试与最终报告。报告记录我的协调、需求分析、系统理解、整合和报告综合工作，原始团队署名与历史保留。

[Open the private final-project repository](https://github.com/yongjiang-niuniu/com6523-2026-yarl-reengineering-pg-05) — repository access is required.

## Project purpose

The team investigated an existing codebase, identified focused changes to its internal structure, and evaluated those changes using analysis evidence and regression tests. The work brings together repository evolution analysis, static analysis, dynamic analysis, refactoring, and a written evaluation.

## Work preserved in the project

- Extracted path, query, and fragment resolution from `URL.join()` into internal helpers.
- Separated child-path construction used by `URL.joinpath()` and the `/` operator.
- Added focused regression coverage for joining URLs and constructing child paths.
- Retained system-understanding notes, analysis outputs, before/after evidence, and the final team report.

The source and reports are kept in a private personal archive with original Git history and attribution. The official final report has now been downloaded from the submitted Blackboard attempt; its SHA-256 digest matches the final PDF already preserved from the classroom repository. A separate local PDF copy has a different file hash; the recorded text and page comparisons match the canonical report.

The verified archive revision after the September 2026 documentation refresh is commit [`ac613bebdea6750ee1d7ade5ed1cf7f9dc733d2e`](https://github.com/yongjiang-niuniu/com6523-2026-yarl-reengineering-pg-05/commit/ac613bebdea6750ee1d7ade5ed1cf7f9dc733d2e). Its updated documentation links the report to the implementation and recorded evidence, records the verified Blackboard submission, and explains how to reproduce checks while preserving the original coursework outputs.

The recorded test and complexity results are historical project evidence; this preservation pass did not rerun the full test suite.

## My contribution and attribution

The project report credits **Yongjiang Liu** with coordination, requirements analysis, system understanding, integration, and report synthesis. This is a team project: its source history and report preserve the broader contribution record.

The underlying yarl library is an upstream open-source project. Its existing license, NOTICE, and contributor attribution remain applicable. Archiving this coursework does not claim authorship of the entire library.

[Return to the portfolio](../README.md).

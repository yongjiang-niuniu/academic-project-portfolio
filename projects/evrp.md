# Electric Vehicle Routing Research

**Report title:** *Perturbation is All You Need*  
**Author:** Yongjiang Liu  
**Report date:** April 2025  
**Institution on the report:** University of Manchester, School of Computer Science

## Research question

How can route perturbation, local search, and feasibility repair improve an initial solution to the Electric Vehicle Routing Problem while respecting vehicle capacity and battery constraints?

## Approach described in the report

The study starts from a multi-stage greedy route constructor and investigates three search methods:

- A genetic algorithm using evolutionary search and route refinement.
- Simulated annealing using neighborhood changes and temperature-controlled acceptance.
- Ant colony optimization using pheromone-guided construction and local search.

The report also describes a C++ validator that checks customer visits, depot boundaries, load, battery feasibility, and route distance. Evaluation is based on the IEEE WCCI 2020 EVRP benchmark family.

## What is available

The original 64-page report has been recovered and preserved without modification in a private project archive, together with its SHA-256 checksum and evidence notes.

This public page summarizes the research. The implementation, original experiment logs, benchmark files, and editable report source have not yet been recovered. The archive is therefore a report record rather than a runnable software release.

## Results and next recovery step

The report contains numerical comparisons and route visualizations, but those experiments have not been rerun during preservation. Some narrative descriptions and table labels need reconciliation against the original experiment files. This page does not assert a universal best algorithm or a verified improvement percentage.

The next useful addition is the original implementation and experiment record, with an environment description and a small reproducible example. Any recovered version should retain its original authorship and be linked to the report's experiments before new performance claims are added.

[Return to the portfolio](../README.md).

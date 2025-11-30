# Reproducibility in Single-Cell RNA-seq: A Systematic Reassessment

![Status](https://img.shields.io/badge/Status-Under_Development-yellow)
![License](https://img.shields.io/badge/License-MIT-blue)

## Overview
This repository hosts the evaluation pipeline and reproducibility scorecard for a systematic meta-analysis of 100 single-cell RNA-seq studies published in *Nature* (2025). This work will be presented at **WCRI 2026**.

We propose a standardized, open-source workflow to address the systemic gaps in bioinformatics reproducibility using **CREDO** and **Docker** containers.

## Abstract
Reproducibility is a cornerstone of scientific integrity, yet it remains a major challenge in bioinformatics. We systematically reassessed 100 single-cell RNA-seq studies, attempting to reproduce key results using only the information provided in each paper. We introduce a reproducibility scorecard evaluating data accessibility, code availability, parameter transparency, and software traceability.

Our entire evaluation pipeline is itself fully reproducible, implemented through Docker containers built with **CREDO** (Alessandri S. et al. 2024), organized with Jupyter notebooks for transparency.

## Project Goals
1.  **Assessment:** Evaluate the current state of reproducibility in high-profile scRNA-seq studies.
2.  **Standardization:** Propose a practical process involving CREDO-based Docker images and JupyterLab.
3.  **Traceability:** Ensure every computational step—from raw data to publication figures—is transparent and reusable.

## Repository Structure (Upcoming)
The full source code, reproducibility scorecards, and container definitions will be released prior to the conference. The repository will include:
* 📂 **notebooks/**: Jupyter notebooks for data acquisition and preprocessing.
* 📂 **docker/**: CREDO-based Dockerfiles for the execution environment.
* 📂 **analysis/**: Downstream analysis and figure generation scripts.
* 📄 **scorecard_data.csv**: Aggregated data on the 100 evaluated papers.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## References
* **CREDO Project:** [https://github.com/CREDOProject](https://github.com/CREDOProject)

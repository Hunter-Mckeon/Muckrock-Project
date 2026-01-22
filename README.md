# U.S. Military Slot Machine Revenue Analysis (FY2020–FY2024)

## Overview

This repository contains the complete data pipeline and analysis for a public-interest research project using FOIA records obtained through MuckRock. The project examines slot-machine revenue and machine distribution across more than 100 U.S. military bases worldwide from fiscal years 2020–2024.

The goal of this work is to support transparent, reproducible analysis of gambling infrastructure within military installations and to enable further research into gambling exposure, financial risk, and public accountability.

## Repository Access & Hosting

This project was conducted using FOIA records and infrastructure provided through MuckRock. As a result, the primary repository is hosted under the BU Spark / MuckRock collaboration and cannot be directly cloned or mirrored into a separate personal GitHub repository.

The full project repository, including source materials and original analysis artifacts, is available here:  
https://github.com/BU-Spark/ds-muckrock-liberation/tree/0b2594b417b13dd36e1af26038d77fe1c88ccbe4/fa25-team-a

This repository is intended to document the methodology, analytical approach, and outputs while referencing the authoritative project source above.

## Project Scope

The project was developed end-to-end, covering the full lifecycle from raw document ingestion to cleaned datasets and exploratory analysis. Source materials consist of scanned government asset reports released through FOIA requests.

Key analytical questions include:
- How slot-machine revenue varies across bases and regions
- Differences in machine counts and revenue concentration
- Regional and temporal patterns over FY2020–FY2024
  

## Methodology

The workflow includes:
- Optical character recognition (OCR) applied to scanned FOIA documents
- Systematic data cleaning, normalization, and validation
- Exploratory data analysis (EDA) to identify revenue and distribution trends
- Structuring outputs for reproducibility and downstream use

Processed datasets are organized to facilitate auditing and extension. Analytical outputs are deployed to a Datasette instance to support large-scale querying and interactive exploration.

## Repository Contents

- **OCR Pipeline**: Scripts for extracting structured data from scanned FOIA documents
- **Cleaned Datasets**: Standardized revenue and machine-count tables covering FY2020–FY2024
- **Exploratory Analysis**: Notebooks and scripts analyzing revenue patterns, regional differences, and base-level summaries
- **Reproducible Workflows**: Modular notebooks and utilities designed for transparency, validation, and future extension


## Intended Use

This repository is intended for:
- Researchers studying gambling exposure and financial risk among service members
- Analysts interested in FOIA-based data pipelines and OCR workflows
- Public-interest and policy research focused on transparency and accountability

## License & Data Use

FOIA-released source documents are public records. Derived datasets and analysis code are provided for research and educational use. Users should cite MuckRock and the originating government sources where appropriate.



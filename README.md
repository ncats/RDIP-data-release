# RDIP-data-release
This repository hosts public releases of RDIP-curated datasets that support the GARD (Genetic and Rare Diseases) program and related rare-disease informatics efforts at NCATS.

Data files are published as versioned GitHub Releases to provide:

  Stable download links

  Transparent version history

  Reproducibility and traceability

***The repository itself primarily serves as a distribution point, not as a codebase for analysis.***

## Available Data

Each release contains multiple CSV tables, including:

  GARD_record.csv

  GARD_age_of_onset.csv

  GARD_Disease_Xref.csv

  GARD_Description.csv

  GARD_Functional_Consequences.csv

  GARD_Disease_to_Gene.csv

  GARD_Inheritance.csv

  GARD_Nomenclature.csv

  GARD_Disease_To_Phenotype.csv


## How to Download the Latest Version

GitHub always maintains a pointer to the most recent release.

### Option 1 — Via browser

Go to:
https://github.com/ncats/RDIP-data-release/releases/latest

Download any CSV file from the Assets section.

### Option 2 — Direct download link (recommended for pipelines)
https://github.com/ncats/RDIP-data-release/releases/latest/download/<filename.csv>


Example:

https://github.com/ncats/RDIP-data-release/releases/latest/download/GARD_record.csv


This link will always resolve to the newest released version of the file.

### Option 3 — Command line
wget https://github.com/ncats/RDIP-data-release/releases/latest/download/GARD_record.csv


or

curl -L -O https://github.com/ncats/RDIP-data-release/releases/latest/download/GARD_record.csv

## How to Access Previous Versions

All historical releases are preserved:

https://github.com/ncats/RDIP-data-release/releases

Each release is tagged using the format:

vYYYY-MM-DD


Example:

v2026-01-28

Example: Downloading a specific version of one dataset

If you want the GARD_record.csv file from release v2026-01-28:

https://github.com/ncats/RDIP-data-release/releases/download/v2026-01-28/GARD_record.csv


You can replace:

The tag (v2026-01-28) with any release tag

The filename (GARD_record.csv) with any dataset file in that release

This allows users to:

  Reproduce analyses

  Compare versions

  Reference specific snapshots in publications

## Update Frequency

Releases are generated through an automated pipeline from Palantir Foundry/NIDAP and reflect the current RDIP curated state at the time of release.

## Data Usage

These datasets are intended for:

Research and analysis

Tool development

Data integration

Internal and external evaluation

Users are responsible for interpreting and validating the data for their specific use cases.

## Contact

For questions, issues, or requests:

Binghan Xue
binghan.xue@nih.gov

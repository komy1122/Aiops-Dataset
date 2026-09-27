# AIOps Dataset Reference

> **Provenance notice:** This repository is maintained as a research reference for an external AIOps dataset. The current repository contents do **not** establish that the dataset was created or authored by this repository owner. Original authorship, paper/source, redistribution terms, and license must be verified before research reuse or redistribution.

## Repository Purpose

This repository records the structure and access information of an AIOps dataset for fault-analysis and root-cause-analysis experiments.

It should be treated as a **dataset reference/index** until the original source, authorship, citation, and license have been independently verified and documented.

## Dataset Description

According to the dataset description currently preserved in this repository, the data were collected from a simulated e-commerce system based on a microservice architecture deployed in a cloud environment.

The described system contains 46 system instances:

- 40 microservice instances
- 6 virtual machines

The dataset description states that fault scenarios were replayed during several days in May 2022 and labeled with root-cause instances.

These statements describe the referenced dataset; they are **not claims that this repository owner conducted the original data collection**.

## Data Modalities

The referenced structure contains:

- logs
- metrics
- traces
- fault-injection / ground-truth records

## Dataset Link

The repository previously recorded the following external download location:

`https://mega.nz/file/SA1VCRoJ#wLSzQdE1p0M4-l5mGbRhUqqEU7t34XJGzbJLXWowEiM`

Availability, integrity, ownership, and redistribution permission of this external file have not been established by this README.

## Described Directory Structure

```text
Aiops-Dataset/
├── data/
│   ├── 2022-05-01/
│   │   ├── log/
│   │   ├── metric/
│   │   └── trace/
│   ├── 2022-05-03/
│   ├── 2022-05-05/
│   ├── 2022-05-07/
│   └── 2022-05-09/
└── groundtruth/
    ├── groundtruth-2022-05-01.csv
    ├── groundtruth-2022-05-03.csv
    ├── groundtruth-2022-05-05.csv
    ├── groundtruth-2022-05-07.csv
    ├── groundtruth-2022-05-09.csv
    └── groundtruth-all.csv
```

## Required Provenance QA Before Use

Before this dataset is used in a paper, benchmark, or public derivative dataset, verify and record:

| Item | Status |
|---|---|
| Original dataset title | To verify |
| Original authors / organization | To verify |
| Original paper / DOI | To verify |
| Canonical repository / landing page | To verify |
| Dataset version | To verify |
| License | To verify |
| Redistribution permission | To verify |
| Integrity / checksum | To verify |
| Required citation | To verify |

## Research Use

Potential research uses include:

- anomaly detection
- failure diagnosis
- root-cause analysis
- multimodal log/metric/trace correlation
- AIOps evaluation

Related project: [E2E Security AIOps](https://github.com/komy1122/e2e-security-aiops)

## Research Integrity

Public availability of a download link does not by itself establish permission to redistribute the dataset.

Until provenance and licensing are verified, this repository should remain a **reference/index rather than a canonical dataset distribution source**.

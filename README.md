# Vigna-Seed-Coat-Physical-Dormancy
Data and R scripts supporting the study of seed coat anatomy, physical dormancy, imbibition, and morphometric variation in Vigna.
# Seed coat anatomy and physical dormancy in Vigna

Data and reproducible R scripts supporting the study:

**Seed coat anatomy and physical dormancy in Vigna: evidence of functional modification associated with mungbean domestication**

## Study overview

This repository contains the data, metadata, and R scripts used to investigate seed coat morphology, seed coat allocation, physical dormancy, and imbibition in three Vigna taxa:

- Vigna radiata var. radiata (VRR)
- Vigna radiata var. sublobata (VRS)
- Vigna stipulacea

The study includes five accessions per taxon.

The analyses examine seed coat morphometric traits, seed coat ratio, imbibition behavior, and multivariate relationships among seed coat traits.

## Repository structure

```text
vigna-seed-coat-physical-dormancy/
│
├── README.md
├── LICENSE
│
├── data/
│   ├── raw/
│   │   ├── morphometric/
│   │   └── accession_data/
│   │
│   └── processed/
│       └── morphometric/
│
├── metadata/
│
├── scripts/
    ├── 01_data_import_quality_check.R
    ├── 02_seed_coat_ratio.R
    ├── 03_imbibition_within_accession.R
    ├── 04_morphometric_ratios.R
    ├── 05_mixed_effects_models.R
    ├── 06_PCA.R


# LUMHR_datasets

Collection of UK public datasets used for local and regional analysis of:

- mental health outcomes
- socio-demographic context
- health service access and capacity
- geospatial environmental factors

The repository is organised as a data library (not a software package): most folders contain source files plus local `readme.md` notes describing origin and contents.

## Repository Layout

Top-level structure:

```text
LUMHR_datasets/
├── datasets/
│   ├── reference/
│   │   ├── geography/
│   │   │   ├── lsoa_county_lookup/
│   │   │   ├── lsoa_local_authority_lookup/
│   │   │   ├── lsoa_icb_lookup/
│   ├── mental_health/
│   ├── socio_demographic/
│   ├── health_accessibility_capacity/
│   └── geospatial_environment/
└── README.md
```

## Dataset Domains

### 1) Mental Health

Representative sources include:

- Small Area Mental Health Index (SAMHI)
- GP Patient Survey
- Hospital Episode Statistics (HES)
- NHS A&E Attendances
- Mental Health Services Data Set (MHSDS)
- QOF and prescribing indicators

Typical granularity: LSOA, quarterly or annual snapshots, depending on source.

### 2) Socio-demographic

Representative sources include:

- NOMIS demographics data (2021)
- Index of Multiple Deprivation (including 2025 materials)
- DWP indicators (before and after 2018)

Typical use: covariates and contextual variables for equity, deprivation, and population structure analysis.

### 3) Health Accessibility and Capacity

Representative sources include:

- DfT travel time to health services
- NHS patients registered at GP practice

Typical use: accessibility and service pressure analysis.

### 4) Geospatial Environment

Representative sources include:

- DEFRA access to green and blue space
- DEFRA UK-AIR resources
- Extrium England noise and air quality viewer exports

Typical use: environmental exposure and place-based context analysis.

### Reference

Look up tables for LSOA to counties and ICBs.
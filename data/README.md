# Data

This folder contains the data used by the SQL scripts and the pandas notebook.

## raw/

Place the original dataset here: `diabetic_data.csv`.
It is not included in this repository. Download it from the
[UCI Machine Learning Repository — Diabetes 130-US Hospitals for Years 1999–2008](https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008).

## reference/

Lookup tables used for joins, split manually from `IDS_mapping.csv` (included with the original dataset):

- `admission_type.csv` — admission type
- `admission_source.csv` — admission source
- `discharge_disposition.csv` — discharge disposition

Expected structure:

    data/
    ├── raw/
    │   └── diabetic_data.csv
    └── reference/
        ├── admission_type.csv
        ├── admission_source.csv
        └── discharge_disposition.csv

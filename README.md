# Navigation System for Visually Impaired

**CSD2002 – Introduction to Data Science | Synthetic simulation project**

This repository contains the complete project package as a ZIP download, including the synthetic dataset, Excel data sheet, Python implementation, Streamlit demo, evaluation script, requirements, and documentation.

## Download the complete project

Download [navigation_project.zip](./navigation_project.zip) and extract it.

## Included components

- `synthetic_navigation_dataset.csv` — 2,000 synthetic obstacle scenarios
- `synthetic_navigation_data_sheet.xlsx` — dataset, data dictionary, and metadata
- `navigation_pipeline.py` — temporal filtering, distance estimation, risk assessment, waypoint graph, and A* routing
- `app.py` — interactive Streamlit simulator
- `evaluate.py` — distance and decision metric evaluation
- `requirements.txt` — Python dependencies
- `README.md` — setup and usage guide

## Run

```bash
pip install -r requirements.txt
streamlit run app.py
```

Evaluate the synthetic data:

```bash
python evaluate.py
```

## Dataset scope and limitations

The dataset is synthetic and intended for academic demonstration and logic evaluation. It is not real camera footage and does not train YOLOv8. The simulator uses manually supplied detection boxes and an illustrative corridor graph; it is not a certified assistive mobility device and must not be relied on for real-world navigation.

# Chinese Longitudinal Mockup

This repository contains a mockup project centered around the Chinese Longitudinal Healthy Longevity Survey (CLHLS) Biomarkers Datasets from 2009, 2012, and 2014 (ICPSR 37226). It includes data files, documentation, and example analyses primarily implemented in Jupyter Notebooks.

## Features

- Access to longitudinal biomarker datasets related to Chinese elderly health and longevity.
- Sample logistic regression modeling of health predictors using Python.
- Included user guide and related literature for context and reference.

## Tech Stack

- Primary language: Jupyter Notebook (Python)
- Data analysis libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
- Additional tools: Google BigQuery client, contextily for mapping

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook
- Required Python packages (install via pip):
  ```
  pip install numpy pandas matplotlib seaborn scikit-learn google-cloud-bigquery contextily
  ```

### Running the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/justin-napolitano/chinese_longitudinal_mockup.git
   cd chinese_longitudinal_mockup
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open and run notebooks or scripts in the `data` folder or others as needed.

## Project Structure

```
chinese_longitudinal_mockup/
├── 37226-descriptioncitation.html      # Description and citation info
├── 37226-manifest.txt                   # Dataset manifest
├── 37226-related_literature.txt        # Bibliography of related works
├── 37226-User_guide.pdf                # User guide for dataset
├── data/                              # Folder containing data and scripts
│   └── logistic_regression.md          # Logistic regression model design and example
├── series-487-related_literature.txt  # Additional literature
└── TermsOfUse.html                     # Terms of use for data
```

## Future Work / Roadmap

- Add more comprehensive Jupyter Notebooks demonstrating advanced statistical and machine learning analyses.
- Integrate data visualization dashboards for interactive exploration.
- Automate data preprocessing pipelines for the CLHLS datasets.
- Expand documentation with detailed methodology and usage examples.
- Potentially include scripts for data extraction and cleaning from raw sources.

---

*Note: This project is a mockup and may require dataset access permissions or additional configuration to fully utilize the data.*
---
# Exploratory Data Analysis for Drug Discovery — DHODH Inhibitors

This repository presents an exploratory data analysis (EDA) of compounds targeting **Human Dihydroorotate Dehydrogenase (DHODH)**, using data retrieved from the ChEMBL database.  
Finding selective DHODH inhibitors could accelerate new treatments for autoimmune diseases like rheumatoid arthritis and multiple sclerosis.

---

## Objectives

- Retrieve DHODH-related compounds from the ChEMBL database
- Clean and preprocess IC50 data for consistency and usability
- Convert IC50 to pIC50 for better interpretability
- Visualize trends in bioactivity and molecular properties
- Prepare the dataset for building bioactivity prediction models

---

## Methodology

1. **Data Acquisition**: Retrieved bioactivity data for DHODH inhibitors using the `chembl_webresource_client`.
2. **Filtering**: Selected compounds with valid IC50 values.
3. **Data Processing**: Converted IC50 values to pIC50 (`pIC50 = -log10(IC50 in molar units)`).
4. **Exploratory Analysis**: Visualized distributions, explored molecular properties, and identified potential high-potency compounds.

---

## Visualizations

### pIC50 Distribution

![download (1)](https://github.com/user-attachments/assets/638c8bb9-2bef-49fd-a277-d090a55473d4)

---

### Molecular Weight vs LogP

![download (2)](https://github.com/user-attachments/assets/e67e2be5-38d8-4390-aa15-5496c1fa9925)

---

### Models Vs R^2 value


![download](https://github.com/user-attachments/assets/5b89c60c-8e91-4423-8e18-3132143b166f)


---


## Tools and Technologies

- **Programming Language**: Python 3
- **Libraries Required**:
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `chembl_webresource_client`
- **Environment**: Jupyter Notebook

Install the libraries using:

```bash
pip install pandas matplotlib seaborn chembl_webresource_client
```

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/drug-discovery-eda.git
   cd drug-discovery-eda
   ```

2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn chembl_webresource_client
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open and run `EDA - Drug Discovery.ipynb`.

---

## Acknowledgements

This project builds upon educational materials available online and was adapted for personal learning and exploration.

---

## About

Maintained by a Master’s student in Biotechnology at Hochschule Offenburg, concurrently pursuing a BSc in Data Science at IIT Madras.  
Focused on applying computational tools to drug discovery and bioinformatics.

---



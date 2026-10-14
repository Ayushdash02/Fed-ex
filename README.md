# FedEx Logistics Operations Analysis

### Exploratory Data Analysis (EDA) | Logistics & Supply Chain Analytics

<p align="center">
  <img src="preview/Fed-ex-logo.png" alt="FedEx Logo" width="240">
</p>

<p align="center">
  <strong>Transforming Supply Chain Data into Actionable Logistics Insights</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Analysis-yellow?style=for-the-badge&logo=python&logoColor=black" alt="Python">
  <img src="https://img.shields.io/badge/Google%20Colab-Notebook-orange?style=for-the-badge&logo=googlecolab&logoColor=white" alt="Google Colab">
  <img src="https://img.shields.io/badge/Analysis-EDA-blue?style=for-the-badge" alt="Exploratory Data Analysis">
</p>

---

## 📌 Project Overview

**FedEx Logistics Operations Analysis** is an exploratory data analysis project focused on identifying patterns in logistics and supply chain operations.

The project examines shipment volumes, destination countries, shipment modes, vendor contributions, manufacturing sites, freight costs, shipment weights, correlations, and data quality. Using Python and Google Colab, the analysis transforms raw supply chain data into visual insights that can support logistics reporting and operational decision-making.

## 🎯 Project Objectives

- Analyze shipment volumes across destination countries.
- Compare shipment distributions by transportation mode.
- Identify leading vendors and manufacturing sites by shipment count.
- Examine freight-cost and shipment-weight distributions.
- Investigate the relationship between shipment weight and freight cost.
- Compare destination countries by average freight cost and shipment count.
- Explore correlations among key numerical logistics variables.
- Identify missing values and summarize numerical features.

## 🧰 Tools & Technologies

| Technology | Application |
|---|---|
| Python | Data analysis and programming |
| Google Colab | Notebook development and execution |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Plotly | Interactive charts |

---

## 📊 Visualizations Gallery

All project visualization images and the FedEx logo are stored in the `preview/` directory.

### 1. Shipment Destinations & Operations

<details>
<summary><strong>Explore shipment destinations, vendors and manufacturing sites</strong></summary>

**01. Top 10 Destination Countries by Number of Shipments**

![Top 10 Destination Countries](preview/01-top-10-destination-countries-by-shipments.png)

**02. Distribution of Shipments by Shipment Mode**

![Shipment Distribution by Mode](preview/02-shipment-distribution-by-mode.png)

**03. Top 10 Vendors by Number of Shipments**

![Top 10 Vendors](preview/03-top-10-vendors-by-shipments.png)

**04. Top 10 Manufacturing Sites by Number of Shipments**

![Top 10 Manufacturing Sites](preview/04-top-10-manufacturing-sites-by-shipments.png)

**09. Top 10 Destination Countries by Average Freight Cost**

![Average Freight Cost by Destination](preview/09-top-10-destination-countries-by-average-freight-cost.png)

**10. Top 15 Destination Countries by Shipment Count**

![Destination Countries by Shipment Count](preview/10-top-15-destination-countries-by-shipment-count.png)

</details>

### 2. Freight Costs & Shipment Weight

<details>
<summary><strong>Explore freight costs, shipment weights and transportation patterns</strong></summary>

**05. Distribution of Freight Cost (USD)**

![Freight Cost Distribution](preview/05-freight-cost-distribution-usd.png)

**06. Distribution of Shipment Weight (kg)**

![Shipment Weight Distribution](preview/06-shipment-weight-distribution-kg.png)

**07. Freight Cost Distribution by Shipment Mode**

![Freight Cost by Shipment Mode](preview/07-freight-cost-by-shipment-mode.png)

**08. Shipment Weight vs. Freight Cost**

![Shipment Weight vs Freight Cost](preview/08-shipment-weight-vs-freight-cost.png)

**11. Shipment Weight Distribution by Shipment Mode**

![Shipment Weight Distribution by Mode](preview/11-shipment-weight-distribution-by-mode.png)

**12. Shipment Weight vs. Freight Cost Analysis**

![Shipment Weight vs Freight Cost Analysis](preview/12-shipment-weight-vs-freight-cost-analysis.png)

</details>

### 3. Statistical Analysis & Data Quality

<details>
<summary><strong>Explore statistical relationships and dataset quality</strong></summary>

**13. Shipment Mode Distribution**

![Shipment Mode Distribution](preview/13-shipment-mode-distribution.png)

**14. Correlation Heatmap of Key Logistics Variables**

![Correlation Heatmap](preview/14-correlation-heatmap-logistics-variables.png)

**15. Pair Plot of Logistics Variables**

![Pair Plot](preview/15-pair-plot-logistics-variables.png)

**16. Missing Values by Feature**

![Missing Values by Feature](preview/16-missing-values-by-feature.png)

**17. Statistical Summary — Numerical Features**

![Statistical Summary](preview/17-statistical-summary-numerical-features.png)

</details>

---

## 🔎 Analytical Workflow

1. **Data loading:** Load the supply chain dataset into Google Colab.
2. **Data inspection:** Examine dataset dimensions, column names, data types and sample records.
3. **Data-quality assessment:** Review missing values, duplicates and potential inconsistencies.
4. **Data preparation:** Identify relevant numerical and categorical features.
5. **Descriptive statistics:** Summarize numerical features and distributions.
6. **Exploratory analysis:** Investigate shipment modes, destinations, vendors, manufacturing sites, freight costs and weights.
7. **Visualization:** Create charts to communicate patterns and relationships.
8. **Interpretation:** Review the analytical results and identify potential operational insights.

## 💡 Business Applications

The analysis provides a foundation for investigating:

- Shipment concentration across destination countries.
- Differences in shipment activity across transportation modes.
- Freight-cost variation across destinations and modes.
- Relationships between shipment weight and freight cost.
- Shipment contributions from vendors and manufacturing sites.
- Missing data that may affect reporting and analytical reliability.

*Business conclusions should be based on the actual metrics and findings produced by the notebook.*

## 📁 Repository Structure

```text
Fed-ex/
│
├── README.md
├── Sample_EDA_Submission_Template.ipynb
├── requirements.txt
│
└── preview/
    ├── Fed-ex-logo.png
    ├── 01-top-10-destination-countries-by-shipments.png
    ├── 02-shipment-distribution-by-mode.png
    ├── 03-top-10-vendors-by-shipments.png
    ├── 04-top-10-manufacturing-sites-by-shipments.png
    ├── 05-freight-cost-distribution-usd.png
    ├── 06-shipment-weight-distribution-kg.png
    ├── 07-freight-cost-by-shipment-mode.png
    ├── 08-shipment-weight-vs-freight-cost.png
    ├── 09-top-10-destination-countries-by-average-freight-cost.png
    ├── 10-top-15-destination-countries-by-shipment-count.png
    ├── 11-shipment-weight-distribution-by-mode.png
    ├── 12-shipment-weight-vs-freight-cost-analysis.png
    ├── 13-shipment-mode-distribution.png
    ├── 14-correlation-heatmap-logistics-variables.png
    ├── 15-pair-plot-logistics-variables.png
    ├── 16-missing-values-by-feature.png
    └── 17-statistical-summary-numerical-features.png
```

**Important:** The image names in this structure must match the actual uploaded files exactly, including capitalization and file extensions. If your logo has a different filename, update its image path accordingly.

## ▶️ How to Run the Notebook

1. Open `Sample_EDA_Submission_Template.ipynb` in your GitHub repository.
2. Open [Google Colab](https://colab.research.google.com/) and upload the notebook if needed.
3. Upload or mount the dataset required by the notebook.
4. Check that dataset paths in the notebook match your files.
5. Run the notebook cells in sequence.

## 📦 Requirements

For a local Python environment, use the following `requirements.txt`:

```text
pandas
numpy
matplotlib
seaborn
plotly
```

Google Colab already includes many common data-analysis libraries. Install any missing dependencies before running the notebook.

## 👤 Project Information

| Field | Details |
|---|---|
| Project Name | FedEx Logistics Operations Analysis |
| Project Type | Individual Project |
| Domain | Logistics & Supply Chain Analytics |
| Development Environment | Google Colab |
| Author | Ayush Dash |

## 🚀 Future Enhancements

- Document key findings using validated metrics from the analysis.
- Improve reproducibility through a structured data-cleaning workflow.
- Apply suitable statistical tests when the data supports them.
- Extend interactive visualizations where they add analytical value.
- Develop a logistics KPI dashboard if the available data supports it.

## 📄 License

A license has not yet been specified. Add a `LICENSE` file if you intend to define how others may use, modify or distribute this project.

---

<p align="center">
  <strong>FedEx Logistics Operations Analysis</strong><br>
  <sub>Exploratory Data Analysis for Supply Chain Insights</sub>
</p>

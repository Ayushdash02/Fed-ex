# FedEx Logistics Operations Analysis

<p align="center">
  <img src="preview/Fed-ex-logo.png" alt="FedEx Logo" width="210">
</p>

<p align="center">
  <strong>Exploratory Data Analysis | Logistics Intelligence | Supply Chain Analytics</strong>
</p>

<p align="center">
  <em>Transforming shipment data into meaningful operational insights.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-Analytics-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Google%20Colab-Notebook-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" alt="Google Colab">
  <img src="https://img.shields.io/badge/Project-EDA-475569?style=for-the-badge" alt="EDA">
</p>

---

## 01. Executive Summary

**FedEx Logistics Operations Analysis** is a data analytics project focused on exploring logistics and supply chain shipment data to understand operational patterns, freight-cost distributions, shipment characteristics, and data quality.

The project uses Python-based exploratory data analysis (EDA) to investigate shipment volumes by destination, transportation mode, vendor, and manufacturing site. It also examines freight costs, shipment weights, numerical relationships, missing values, and descriptive statistics.

The objective is to develop a structured understanding of the available data, identify patterns that warrant further investigation, and demonstrate a reproducible analytical workflow.

**Analytical approach:** Data inspection → Data quality assessment → Exploratory analysis → Statistical profiling → Visualization → Interpretation.

## 02. Business Context

Logistics data contains information that can help analysts investigate shipment distribution, transportation activity, freight costs, and operational data quality.

This project approaches the dataset from a business analyst's perspective by organizing the exploration around specific questions rather than producing visualizations without context.

### Business Questions

| Business Area | Analytical Question |
|---|---|
| Destination Analysis | Which destination countries have the highest shipment counts? |
| Transportation Analysis | How are shipments distributed across shipment modes? |
| Vendor Analysis | Which vendors account for the largest shipment volumes? |
| Manufacturing Analysis | Which manufacturing sites contribute the most shipments? |
| Freight Cost Analysis | How are freight costs distributed, and how do they vary across shipment categories? |
| Shipment Weight Analysis | What patterns exist in shipment weights, and how are they associated with freight costs? |
| Statistical Analysis | What relationships appear among the numerical logistics variables? |
| Data Quality | Which features contain missing values, and what do the numerical summaries reveal? |

## 03. Project Objectives

- Examine shipment-volume patterns across destinations and operational categories.
- Compare shipment distributions across transportation modes.
- Analyze vendor and manufacturing-site shipment contributions.
- Explore freight-cost and shipment-weight distributions.
- Investigate the association between shipment weight and freight cost.
- Compare destination countries by shipment count and average freight cost.
- Assess correlations among selected numerical variables.
- Evaluate missing values and summarize numerical features.
- Communicate the analysis through clear, documented visualizations.

## 04. Technology Stack

| Technology | Analytical Application |
|---|---|
| Python | Core analytical programming |
| Google Colab | Notebook development and execution |
| Pandas | Data inspection, manipulation, and tabular analysis |
| NumPy | Numerical operations |
| Matplotlib | Chart creation |
| Seaborn | Statistical visualization and correlation analysis |
| Plotly | Interactive visualizations, where implemented |

---

## 05. Exploratory Data Analysis — Visualization Gallery

The following visualizations are organized by analytical purpose. All image references use the repository's `preview/` directory.

### 5.1 Shipment Distribution & Operational Network

These visualizations examine shipment volumes across destinations, shipment modes, vendors, and manufacturing sites.

<details>
<summary><strong>View operational analysis visualizations</strong></summary>

#### 01. Top 10 Destination Countries by Shipments

![Top 10 Destination Countries by Shipments](preview/01-top-10-destination-countries-by-shipments.png)

#### 02. Shipment Distribution by Mode

![Shipment Distribution by Mode](preview/02-shipment-distribution-by-mode.png)

#### 03. Top 10 Vendors by Shipments

![Top 10 Vendors by Shipments](preview/03-top-10-vendors-by-shipments.png)

#### 04. Top 10 Manufacturing Sites by Shipments

![Top 10 Manufacturing Sites by Shipments](preview/04-top-10-manufacturing-sites-by-shipments.png)

#### 09. Top 10 Destination Countries by Average Freight Cost

![Top 10 Destination Countries by Average Freight Cost](preview/09-top-10-destination-countries-by-average-freight-cost.png)

#### 10. Top 15 Destination Countries by Shipment Count

![Top 15 Destination Countries by Shipment Count](preview/10-top-15-destination-countries-by-shipment-count.png)

</details>

### 5.2 Freight Cost & Shipment Weight

These charts explore freight-cost distributions, shipment weights, mode-level cost differences, and the relationship between weight and freight cost.

<details>
<summary><strong>View freight-cost and shipment-weight visualizations</strong></summary>

#### 05. Freight Cost Distribution (USD)

![Freight Cost Distribution](preview/05-freight-cost-distribution-usd.png)

#### 06. Shipment Weight Distribution (kg)

![Shipment Weight Distribution](preview/06-shipment-weight-distribution-kg.png)

#### 07. Freight Cost by Shipment Mode

![Freight Cost by Shipment Mode](preview/07-freight-cost-by-shipment-mode.png)

#### 08. Shipment Weight vs. Freight Cost

![Shipment Weight vs Freight Cost](preview/08-shipment-weight-vs-freight-cost.png)

#### 11. Shipment Weight Distribution by Mode

![Shipment Weight Distribution by Mode](preview/11-shipment-weight-distribution-by-mode.png)

#### 12. Shipment Weight vs. Freight Cost Analysis

![Shipment Weight vs Freight Cost Analysis](preview/12-shipment-weight-vs-freight-cost-analysis.png)

</details>

### 5.3 Statistical Profiling & Data Quality

These visualizations support the examination of shipment categories, numerical relationships, missing data, and feature distributions.

<details>
<summary><strong>View statistical and data-quality visualizations</strong></summary>

#### 13. Shipment Mode Distribution

![Shipment Mode Distribution](preview/13-shipment-mode-distribution.png)

#### 14. Correlation Heatmap of Logistics Variables

![Correlation Heatmap](preview/14-correlation-heatmap-logistics-variables.png)

#### 15. Pair Plot of Logistics Variables

![Pair Plot of Logistics Variables](preview/15-pair-plot-logistics-variables.png)

#### 16. Missing Values by Feature

![Missing Values by Feature](preview/16-missing-values-by-feature.png)

#### 17. Statistical Summary — Numerical Features

![Statistical Summary of Numerical Features](preview/17-statistical-summary-numerical-features.png)

</details>

---

## 06. Analytical Methodology

The project follows a structured exploratory workflow.

| Stage | Activity | Purpose |
|---|---|---|
| 01 | Data Inspection | Understand the dataset's structure, columns, and data types |
| 02 | Data Quality Assessment | Examine missing values, duplicates, and potential inconsistencies |
| 03 | Descriptive Statistics | Understand numerical distributions and summary measures |
| 04 | Categorical Analysis | Explore shipment counts by destination, mode, vendor, and site |
| 05 | Cost & Weight Analysis | Examine freight costs, weights, and their association |
| 06 | Correlation Analysis | Identify associations among selected numerical variables |
| 07 | Visualization | Communicate patterns through graphical analysis |
| 08 | Interpretation | Identify evidence-based questions and potential follow-up analyses |

## 07. Analyst's Interpretation Framework

Professional analysis requires distinguishing what a visualization shows from what can reasonably be concluded from it.

- **Shipment volume:** A high shipment count indicates greater recorded activity, not necessarily higher profitability or better service.
- **Freight cost:** Cost comparisons should account for differences in shipment weight, mode, destination, and other relevant factors where data is available.
- **Weight and cost:** Correlation indicates association, not proof that shipment weight alone determines freight cost.
- **Vendor rankings:** Shipment volume does not independently measure vendor quality, delivery reliability, or efficiency.
- **Missing values:** Missingness should be investigated before removing records or imputing values.
- **Statistical summaries:** Measures such as mean, median, standard deviation, and quartiles help characterize distributions but should be interpreted in context.

> **Evidence standard:** The README describes the scope of the analysis. Specific numerical findings and business recommendations should be added only after verifying the notebook's results.

## 08. Potential Business Applications

The analytical methods used in this project can provide a foundation for:

- Monitoring shipment-volume distribution by destination and mode.
- Investigating freight-cost variation across comparable shipment groups.
- Reviewing activity across vendors and manufacturing sites.
- Identifying unusual shipment weights or freight costs for further examination.
- Improving data-quality checks and reporting reliability.
- Defining candidate metrics for a future logistics dashboard.

These are potential applications, not claims of measured operational improvements.

## 09. Repository Structure

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

**Image paths:** All visualization references assume the filenames above exist inside `preview/`. GitHub paths are case-sensitive. If your actual files have different names or extensions, update the corresponding image links.

## 10. Reproducing the Analysis

1. Open `Sample_EDA_Submission_Template.ipynb` from the repository.
2. Open the notebook in [Google Colab](https://colab.research.google.com/).
3. Upload or mount the dataset required by the notebook.
4. Verify the dataset filename and file path referenced in the code.
5. Execute the notebook cells in order.
6. Review the outputs and compare them with the visualizations documented above.

### Dependencies

For a local Python environment, the `requirements.txt` file can contain:

```text
pandas
numpy
matplotlib
seaborn
plotly
```

Google Colab commonly includes these libraries. Install any missing dependencies before running the notebook.

## 11. Project Information

| Attribute | Details |
|---|---|
| Project Title | FedEx Logistics Operations Analysis |
| Project Category | Exploratory Data Analysis |
| Domain | Logistics & Supply Chain Analytics |
| Environment | Google Colab |
| Language | Python |
| Author | Ayush Dash |

## 12. Limitations & Future Scope

The strength of the conclusions depends on the dataset's completeness, variable definitions, and the analytical methods implemented in the notebook.

Potential next steps include:

- Add verified findings with key metrics and chart-specific interpretations.
- Document cleaning decisions and data-validation rules.
- Apply appropriate statistical tests where assumptions and data support them.
- Investigate additional cost drivers if relevant variables are available.
- Develop a KPI dashboard if the dataset supports reliable measures and time-based analysis.

## License

No license is currently specified. Add a `LICENSE` file if you intend to define permissions for using, modifying, or redistributing this project.

---

<p align="center">
  <strong>FedEx Logistics Operations Analysis</strong><br>
  <sub>Data exploration for evidence-based supply chain insights</sub>
</p>

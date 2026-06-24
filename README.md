# 🐍 Algorithmic Problem Solving & Quantitative Data Manipulation (Python & Pandas)

## 📌 Project Background & Context

* **Role:** Associate Data Analyst (Data Analyst Bootcamp Client Project)
* **Stakeholder Audience:** Operations Management & Business Intelligence Teams
* **Context:** As a core technical milestone within my intensive Data Analyst Bootcamp, I completed a series of programmatic data pipelines and core automation scripts using Python and the Pandas library. Transitioning from visual BI interfaces to programmatic execution, this project required using Google Colab and Jupyter Notebook environments to engineer algorithmic business logic (such as validation systems and conditional loops) and execute vectorized data cleansing on messy retail and vehicle datasets. The ultimate goal was to replace manual file manipulation with reproducible, automated data engineering workflows.

---

## 📑 Executive Summary

This development repository contains a modular collection of production-ready Python automation scripts and structured Pandas analysis tasks. The initial modules focus on foundational programmatic structures, implementing data type control frameworks, validation loops, and error-handling menu interfaces to process direct user inputs cleanly.

The core of the project applies advanced Pandas workflows to process transactional product sales logs and legacy automotive metrics. By engineering data hygiene functions, applying targeted conditional indexing, and calculating weighted variables, this setup transforms messy raw tables into clean, structured datasets ready for corporate reporting. These programmatic assets eliminate repetitive manual tracking tasks, giving downstream stakeholders instant access to cleaner business data.

---

## 🛠️ Technical Workflow & Practical Applications

During my bootcamp training, I developed automated logic and clean data transformations to replace manual file processing workflows:

### 1. Algorithmic Business Logic & Flow Control
* **Security & Access Validation:** Coded validation controls using conditional multi-branch processing (`if`, `elif`, `else`) to securely verify incoming strings and manage access logic based on defined criteria.
* **Menu-Driven Interface Automation:** Built user-driven calculator tools inside persistent `while` loops, combining evaluation logic and custom loop control techniques (`break`) to keep programs running continuously without system crashes.
* **Mathematical Operations:** Applied logical computational structures to resolve programmatic mathematical challenges, engineering factorial calculators, prime number identifiers, and loop-generated numerical tracking arrays using the `range()` function.

### 2. Programmatic Data Hygiene & Engineering (Pandas)
* **Vectorized Data Cleansing:** Created Pandas DataFrames to systematically rename unformatted headers, transform legacy text strings into proper datetime/numerical data types, and clean dirty currency indicators for financial reporting.
* **Calculated Metrics & Boolean Masking:** Avoided slow row-by-row iteration by deploying vectorized arrays to compute total revenue performance (pricing × volume shares) and fuel economy indicators. Used high-performance Boolean masks to isolate data slices, such as segmenting vehicle transmission variables and filtering rows outperforming median baseline metrics.

---

## 📂 Repository Architecture & Workspace

### 🖼️ Environment Infrastructure
The workspace snapshot below highlights the production layout of my development scripts hosted on GitHub, showcasing clean version control, modular script execution blocks, and unified project notebook delivery:

### 💾 Core Development Assets:
* **`MAY_2026_KKS_DAY_2_1_1_Pandas...`**: Core structural data manipulation scripts handling multi-field DataFrame parsing and automated file exports.
* **`MAY_26_KKS_Python_Day_2_1_2...`**: Targeted vectorization testing notebooks optimizing column operations and cleansing metrics.
* **`MAY_26_KKS_Python_Day_3_Master...`**: Core loop architectures, advanced Boolean masks, and segmented data filtering scripts.
* **`MAY_26_KKS_Python_Day_4_Task...`**: Practical application labs executing product revenue metrics and statistical summaries.
* **`Python_Master.ipynb`**: The master compilation notebook consolidating interactive programs, custom business logic, and mathematical problem-solving assets.

---

## 📊 Core Analytical Applications & Logic Examples

### 💻 Automated Value Profiling & Logic
To handle programmatic threshold segmentations without human error, I deployed conditional evaluation metrics inside the data pipeline:

```python
# Programmatic validation tracking example
def assess_customer_velocity(order_volume):
    if order_volume > 10:
        return 'High Frequency Client'
    elif 5 <= order_volume <= 10:
        return 'Medium Frequency Client'
    else:
        return 'Low Frequency Client'

# Applied immediately across the entire tracking column via Pandas
df['customer_tier'] = df['total_orders'].apply(assess_customer_velocity)

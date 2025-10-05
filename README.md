
# 📘 Big Data Analytics Project: Property Crime Analysis (2001–2010)

[](https://www.python.org/)
[](https://spark.apache.org/docs/latest/api/python/index.html)
[](https://opensource.org/licenses/MIT)

## 🌟 Project Overview

This project is a comprehensive Big Data Analytics study focused on analyzing **Property Stolen and Recovered** data across India from **2001 to 2010**.

Leveraging the power of **PySpark**, the analysis cleans, transforms, and aggregates massive crime statistics to derive critical metrics related to crime patterns and law enforcement efficiency.

### 🎯 Key Objectives

1.  **Pattern Identification:** Determine the dominant types of property crime (Theft, Burglary, etc.).
2.  **Trend Analysis:** Track the year-over-year change in total property crime over the decade.
3.  **Recovery Evaluation:** Calculate and compare **Property Recovery Rates** (by cases and value) to assess regional law enforcement effectiveness.

## 💡 Key Analytical Findings

The PySpark analysis transformed raw statistics into these core insights:

| Finding | Detail | Implication |
| :--- | :--- | :--- |
| **Dominant Crime Type** | **Theft** is the single largest specific crime head, accounting for approximately **65.5%** of all reported property crime cases. | Strategy must focus heavily on **non-violent, opportunity-based crime** prevention (e.g., surveillance, securing movable assets). |
| **Decadal Trend** | Total property crime cases saw a net increase of nearly **20%** between 2001 and 2010, peaking at the end of the decade. | The overall challenge grew significantly, demanding updated, data-driven policing models. |
| **Data Quality** | The raw dataset demonstrated **100% completeness** (no missing values) and **100% uniqueness** (no duplicate rows), providing a highly reliable foundation for analysis. | The results are built on a robust, high-quality data foundation. |

## 🛠️ Tools and Technologies

This project is built on a scalable Big Data stack suitable for processing large analytical workloads.

  * **Primary Framework:** **Apache PySpark** (for distributed data processing and transformation).
  * **Environment:** Jupyter Notebook (`.ipynb`).
  * **Core Libraries:** Pandas (for initial checks/visualization prep), NumPy.

## 💾 Dataset

The analysis uses the following dataset:

  * **File:** `10_Property_stolen_and_recovered.csv`
  * **Source:** Government Crime Statistics (India)
  * **Scope:** Records across all Indian States and Union Territories from 2001 to 2010.
  * **Key Fields:** `Area_Name`, `Year`, `Group_Name` (e.g., Theft, Burglary), `Cases_Property_Stolen`, `Value_of_Property_Stolen`, and corresponding `Recovered` columns.

## 📁 Repository Structure for project

```
Big-Data-Analytics/
├── PROPERTY CRIME ANALYSIS PROJECT 
               ├──10_Property_stolen_and_recovered.csv
               ├── PPT
               ├── PROJECT REPORT
               ├── Property Crime Analysis Project
```

## 🚀 How to Run the Project

To replicate the analysis, follow these steps:

### Prerequisites

1.  **Install Apache Spark:** Ensure you have a working installation of Apache Spark on your system (or a cluster).
2.  **Install PySpark:** Install the PySpark library via pip:
    ```bash
    pip install pyspark pandas
    ```

### Execution

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/MONIS1234/Big-Data-Analytics.git
    cd Big-Data-Analytics
    ```
2.  **Open the Notebook:** Launch Jupyter Notebook and open the file `Property_crime_analysis_project.ipynb`.
3.  **Run Cells:** Execute the cells sequentially. The notebook initializes the SparkSession, loads the data, performs cleaning, calculates derived features (Recovery Rates), and executes the final aggregation and analysis queries.

-----

### **Submitted By:** S.MONIS (2211CS010502)

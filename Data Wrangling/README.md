# San Francisco Public Library Patron Usage Analysis (Data Wrangling)

## Overview
This project focuses on **data wrangling and exploratory data analysis (EDA)** using the **San Francisco Public Library Patron Usage** dataset. The analysis demonstrates how raw, real-world public-sector data can be cleaned, standardized, and transformed into an analysis-ready format.

Using **Pandas**, **Matplotlib**, and **Seaborn**, the project explores **patron behavior patterns** across age groups, patron types, and library branches while emphasizing best practices in data quality, feature engineering, and reproducible analysis.

---

## Objective
To clean, preprocess, and analyze public library usage data by applying data wrangling techniques and exploratory analysis, enabling meaningful insights into patron engagement and supporting data-driven decision-making for library services.

---

## Data Source
- **Library_Usage.csv**
  - Dataset from Kaggle: [San Francisco Public Library Usage dataset](https://www.kaggle.com/datasets/datasf/sf-library-usage-data?select=Library_Usage.csv)
  - Contains patron demographics, usage metrics, and activity history
  - Represents real-world, messy operational data

---

## Methods & Tools Used
- Data cleaning and preprocessing
- Duplicate detection and removal
- Missing value handling using logical assumptions
- Feature engineering for behavioral analysis
- Outlier identification and resolution
- Exploratory data analysis using visualizations

---

## Programming Environment
- Python 3.12
- Jupyter Notebook

---

## Libraries Used
- **Data Manipulation:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  

---

## Workflow (End-to-End Pipeline)

1. Load library usage dataset using Pandas  
2. Inspect data structure, data types, and missing values  
3. Identify and remove duplicate records  
4. Handle missing values based on domain logic and assumptions  
5. Convert and standardize data types and text fields  
6. Perform feature engineering:
   - Total Activity
   - Patron Tenure
   - Recent Activity indicators  
7. Conduct exploratory data analysis (EDA) using visualizations  
8. Resolve outliers impacting analysis reliability  
9. Export the cleaned dataset for downstream analysis or modeling  

---

## Project Structure
```text
├── library_data_wrangling.ipynb   # Data cleaning, EDA, and feature engineering
├── Library_Usage.csv              # Raw dataset (Kaggle: Library Usage)
├── requirements.txt               # Project dependencies
├── README.md                      # Project documentation
└── LICENSE                        # MIT License
```

---

## Results & Insights
- Successfully transformed raw public-sector data into a clean, analysis-ready dataset
- Identified usage patterns across: Age groups, Patron types, Library branches
- Feature engineering revealed differences in engagement and tenure among patrons
- Visualizations highlighted trends, anomalies, and outliers impacting interpretation
- Demonstrated the importance of data quality in real-world analytics

---

## Practical Applications
- Public library usage analysis and reporting
- Data-driven planning for library services and resource allocation
- Patron engagement and retention analysis
- Foundational dataset preparation for predictive modeling
- Example of real-world data wrangling for analytics roles

---

## How to Run This Project
1. Clone the repository: *git clone https://github.com/yourusername/your-repo-name.git*
2. Open the notebook: *jupyter notebook library_data_wrangling.ipynb*
3. Run all cells sequentially to reproduce the analysis

---

## Future Enhancements
- Apply predictive modeling to identify high-engagement patrons
- Cluster patrons based on usage behavior
- Build interactive dashboards for operational insights
- Integrate geospatial analysis for branch-level planning
- Extend analysis to longitudinal usage trends


### License
This project is licensed under the MIT License.

**Ethical Use Notice:**
This project is intended for educational, research, and professional learning purposes.
Misrepresentation of authorship or deceptive use is unethical. Attribution is required under the MIT License.
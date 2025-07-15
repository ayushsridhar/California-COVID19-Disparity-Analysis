# California COVID-19 Demographic Disparity Analysis

This project analyzes public health data from the California Health & Human Services (CHHS) portal to investigate disparities in COVID-19 vaccination, case, and death rates across different demographic groups (age, race/ethnicity, and gender).

The analysis involves loading, cleaning, and visualizing over 100,000 records to identify key trends and areas of inequity in public health outcomes during the pandemic.

---

### **Key Findings**

This analysis culminated in a published research paper, which found significant disparities in public health outcomes. Key takeaways include:

* **Vaccination Gaps:** Lower vaccination rates were consistently observed among minority populations, particularly Hispanic/Latino and African American communities, when compared to their share of the state's population.
* **Age-Related Risk:** While younger populations (18-49) accounted for a disproportionately high percentage of total cases, mortality rates were overwhelmingly concentrated in the elderly (65+).
* **Gender Differences:** A consistent trend of higher vaccination rates among females compared to males was observed across all vaccine dosage metrics.

**Published Paper:** [View the full paper here (DOI: 10.58445/rars.670)](https://research-archive.org/index.php/rars/preprint/view/670/1050)

---

### **Technologies Used**

* **Python:** The core language for the analysis.
* **Pandas:** Used for data loading, cleaning, manipulation, and aggregation.
* **NumPy:** Used for numerical operations.
* **Matplotlib:** Used for generating all data visualizations.
* **Jupyter Notebook:** The environment for conducting the analysis.

---

### **How to Run This Project**

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ayushsridhar/California-COVID19-Disparity-Analysis.git](https://github.com/ayushsridhar/California-COVID19-Disparity-Analysis.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy matplotlib
    ```
3.  **Place data:** Ensure the raw data CSV files (`DemographicVaccineData.csv`, `DemographicCovidDeathData.csv`) are located inside the `data/` subfolder.
4.  **Run the notebook:** Open and run the `covid_analysis_notebook.ipynb` file in a Jupyter environment like Jupyter Lab or VS Code.
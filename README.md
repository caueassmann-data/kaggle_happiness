# World Happiness Report Analysi

This repository contains a detailed analysis of the **World Happiness Report** data, spanning from 2005 to 2025. The project explores global well-being trends and the socio-economic factors that influence happiness scores across different nations.

## 📌 Project Overview

The primary goal of this analysis is to understand how variables such as GDP per capita, social support, healthy life expectancy, freedom, generosity, and perceptions of corruption impact the perception of happiness worldwide.

The analysis was developed in a Jupyter Notebook environment, utilizing data cleaning techniques, interactive visualizations, and statistical modeling.

## 📊 Analysis Performed

1.  **Data Exploration:** Identification of missing values and initial descriptive analysis.
2.  **Data Preprocessing:** Data imputation using the `backfill` method for time series and validation against cleaned data.
3.  **Interactive Visualizations:** 
    *   Interactive world map (Choropleth) showing the evolution of the happiness index over the years.
    *   Scatter plots with trend lines to correlate specific factors.
4.  **Correlation Analysis:** Heatmap to identify which factors have the greatest weight on global happiness.
5.  **Linear Regression:** Statistical modeling to quantify how much the explanatory factors (GDP, Social Support, etc.) account for the variation in the total score.
6.  **Recent Trend Analysis:** Identification of countries that showed the largest drops in the happiness index between 2020 and 2025 (e.g., Afghanistan, Lebanon).

## 📂 Repository Structure

*   `happiness_kaggle.ipynb`: Main notebook containing all analysis code and visualizations.
*   `world_happiness_report_2005_2025.csv`: The dataset used in the project.

## 🛠️ Technologies Used

*   **Language:** Python 3.x
*   **Data Manipulation:** `Pandas`, `NumPy`
*   **Visualization:** `Plotly Express`, `Seaborn`, `Matplotlib`
*   **Machine Learning (Statistics):** `Scikit-learn` (Linear Regression)

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/happiness-analysis.git
   ```
2. Install the necessary dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly scikit-learn
   ```
3. Open the `happiness_kaggle.ipynb` file in your Jupyter environment or Google Colab to view the complete analysis.

## 📈 Results and Conclusions

The analysis demonstrated that Log GDP per capita and Social Support are the factors with the highest positive correlation with happiness scores. Furthermore, mathematical validation confirmed that the final happiness score is the direct sum of the explanatory factors plus the residual component (Dystopia).

---
*This project was developed as part of academic activities/data science studies.*

# 📘 **README: GDP & Life Expectancy Analysis**  

## 📌 **Overview**  
This project explores the relationship between **GDP and Life Expectancy** across multiple countries using data from the **World Health Organization** and the **World Bank**. The goal is to **identify patterns and insights** that can help public health officials and policymakers make data-driven decisions.

## 📊 **Dataset Description**  
The dataset includes GDP and life expectancy data for multiple countries over different years. The key columns are:

| Column Name                   | Description |
|--------------------------------|-------------|
| **Country**                   | Name of the country |
| **Year**                      | Year of data collection |
| **Life_Expectancy**           | Average life expectancy at birth (years) |
| **GDP**                       | Gross Domestic Product (USD) |

## 🎯 **Objectives of the Analysis**
- Examine the **correlation** between GDP and life expectancy.
- Use **logarithmic transformations** to check for non-linear relationships.
- Perform **regression analysis** to estimate **the effect of GDP on life expectancy**.
- Create **visualizations** to communicate insights effectively.

## 🛠 **Technologies & Libraries Used**
- **Python 3.x**
- **Pandas** – Data processing and cleaning
- **NumPy** – Mathematical computations
- **Matplotlib & Seaborn** – Data visualization
- **Statsmodels** – Statistical modeling (OLS Regression)
- **Google Colab** – Execution environment
- **GitHub** – Version control and project sharing

## 📌 **How to Run the Analysis**
1. **Clone the repository** (if hosted on GitHub):
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
   cd YOUR_REPO
   ```
2. **Upload the dataset** (`all_data.csv`) to your Google Colab environment.
3. **Run the Jupyter notebook or Python script**:
   ```bash
   python gdp_life_expectancy_analysis.py
   ```
4. **Review the output visualizations and model summary.**

## 📈 **Key Findings**
### 🔥 **Correlation Analysis**
- GDP has a **strong positive correlation** with life expectancy.
- High-income countries tend to have **higher life expectancy**, while low-income countries experience **greater variation**.

### 📉 **Regression Analysis (OLS Model)**
- **Log(GDP) significantly predicts life expectancy (p < 0.001)**.
- For every **unit increase in Log(GDP), life expectancy increases by ~3.36 years**.
- However, diminishing returns are observed in **high-income** countries.

### 📊 **Visualizations**
- **Heatmap** of correlation between GDP and Life Expectancy.
- **Scatter Plot** showing the impact of GDP on life expectancy.
- **Regression Model** with predicted trends.

## 🔍 **Next Steps & Enhancements**
- **Expand dataset** to include more years and countries.
- **Incorporate additional health indicators**, such as **education levels, healthcare access, and pollution levels**.
- **Apply machine learning models** (e.g., Random Forest, XGBoost) for more accurate predictions.

## 🏆 **Contributions & License**
- Contributions are welcome! Feel free to fork and submit pull requests.
- Licensed under **MIT License** – free to use and modify.

## 📩 **Contact**
For any inquiries, reach out via:
- **Email**: aicoaching2025@gmail.com
- **GitHub**: https://www.linkedin.com/in/candace215

---

✅ **Project Complete!** Feel free to run the analysis, explore the data, and contribute! 🚀

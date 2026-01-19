#  Task 3: Advertising Sales Prediction using Machine Learning

##  Project Overview
The objective of this project is to build a predictive model that estimates sales based on advertising expenditures across three
main platforms: **TV, Radio, and Newspaper**. This project demonstrates how data-driven decisions can help businesses allocate their marketing
budgets more effectively to maximize revenue (ROI).

---

##  Technical Workflow

### 1. Data Exploration & Inspection
- **Source:** The dataset consists of advertising budgets and resulting sales for 200 different markets.
- **Initial Check:** Conducted statistical analysis using `.describe()` to understand data distribution and verified zero missing values using `.isnull()`.

### 2. Exploratory Data Analysis (EDA)
To understand the relationship between features and the target variable (Sales), I performed:
- **Correlation Heatmap:** Visualized the strong positive correlation between TV advertising and Sales.
- **Pairplots & Regression Plots:** Analyzed the linear trends using Seaborn to confirm if the data follows a linear pattern.
- **Outlier Detection:** Used Boxplots to ensure the data was clean and free from extreme values that could skew the model.



### 3. Advanced Feature Engineering
To provide more depth to the analysis, I introduced a new feature:
- **`Total_Spend`**: Sum of TV, Radio, and Newspaper expenditures. This helps in understanding the cumulative impact of the entire marketing mix on sales performance.

### 4. Model Development
- **Algorithm:** Linear Regression.
- **Data Splitting:** 80% Training and 20% Testing.
- **Training:** The model was trained to identify the optimal coefficients for each advertising channel.

### 5. Rigorous Model Evaluation
Unlike basic projects, I used multiple metrics to ensure reliability:
- **R-Squared Score:** **89.94%** (Explains the variance in sales accurately).
- **Mean Absolute Error (MAE):** **1.46** (Indicates low average prediction error).
- **Cross-Validation:** Performed **5-Fold Cross-Validation**, achieving a consistent score of **88.71%**, which confirms that the model is stable and not overfitting.


---

##  Actionable Business Insights
Based on the model coefficients, the following strategies are recommended:
1. **Prioritize TV:** TV advertising has the highest impact on driving sales volume.
2. **Optimize Radio:** Radio has a high "Impact Factor" per unit of investment, making it a very cost-effective channel.
3. **Re-evaluate Newspaper:** Newspaper ads showed minimal correlation with sales, suggesting the budget could be redirected to more profitable channels.

---

##  Contact & Connect
- **LinkedIn:** https://www.linkedin.com/in/kumarimeena
- **Internship Provider:** https://www.codealpha.tech

*Thank you for visiting my repository! Feel free to explore the folders for detailed code and documentation.*


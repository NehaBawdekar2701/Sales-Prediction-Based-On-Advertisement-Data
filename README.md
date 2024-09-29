# Sales-Prediction-Based-On-Advertisement-Data
 The project aims to predict sales based on advertising budgets, specifically from TV, radio, and newspaper ads. The dataset contains columns like:TV Ad Budget ($),Radio Ad Budget ($),Newspaper Ad Budget ($),Sales
 
**Steps in the Project:**

**1)Libraries Import:**
pandas, numpy, seaborn, and matplotlib are imported for data manipulation, analysis, and visualization.

**2)Data Loading:**
The dataset is loaded from a CSV file using pandas.
Initial exploratory steps include checking data types, shape, summary statistics (df.describe()), and identifying missing values.

**3)Data Cleaning:**
The column Unnamed: 0, which seems irrelevant, is dropped.
Missing values are checked, though no specific handling is mentioned.

**4)Exploratory Data Analysis (EDA):**
Distribution of Features: The distribution of TV, Radio, Newspaper budgets, and Sales is visualized using histograms with sns.histplot().

**5)Relationships between Variables:** 
Scatter plots (using sns.pairplot()) are used to analyze the relationship between ad budgets and sales.
Correlation Analysis: A heatmap is generated to visualize the correlations between the features.

**6)Modeling Approach:**
A regression model is used to predict sales based on the advertisement budgets.
Variance Inflation Factor (VIF): VIF is computed to check for multicollinearity between independent variables. The VIF values being less than 5 suggests that there’s no significant multicollinearity.

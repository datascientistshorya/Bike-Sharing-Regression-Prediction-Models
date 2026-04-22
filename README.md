🚴 Bike Sharing Demand Prediction (OLS & Linear Regression)
📌 Project Overview
This project focuses on building a robust regression framework to predict bike rental demand using the Bike Sharing dataset. The goal was to develop a model that not only performs well but is also interpretable, enabling clear insights into the factors influencing demand.
We combined statistical modeling (OLS) with machine learning (Linear Regression) to strike a balance between explainability and predictive performance.

🎯 Problem Statement
Accurately predicting bike rental demand is critical for:


Optimizing inventory and availability


Improving operational efficiency


Enhancing customer experience


This project aims to model demand patterns using historical data and uncover key drivers behind rental behavior.

🧠 Workflow & Methodology
1. Data Preprocessing


Converted and processed date features


Extracted meaningful variables (e.g., month, temporal indicators)


Identified categorical vs numerical features


Handled missing values and ensured data consistency



2. Feature Engineering


Applied One-Hot Encoding to categorical variables
→ Enabled models to interpret non-numeric categories


Scaled numerical features
→ Ensured uniform feature contribution and improved model stability



3. Train-Test Split


Split dataset into training and testing sets


Ensured unbiased model evaluation and generalization



4. OLS Regression (Statistical Modeling)


Built an initial Ordinary Least Squares (OLS) model


Used p-values to evaluate feature significance


Iteratively removed insignificant variables


Addressed multicollinearity (reduced condition number)


📊 Statistical Validation


Residual analysis performed to validate:


Linearity


Normality of residuals


Homoscedasticity




This step ensured the model was statistically sound and interpretable.

5. Linear Regression (Machine Learning)


Built a sklearn Linear Regression model using selected features


Focused on predictive performance rather than inference


📈 Performance


R² Score ≈ 0.76 → Strong explanatory power


Evaluated using absolute error metrics


Model performs well for most observations, with some larger deviations



🔍 Key Insights


Demand is strongly influenced by:


🌦️ Weather conditions


📅 Seasonality


🗓️ Temporal patterns (weekends vs working days)




Proper feature selection significantly improves model stability


Removing multicollinearity enhances interpretability



📉 Error Analysis


Residuals show:


Mild heteroscedasticity


Slight skewness




👉 Interpretation:


Model captures overall trends well


Some complex/non-linear patterns remain unmodeled


Larger errors occur in edge cases



⚖️ Model Strengths


✅ Interpretable (thanks to OLS)


✅ Good predictive performance (Linear Regression)


✅ Statistically validated


✅ Handles multicollinearity effectively


✅ Real-world aligned insights



⚠️ Limitations


Assumes linear relationships


Does not fully capture:


Non-linear patterns


Feature interactions




Some prediction errors persist for extreme cases



🚀 Future Improvements


Add interaction terms


Apply non-linear transformations


Experiment with advanced models:


Ridge Regression


Lasso Regression


Random Forest / Tree-based models




Incorporate additional features:


Holidays


External/environmental factors





🏁 Conclusion
This project delivers a strong baseline model for predicting bike rental demand. It successfully combines:


Rigorous statistical analysis


Thoughtful feature engineering


Practical machine learning implementation


The result is a model that balances simplicity, interpretability, and performance, making it a solid foundation for further enhancements and real-world deployment.

🛠️ Tech Stack


Python 🐍


Pandas & NumPy


Matplotlib & Seaborn


Statsmodels (OLS)


Scikit-learn


https://www.linkedin.com/in/shorya-bisht-a20144349/




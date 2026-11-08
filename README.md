# 🏠 House Sales Price Prediction – King County, USA

Final project for the **IBM Data Analysis with Python** course on Coursera. The project analyzes King County (Seattle) house sales data to understand what drives house prices, and builds Linear Regression models to predict them.

## 🎯 Objective
Explore housing sales data, identify the key factors associated with house prices, and apply Machine Learning techniques to predict prices.

## 🔄 Workflow
- Data loading and exploration with Pandas
- Data type inspection and statistical analysis
- Data cleaning and handling missing values
- Exploratory Data Analysis (EDA)
- Visualization with Seaborn & Matplotlib
- Correlation analysis
- Linear Regression modeling
- Model evaluation using R²
- Feature scaling and polynomial features (Scikit-learn)
- Building a Machine Learning Pipeline

## 🔍 Key Insights
- `sqft_living` has a strong positive correlation with price (~0.70)
- `grade` is also strongly correlated with price (~0.67)
- `sqft_above` has a positive correlation with price (~0.61)
- Waterfront properties have considerably higher prices than non-waterfront ones
- `sqft_living`, `grade`, `sqft_above`, and `bathrooms` show some of the strongest relationships with price

## 📈 Model Results
| Model | R² |
|-------|-----|
| Longitude only | ~0.0005 |
| sqft_living only | ~0.49 |
| Multiple features | ~0.66 |

Using multiple features improved the model significantly over a single feature.

## 🛠️ Tools & Technologies
Python | Google Colab | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn

## 👩‍💻 Author
**Asmaa Mohamed**  
Aspiring Data Analyst | Python, SQL, Excel  
🔗 [https://www.linkedin.com/in/asmaa-mohamed-41b392324]

# CO2 Emission of Cars Prediction using Linear Regression

## 📌 Objective
To predict CO2 emissions of cars using engine Volume and Weight.

## 📊 Dataset
The dataset contains information about cars including:
- Engine Volume
- Weight
- CO2 Emissions

## ⚙️ Approach

1. Data Preprocessing
   - Selected relevant features: Volume, Weight, CO2
   - Grouped data by Volume to reduce noise and observe average trends

2. Exploratory Data Analysis
   - Scatter plots were used to understand relationships between variables

3. Model Training
   - Linear Regression model was trained using train-test split

4. Model Evaluation
   - Metrics used:
     - Mean Squared Error (MSE)
     - Root Mean Squared Error (RMSE)
     - R² Score

5. Polynomial Regression
   - Polynomial Regression (degree = 2) was tested to capture non-linear relationships

## 📈 Results

| Model                 | R² Score |
|-----------------------|----------|
| Linear Regression     | ~  0.22  |
| Polynomial Regression | ~ -0.97  |

## 🔍 Observations
- Linear Regression shows moderate performance
- Polynomial Regression performs significantly worse
- This indicates overfitting and poor generalization in the polynomial model
  
### 📊 Visualization Improvement
To improve regression visualization, the input feature values were sorted before plotting predictions. This ensures a smooth and meaningful regression line instead of a zig-zag pattern caused by unordered data.

## ⚠️ Limitations
- Dataset is small
- Grouping reduces dataset size further
- Only two features were used (Volume, Weight)

## ✅ Conclusion
Linear Regression is more suitable for this dataset. Increasing model complexity without sufficient data leads to worse performance.

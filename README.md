🏡 Luxury Home Investment Analysis
📌 Project Overview
The goal is to recommend 20 of the most luxurious (i.e., priciest) homes out of 100 candidate properties with unknown sales prices.
The prediction is evaluated based on how many of the predicted homes match the actual top 20 most expensive homes.
The project follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology.
📊 CRISP-DM Implementation
1️⃣ Business Understanding
✔️ Define project objectives and investment strategy.
✔️ Identify the key evaluation metric: number of correct home predictions.

2️⃣ Data Understanding
✔️ Analyze the dataset containing 100 candidate homes.
✔️ Explore available features (size, location, amenities, bedrooms, etc.).
✔️ Identify missing values and data inconsistencies.

3️⃣ Data Preparation
✔️ Handle missing data and outliers.
✔️ Perform feature engineering (creating useful new features).
✔️ Normalize and scale numerical data.
✔️ Encode categorical variables if necessary.

4️⃣ Modeling
✔️ Select machine learning models such as:

Linear Regression
Decision Trees
Random Forest
XGBoost
✔️ Train models on the processed dataset.
✔️ Tune hyperparameters for best performance.
5️⃣ Evaluation
✔️ Evaluate models using Mean Absolute Error (MAE), RMSE, and R² Score.
✔️ Compare predictions against actual property prices.
✔️ Select the best-performing model based on overlap with actual top 20 homes.

6️⃣ Deployment
✔️ Generate the final list of top 20 homes for investment recommendation.
✔️ Optionally deploy results using a dashboard or web application.

🛠 Tech Stack
✔️ Language: Python 🐍
✔️ Libraries & Frameworks:

Data Processing: Pandas, NumPy
Visualization: Matplotlib, Seaborn
Modeling: Scikit-learn, XGBoost
Evaluation: Statsmodels, Scipy

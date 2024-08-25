# 🚀 Applied Data Science Capstone

Final Project for IBM Applied Data Science Capstone Certificate.


## 📄 Project Background
SpaceX, a pioneering company in the commercial space industry, has revolutionized space travel by significantly reducing costs. While traditional rocket launches can cost upwards of 165 million dollars, SpaceX offers Falcon 9 rocket launches for just 62 million dollars. A key factor in this cost-efficiency is the reusability of the rocket's first stage. By successfully landing and reusing this stage, SpaceX can dramatically lower the cost per launch. This project aims to leverage public data and machine learning techniques to predict the likelihood of the first stage landing successfully, thus providing insights into the potential cost of future launches.

## 📄 Questions to be answered
1. How do factors such as payload mass, launch site, number of previous flights, and orbital parameters influence the success rate of the first-stage landing?
2. Has the success rate of first-stage landings improved over the years, indicating a learning curve or technological advancements?
3. What machine learning algorithm provides the most accurate binary classification for predicting the success of the first stage landing?
   
## 📄 Methodology
1. **Data collection:**
* **SpaceX REST API:** Retrieved detailed information on SpaceX launches, including launch site, payload details, and mission outcomes.
* **Web Scraping:** Gathered historical data from Wikipedia and other public sources to supplement the SpaceX API data, particularly for older launches.
2. **Data Wrangling:**
* **Filtering Data:** Selected relevant features and observations necessary for the analysis.
* **Handling Missing Values:** Addressed missing data through imputation and exclusion strategies to ensure a clean dataset.
* **Data Encoding:** Applied One Hot Encoding to categorical variables, making them suitable for binary classification models.
3. **Exploratory Data Analysis (EDA):**
* **Visualization:** Employed various plotting techniques to explore relationships and trends within the data, including bar plots, scatter plots, and histograms.
* **SQL Queries:** Used SQL to perform complex data manipulations and summarizations, aiding in the discovery of patterns in the dataset.
4. **Interactive Visual Analytics:**
* **Folium:** Created interactive maps to visualize the geographical distribution of launches and landing outcomes.
* **Plotly Dash:** Developed interactive dashboards to allow dynamic exploration of the data, facilitating deeper insights into the factors influencing landing success.
5. **Predictive Analysis:**
* **Model Building:** Developed multiple classification models, including logistic regression, decision trees, random forests, and support vector machines (SVM), to predict the success of first-stage landings.
* **Model Tuning:** Used techniques such as grid search and cross-validation to optimize model performance.
* **Model Evaluation:** Assessed models using accuracy, precision, recall, F1-score, and ROC-AUC to identify the best-performing algorithm for binary classification in this context.

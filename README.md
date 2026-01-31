## 👩‍💻 Author  
**Khushi Pandit**

# 📊 E-Commerce Sales Analysis using Bagging Model


## 📌 Project Overview
This project analyzes **E-Commerce sales data** and applies a **Bagging (Bootstrap Aggregation) Machine Learning model** to improve prediction performance and reduce overfitting.  

The notebook integrates:
- Data preprocessing  
- Exploratory Data Analysis (EDA)  
- Data visualization  
- Ensemble learning  

to extract meaningful insights and build a robust predictive model.


## 🎯 Objectives
- Analyze sales trends and patterns  
- Perform data cleaning and preprocessing  
- Apply the Bagging ensemble technique  
- Improve model stability and accuracy  
- Evaluate model performance  


## 🛠️ Technologies Used
- **Python**  
- **Jupyter Notebook**  
- **Pandas & NumPy** – Data handling  
- **Matplotlib & Seaborn** – Data visualization  
- **Scikit-learn** – Machine Learning & Bagging Model  


## 📂 Dataset Description
The dataset consists of **e-commerce transactional data**, including:
- Product details  
- Order information  
- Sales / revenue values  
- Customer-related attributes  

📌 *The dataset is loaded directly inside the notebook.*


## 🔍 Methodology

### 1️⃣ Data Preprocessing
- Handling missing values  
- Removing duplicate records  
- Encoding categorical variables  
- Feature scaling (if required)  

### 2️⃣ Exploratory Data Analysis (EDA)
- Descriptive statistics  
- Sales distribution analysis  
- Category-wise and product-wise analysis  
- Trend visualizations  

### 3️⃣ Model Building – Bagging
- Selection of a base estimator (e.g., Decision Tree)  
- Bootstrap sampling  
- Training multiple models  
- Aggregating predictions using:
  - `BaggingClassifier`  
  - `BaggingRegressor`  

### 4️⃣ Model Evaluation
- Accuracy / RMSE (based on problem type)  
- Performance comparison with base estimator  
- Analysis of improvement using Bagging  


## 🤖 Bagging Model Explanation
**Bagging (Bootstrap Aggregation)** is an ensemble learning technique that:
- Trains multiple models on randomly sampled subsets of data  
- Reduces variance  
- Improves prediction stability  
- Helps prevent overfitting  

📌 Implemented using **Scikit-learn's `BaggingClassifier`**.


## 📈 Results & Insights
- Bagging model outperforms a single estimator  
- Reduced overfitting  
- More stable and reliable predictions  
- Improved overall model performance  


## 🔮 Future Enhancements
- Compare Bagging with Boosting and Random Forest  
- Perform hyperparameter tuning  
- Implement cross-validation  


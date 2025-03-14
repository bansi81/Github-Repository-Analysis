# GitHub Repository Analysis
A data-driven approach to analyzing and predicting GitHub repository success using machine learning. 

## Project Overview
This project involves an in-depth analysis of GitHub repositories, including data cleaning, exploratory data analysis (EDA), and machine learning modeling to classify repositories as popular or unpopular based on various metrics.  

Key objectives:  
- Perform data cleaning and preprocessing to ensure data quality.  
- Conduct exploratory data analysis (EDA) to identify trends in repository success.  
- Implement a machine learning model (Random Forest) for classification.  
- Evaluate model performance using accuracy, precision, recall, and F1-score.  

---

## Exploratory Data Analysis (EDA)  
EDA was performed to identify key factors influencing repository success, including:  
- Distribution of repository stars, forks, and issues
- Relationship between programming languages and repository popularity  
- Correlation analysis of repository features  

Example Visualizations: 
![image](https://github.com/user-attachments/assets/5b6aab80-2b60-4a48-86a1-a480f9e75465)
![image](https://github.com/user-attachments/assets/1409bb7e-67c9-4dbb-9760-10a28da08af5)



---

## Data Preprocessing 
Before training the machine learning model, the dataset was cleaned and transformed by:  
- Handling missing values  
- Encoding categorical variables 
- Scaling numerical features
- Removing outliers to improve model performance  

---

## Machine Learning Model  
The Random Forest classifier was used for predicting whether a GitHub repository is popular or unpopular based on extracted features.  

| Model           | Accuracy | Precision | Recall | F1-score |
|---------------|----------|------------|---------|------------|
| Random Forest | 88%      | 88%        | 88%     | 88%        |


---

## How to Run the Project 
### 1. Clone the Repository  
```sh
git clone https://github.com/bansi81/Github-Repository-Analysis.git
cd Github-Repository-Analysis
```

### 2. Install Dependencies
```sh
pip install -r requirements.txt
```

### 3. Run the Jupyter Notebook for Analysis and Model Training 
```sh
jupyter notebook
```

---

## Results and Insights 
- Identified key factors influencing GitHub repository popularity.  
- Analyzed which programming languages are most commonly associated with high-star repositories.  
- Used a **Random Forest model** to predict **repository success** based on available features.  
- Determined **feature importance** to understand which factors contribute most to popularity.  


---

## Future Enhancements 
- Compare **other classification models** such as Logistic Regression, XGBoost, or Neural Networks.  
- Integrate **time series analysis** to track repository growth over time.  
- Deploy the model as a **web application** for real-time predictions.  

---

## Conclusion 
This project provides valuable insights into what makes a GitHub repository successful and demonstrates the use of Random Forest for classification tasks.  


## Author and Contact 
**Bansi Shah**  
Email: bansishah009@gmail.com 
GitHub: bansi81
  



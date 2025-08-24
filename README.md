Customer Churn Prediction – BCG Simulation

 Project Overview
This project was developed as part of a BCG Data Science simulation.  
The goal is to predict **customer churn** based on historical client and pricing data, and provide insights into the key factors influencing churn.

 Key Steps
1.Exploratory Data Analysis (EDA)  
   - Investigated distributions, outliers, and correlations.  
   - Visualized consumption, subscribed power, and churn distribution.  

2.Feature Engineering  
   - Created new features (e.g., price sensitivity, consumption ratios, net/gross margin ratios).  
   - Converted dates, categorical variables, and handled skewed distributions.  

3.Modeling  
   - Trained a Random Forest Classifier using Scikit-learn.  
   - Evaluated using Accuracy, Precision, Recall.  

4. Results & Insights  
   - Identified net margin and 12-month consumption as top drivers of churn.  
   - Price sensitivity was less influential compared to financial and consumption features.  

 Example Output
- Confusion Matrix & Metrics  
- Feature Importance Chart  
- Predictions exported with churn probabilities.  

 Tech Stack
- Python, Pandas, Numpy  
- Matplotlib, Seaborn  
- Scikit-learn  

 How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/


# 💳 Loan Repayment Likelihood Prediction Project  

## 📌 Project Overview  
Developed a predictive model in Python to assess the likelihood of loan repayment using a real-world bank dataset.  
The project involved data cleaning (removing irrelevant columns, converting categorical variables into numerical formats), descriptive and exploratory data analysis (EDA) to understand borrower characteristics, and the application of multiple machine learning models to predict loan default risk.  

Models such as Logistic Regression, Decision Tree, Support Vector Machine (SVM), Random Forest, and Naïve Bayes were tested and evaluated using scikit-learn.  
Visualizations were created using matplotlib and seaborn to better understand patterns in borrower data.  

The **Decision Tree** model, trained on a 70%/30% train-test split, was chosen as the final model for its interpretability and balance of performance.  
✅ Achieved **81% accuracy**  
✅ Improved **recall from 0% → 65%**  
This enabled financial institutions to identify more true defaulters and reduce potential credit risk exposure.  

---

## 📂 Key Files  
- 📓 **Jupyter Notebook**: [Finance Loans Project.ipynb](https://github.com/Nirvan-Jothi-001/Data-Analytics-Projects/blob/main/Finance-Loan-Default/Finance%20Loans%20Project.ipynb)  
- 📑 **Project Report (PDF)**: [Finance Loans.pdf](https://github.com/Nirvan-Jothi-001/Data-Analytics-Projects/blob/main/Finance-Loan-Default/Finance%20Loans.pdf)  
- 🎤 **Presentation Slides (PPTX)**: [Finance Loan Project Slides.pptx](https://github.com/Nirvan-Jothi-001/Data-Analytics-Projects/blob/main/Finance-Loan-Default/Finance%20Loan%20Project%20Slides.pptx)  

---

## 🛠 Tools and Libraries  
- **Python**  
- **scikit-learn** (machine learning)  
- **NumPy** (numerical computations)  
- **pandas** (data manipulation)  
- **matplotlib** & **seaborn** (data visualization)  

---

## 🔎 Steps Taken  
1. **Data Cleaning & Preparation**: Removed irrelevant columns, handled missing values, and converted categorical variables into numerical formats.  
2. **Exploratory Data Analysis (EDA)**: Analyzed borrower characteristics (age, income, loan amount, repayment status) to identify patterns and relationships.  
3. **Model Training, Testing & Predicting**: Built predictive models using Logistic Regression, SVM, Decision Tree, Random Forest, and Naïve Bayes on multiple train-test splits (70/30, 75/25, 80/20).  
4. **Model Evaluation**: Evaluated models using **accuracy, precision, recall, and confusion matrices**, with special focus on recall to capture more true defaulters.  

---

## 📊 Results  
- All models achieved around **81% accuracy** due to the balanced nature of the dataset.  
- **Decision Tree** was selected as the final model for its interpretability and suitability for this dataset.  
- **Recall improved from 0% to 65%**, significantly reducing false negatives (missed defaulters).  
- These improvements help banks:  
  - Better identify risky borrowers.  
  - Reduce potential **credit risk exposure**.  
  - Make safer, data-driven lending decisions.  

---

## 🏁 Conclusion  
This project demonstrates the use of machine learning in financial risk management.  
By focusing on recall and accuracy together, the model improves the ability of financial institutions to **catch potential defaulters early**, reducing financial losses and strengthening loan approval processes.  

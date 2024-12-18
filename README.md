# SOFTWARE COMPONENT DESIGN

## Group Members
- **Elbethel Shineda** (ETS0406/13)  
- **Leul Mintesinot** (ETS0766/13)  
- **Mihret Agegnehu** (ETS0874/13)  
- **Mikiyas Bedasa** (ETS0888/13)  
- **Natanim Ashenafi** (ETS0979/13)  

### Submitted to:  
**Mr. Gizate Desalgn**  

### Submission Date:  
**December 18, 2024**

---

## **1. Prototyping Model**

The **Prototyping Model** is a software development methodology that prioritizes creating an initial version of a system (prototype) to refine requirements before building the final product.

### **Steps in the Prototyping Model**
1. **Requirements Gathering and Analysis:** Collaborate to identify essential features.
2. **Quick Design:** Create a preliminary design focused on key system aspects.
3. **Prototype Development:** Build a simplified version demonstrating core functionalities.
4. **User Evaluation:** Gather feedback from stakeholders to refine the prototype.
5. **Refinement:** Iterate on the prototype until it meets expectations.
6. **Engineering Product Development:** Develop the final system incorporating validated requirements.

### **Types of Prototypes**
- **Throwaway Prototypes:** Used for quick feedback, discarded later.
- **Evolutionary Prototypes:** Iteratively refined to evolve into the final product.
- **Incremental Prototypes:** Individual components developed and integrated later.
- **Extreme Prototypes:** Focus on user interface first, followed by backend integration.

### **Advantages**
- Enhanced user involvement.
- Early detection of issues.
- Accurate requirements definition.
- Flexibility in design iterations.

### **Disadvantages**
- Risk of scope creep.
- Potential for inadequate documentation.
- Misunderstandings about the prototype’s purpose.

### **Applications**
- Clarifying unclear requirements.
- Designing user-interactive systems.
- Experimenting with innovative technologies.

---

## **2. Python ML Code**

### **Project Title:**  
**Machine Learning Predicting Customer Churn**

### **Introduction**
This project aims to develop a machine learning model to predict customer churn, enabling businesses to proactively engage at-risk customers. Customer churn refers to customers discontinuing their relationship with a company, posing a challenge to revenue and growth.

### **Objectives**
- Collect and preprocess customer churn datasets.
- Perform exploratory data analysis (EDA).
- Build, compare, and evaluate machine learning models.
- Select the best-performing model based on metrics.

### **Dataset Description**
- **Source:** Telco Customer Churn dataset (Kaggle).  
- **Structure:** 7043 rows, 21 columns.  
- **Key Features:** Gender, SeniorCitizen, tenure, PhoneService, TotalCharges, and Churn.  
- **Churn Rate:** 26.5% of customers churned.  

### **Machine Learning Workflow**
1. **Data Preprocessing:** Handle missing values, encode categorical variables, and normalize data.
2. **EDA:** Use visualizations (e.g., histograms, bar plots, heatmaps) to explore feature relationships.
3. **Model Building:** Train models like Logistic Regression, Random Forest, and Gradient Boosting.
4. **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score.

### **Tools and Libraries**
- **Data Manipulation:** `pandas`, `numpy`  
- **Visualization:** `matplotlib`, `seaborn`  
- **Modeling:** `scikit-learn`

### **Best Model**
- **Algorithm:** K-Neighbors Classifier (KNN).  
- **Performance:** Achieved 98.2% accuracy.  

### **Running the Code**
1. Clone the repository:
   ```bash
   git clone https://github.com/mihretgold/churn_prediction_group2.git
   ```
2. Navigate to the project directory:
   ```bash
   cd churn-prediction
   ```
3. Run the script for preprocessing and training:
   ```bash
   python churn_prediction.ipynb
   ```
---

### **Conclusion**

This project demonstrates the utility of machine learning in predicting customer churn. By identifying key factors influencing churn, actionable strategies can be developed for customer retention. The **K-Neighbors Classifier (KNN)** model stood out as the top performer with a robust accuracy of **98.2%**.

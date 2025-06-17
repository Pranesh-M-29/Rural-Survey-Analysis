**🌾 Rural Survey Analysis**

This project applies machine learning and interactive visualization techniques to analyze rural community survey data, identify basic needs, and recommend suitable livelihood strategies. It empowers social development teams and government agencies to make data-driven decisions that can improve the lives of underserved populations.

**📌 Project Overview**

Rural Survey Analysis is a real-world, data-driven solution that processes and interprets rural household survey data. It performs two core tasks:

**1. Basic Needs Classification**

 Classifies households into three categories:
 
 • High Need
 
 • Moderate Need
 
 • Low Need
 
 Based on key indicators such as food availability, shelter status, electricity access, healthcare, and clothing.

**2. Livelihood Type Prediction**

 Recommends optimal livelihood options based on parameters like:
 
 • Number of family members
 
 • Number of working individuals
 
 • Education levels
 
 • Income and skill profiles



**🧠 Machine Learning Techniques**

**📌 Algorithms:**

 • Random Forest
 • XGBoost
 • SMOTE (for class imbalance handling)

**📊 Classification:**

   • Multi-label classification for livelihood recommendation
   • Multi-class classification for need-level prediction

**📂 Dataset:**
 Real-time collected rural household survey data (\~113 samples in initial version – expandable for scalability)

 
**📊 Visualization with Power BI**

An interactive Power BI dashboard has been created to:

- Display classified need levels across regions
- Show livelihood suggestions and predicted distributions
- Highlight patterns, outliers, and correlation insights
- Enable filtering by demographic and socioeconomic criteria

Screenshots of the dashboard can be found in the /screenshots/ directory.


**🛠 Technical Stack**

| Component     | Technology Used                         |
| ------------- | --------------------------------------- |
| Programming   | Python                                  |
| ML Libraries  | Scikit-learn, XGBoost, Imbalanced-learn |
| Visualization | Power BI                                |
| IDE/Tools     | Jupyter Notebook, VS Code               |


**🚀 Use Cases**

* Planning government aid distribution
* Prioritizing healthcare and food interventions
* Suggesting sustainable income programs
* Monitoring progress over time

# Titanic Survivors Analysis

### Project Goal
This project is a comprehensive analysis of the Titanic disaster dataset. The goal was to explore the factors that influenced a passenger's chance of survival, and to build a predictive model to forecast survival outcomes.

---

### Key Findings from Data Exploration
Using a combination of data cleaning, exploratory data analysis (EDA), and powerful visualizations, the analysis revealed several critical insights:

* **Gender:** There was a significant difference in survival rates based on gender. A remarkable **74% of females survived**, compared to only **19% of males**.
![Survival Rate by Gender](https://github.com/dpriestley09/Titanic_Survivor_Analysis/blob/main/titanic%20gender.png)
* **Passenger Class:** Socioeconomic status played a major role. Passengers in **first class had a 63% survival rate**, while those in **third class had a survival rate of just 24%**.
![Survival Rate by Passenger Class](https://github.com/dpriestley09/Titanic_Survivor_Analysis/blob/main/titanic%20class.png)
* **Age:** The age of a passenger also impacted their chance of survival. The data shows that a higher proportion of **children (under 10 years old)** survived the disaster, while the survival rates for young and middle-aged adults were notably lower.
![Age Distribution by Survival Status](https://github.com/dpriestley09/Titanic_Survivor_Analysis/blob/main/titanic%20age.png)
* **Alone vs. With Family:** Passengers traveling with a family had a higher survival rate (**51%**) than those who were traveling alone (**30%**).

---

### Predictive Modeling
To demonstrate the ability to use data for predictive purposes, a **Logistic Regression** model was built to predict survival outcomes.

* **Methodology:** The model was trained on cleaned and preprocessed data, including a new feature for `FamilySize`.
* **Performance:** The model achieved an impressive **82% accuracy** in predicting survival on a test set of unseen data.

---

### Conclusion
This project demonstrates a full-scale data analysis workflow, from raw data to actionable insights and a predictive model. The findings challenge the simple historical narrative by highlighting how factors like gender, class, and family size created a hierarchy of survival on the Titanic.

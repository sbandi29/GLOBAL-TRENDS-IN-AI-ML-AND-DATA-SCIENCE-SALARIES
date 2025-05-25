# 📊 Global Trends in AI, ML, and Data Science Salaries

Hi, I’m Sriraj Bandi 👋 and this repository contains the final group project for STAT-515, completed alongside my teammates Shashidharreddy Maligireddy and Abhinay Rao. We explored global salary trends across Artificial Intelligence, Machine Learning, and Data Science roles using a real-world dataset.

Our goal was to understand how salaries vary across job roles, experience levels, company sizes, and remote work settings—and to build machine learning models that can predict salary or company size based on key attributes.

---

## 📦 Dataset Summary

We used an open-source dataset which included:
- Job titles & experience levels
- Remote work ratios
- Company size & location
- Employee residence
- Salaries in various currencies, converted to USD

---

## 🔍 Research Questions

1. How does salary distribution vary by experience level and job title?
2. Is there a salary difference based on remote work ratio, and does it vary by country or company size?
3. Do certain job titles consistently receive higher salaries across companies and regions?
4. Can we predict salary using job title and experience level?
5. Can we classify company size using salary and experience?

---

## 🧠 Methods & Models Used

- **Univariate Regression** – to study how salary varies with remote work and company size
- **Multivariate Regression** – to explore the combined impact of experience, location, and company size
- **Machine Learning Models**:
  - Logistic Regression
  - Random Forest Classifier
  - Lasso Regression (for salary prediction)

---

## 📊 Key Visualizations

- Salary distribution histograms
- Salary vs. experience scatter plots
- Company size vs. salary bar plots
- Remote work ratio vs. salary comparisons
- Multivariate salary plots (experience level × company size × location)

---

## 🏆 Results Summary

- **Random Forest** performed best with ~90.32% accuracy for company size classification.
- **Logistic Regression** gave ~89.63% accuracy—close, but slightly behind.
- **Lasso Regression** had an R² of 0.27, indicating moderate predictive power for salary estimation.

---

## 📁 Files Included

├── stat515_grp_11.pdf # Final report with analysis and results
├── STAT515_grp_11.pptx # PowerPoint presentation for the project
├── README.md # This file




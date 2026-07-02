 ## IBM HR Analytics - Employee Attrition Analysis

 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the IBM HR Analytics Employee Attrition dataset to identify the major factors influencing employee turnover. The analysis focuses on understanding workforce demographics, departmental trends, overtime impact, and other attributes associated with employee attrition.

The objective is to derive meaningful business insights that can help organizations make data-driven HR decisions and improve employee retention.

---

 ## Dataset Information

- **Dataset:** IBM HR Analytics Employee Attrition
- **Total Employees:** 1,470
- **Employees Left:** 237
- **Overall Attrition Rate:** **16.12%**

The dataset contains employee-related information such as:

- Age
- Gender
- Department
- Job Role
- Monthly Income
- Education
- Business Travel
- Overtime
- Years at Company
- Job Satisfaction
- Performance Rating
- Work-Life Balance
- Attrition Status

---

##  Project Objectives

- Understand employee attrition trends.
- Identify factors contributing to employee turnover.
- Perform exploratory data analysis using visualizations.
- Discover relationships between employee attributes.
- Prepare the dataset for future machine learning models.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

##  Data Preprocessing

The following preprocessing steps were performed:

- Loaded the IBM HR Analytics dataset
- Renamed inconsistent column names
- Checked for missing values
- Removed unnecessary columns
- Generated descriptive statistics
- Prepared data for visualization

---

##  Exploratory Data Analysis

The project includes analysis of:

### Employee Distribution

- Department distribution
- Business Travel distribution
- Education Field distribution
- Gender distribution
- Age distribution

### Attrition Analysis

- Attrition by Department
- Attrition by Job Role
- Attrition by Gender
- Attrition by Overtime

### Correlation Analysis

- Correlation Heatmap
- Pairplot for numerical features

### Data Visualization

- Count plots
- Bar charts
- Heatmaps
- Pairplots
- Subplots

---

## Key Insights

- Employees working overtime have significantly higher attrition.
- Attrition varies across departments and job roles.
- Age distribution provides insights into workforce demographics.
- Gender-wise attrition differences were analyzed.
- Correlation analysis highlights relationships among numerical features.

---

##  Results

The exploratory analysis indicates that the following factors have a strong relationship with employee attrition:

- Overtime
- Department
- Job Role
- Age
- Monthly Income
- Years at Company

These insights can help HR departments identify at-risk employees and improve employee retention strategies.

---

##  Future Enhancements

Future work may include:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier
- Feature Importance Analysis
- Hyperparameter Tuning
- Model Evaluation
- Employee Attrition Prediction Dashboard

---

##  Project Structure

```
IBM-HR-Attrition-Analysis/
│
├── IBM_Attrition_.csv
├── IBM.ipynb
├── IBM_Attrition_Report_Analysis.docx
├── README.md
└── images/
    ├── correlation_heatmap.png
    ├── attrition_department.png
    ├── overtime_analysis.png
    └── pairplot.png
```

---

## Sample Visualizations

- Department Distribution
- Gender Count Plot
- Age Distribution
- Correlation Heatmap
- Pairplot
- Attrition by Department
- Attrition by Job Role
- Attrition by Overtime

*(Add screenshots from your notebook inside the `images` folder.)*

---

##  Business Value

This analysis helps organizations:

- Reduce employee turnover
- Improve workforce planning
- Enhance employee satisfaction
- Support HR decision-making using data
- Build predictive HR analytics solutions

---

##  How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/IBM-HR-Attrition-Analysis.git
```

2. Navigate to the project folder

```bash
cd IBM-HR-Attrition-Analysis
```

3. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

5. Open `IBM.ipynb` and run all cells.

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Statistical Analysis
- Python Programming
- Business Insights
- HR Analytics

---

 ## Author

- GitHub: https://github.com/yourusername
- LinkedIn: https://linkedin.com/in/yourprofile

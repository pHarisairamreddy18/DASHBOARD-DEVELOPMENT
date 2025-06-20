# DASHBOARD-DEVELOPMENT

*COMPANY* :CODTECH IT SOLUTIONS

*NAME* :PULLA HARI SAIRAM REDDY

*INTERN ID* :CT06DF1059

*DOMAIN* :DATA ANALYTICS

*DURATION* :6 WEEKS

*MENTOR* :NEELA SANTHOSH KUMAR

**Interactive Heart Disease Analysis Dashboard**

**Project Overview**

This project presents an interactive dashboard for analyzing heart disease data using **Power BI**. The dashboard enables users to explore key patterns and relationships between clinical attributes and heart disease diagnoses. Power BI was selected as the preferred tool for its intuitive visual interface, powerful data modeling capabilities, and ease of sharing and publishing dashboards.

**Dataset Information**

The dataset used is the **Heart Disease UCI dataset**, which is widely used in healthcare analytics research and machine learning tasks.

- **Source**: [Kaggle – Heart Disease UCI Dataset](https://www.kaggle.com/datasets/ronitf/heart-disease-uci)
- **Records**: 1,025 patient entries
- **File Format**: CSV (extracted manually from ZIP)
- **Key Features**:
  - 'age'
  - 'sex'
  - 'cholestoral'
  - 'Max_heart_rate'
  - 'resting_blood_pressure'
  - 'thalassemia'
  - 'exercise_induced_angina'
  - 'target' (1 = heart disease present, 0 = not present)
    
## Dashboard Features

The dashboard is composed of several visual components, filters, and KPIs that together provide a comprehensive view of the heart disease risk distribution.

 **Visualizations Included:**

**KPI Cards** :Show average age, average cholesterol, and total patient count. 
**Bar Chart** : Displays the distribution of `target` values grouped by `sex`. 
**Pie Chart** : Shows the percentage split between patients with and without heart disease. 
**Clustered Column Chart** : Compares average age and average cholesterol across the dataset. 
**Scatter Plot** : Visualizes relationships between `age` and `Max_heart_rate`, categorized by `sex` and `thalassemia`. 
**Slicers** : Filters available for `sex`, `thalassemia`, and `exercise_induced_angina`. 

**Actionable Insights**

The following key insights were derived from the dashboard:

1. **Prevalence of Heart Disease**  
   - Out of 1,025 patients, about 48.7% are diagnosed with heart disease.  
   - This split shows a nearly even balance between diseased and non-diseased individuals.

2. **Gender Analysis**  
   - A significantly higher number of males are affected by heart disease than females.  
   - This suggests a potential gender disparity in heart disease risk.

3. **Age Trends**  
   - The average age of patients is approximately 54.4 years.  
   - Middle-aged individuals show a higher risk based on the target variable analysis.

4. **Cholesterol Observation**  
   - The average cholesterol level among patients is around 246 mg/dL.  
   - High cholesterol correlates with higher risk of heart disease.

5. **Heart Rate vs Age**  
   - Max heart rate tends to decrease with increasing age.  
   - This correlation may suggest reduced cardiovascular performance as people age.

**Tools Used**

**Power BI Desktop**  
  Used to build the dashboard, transform data, and generate interactive visuals.

**Microsoft Excel / CSV**  
  Used to clean and view the dataset before importing into Power BI.

 **Export & Sharing**

- The dashboard can be exported as a PDF using `File → Export → Export to PDF`.
- For online access (Power BI Pro), use `Publish → Publish to Web`.

 **How to Use the Dashboard**

1. **Open the '.pbix' file** in Power BI Desktop.
2. Interact with the **slicers** on the left to filter data by gender, thalassemia, or angina.
3. Hover over the charts and scatter plots to view detailed tooltips.
4. Review KPIs and visuals for high-level trends and outliers.

 **Future Improvements**

- Add predictive modeling using Power BI’s DAX or integrate with Python/R visuals.
- Incorporate more clinical variables like blood sugar levels or ECG signals.
- Connect to a live database for real-time monitoring.

**Conclusion**

This Power BI dashboard successfully fulfills the task requirement by delivering a fully functional, interactive dashboard capable of generating meaningful and actionable insights about heart disease patterns. It provides a user-friendly experience with dynamic filtering, insightful KPIs, and effective visualization strategies. Healthcare professionals or analysts can use this dashboard as a foundation for deeper investigation or integration into broader health systems.


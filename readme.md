# HR Analytics Dashboard 📊

Welcome to the **HR Analytics Dashboard** repository! This end-to-end project showcases an interactive Power BI dashboard that visualizes and analyzes HR metrics, empowering organizations to uncover workforce insights and drive data-driven decisions.

---

## 🔍 Project Overview

The HR Analytics Dashboard delivers rich, interactive visualizations of critical human resource data, including:

- **Employee Count & Attrition**: Displays total headcount (446), attrition count (92), and attrition rate (20.6%).
- **Demographics**: Illustrates age distribution, average age (37), and gender breakdown (47 males vs. 35 females who left).
- **Compensation Analysis**: Breaks down salary bands and average salary (7.0K).
- **Tenure Insights**: Tracks years-at-company trends and attrition by tenure with a line chart.
- **Education & Role Breakdown**: Shows attrition by education field (Marketing 38%, Life Sciences 32%, etc.) and by job role performance (Sales Executive 57, Sales Rep 33, Manager 2).

---

## ✨ Key Features

1. **High-Level KPI Cards**: Animated cards highlight core metrics—Employee Count, Attrition Count/Rate, Average Age/Salary/Years.
2. **Department Filter**: Slicer to toggle views between Human Resources, Research & Development, and Sales departments.
3. **Interactive Visuals**:
   - **Donut Chart**: Attrition by Education Field with percentage labels.
   - **Vertical & Horizontal Bar Charts**: Attrition by Age Group and Salary Bands.
   - **Line Chart**: Attrition trend across Years at Company with labeled data points.
   - **Matrix Table**: Attrition counts by JobRole and service year.
4. **Data Drill-Down & Export**: Click on any segment to drill into detailed records; export filtered data to CSV or Excel.
5. **Modern UI Theme**: Dark gradient background with custom color palette for readability.
6. **Custom DAX Measures**: Utilizes advanced DAX formulas for dynamic calculations (e.g., `Attrition Rate = DIVIDE([Attrition Count], [Total Employees])`).

---

## 🛠 Technologies & Tools

- **Power BI Desktop** (Feb 2025 release)
- **DAX (Data Analysis Expressions)** for measures and KPIs
- **Power Query (M Language)** for ETL and data shaping
- **Microsoft Excel** for initial data cleaning and validation

---

## 📂 Repository Structure

```
├── HR_Analytics.pbix            # Power BI report file
├── assets/
│   └── dashboard_preview.png    # Dashboard screenshot
├── data/
│   └── hr_data.csv              # Sample HR dataset (~10,000 records)
├── docs/
│   ├── data_dictionary.md       # Field definitions and source mappings
│   └── UX_notes.md              # UI design decisions and color palette
├── LICENSE
└── README.md                    # Project overview and setup guide
```

---

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/<your-username>/hr-analytics-dashboard.git
   cd hr-analytics-dashboard
   ```
2. **Open the Power BI file**:
   - Launch **Power BI Desktop**.
   - Open `HR_Analytics.pbix`.
3. **Review Data & DAX Measures**:
   - In **Power Query Editor**, examine applied steps for data cleansing.
   - In **Model** view, inspect custom DAX measures under the `Measures` table.
4. **Interact & Customize**:
   - Use the department slicer to switch between HR, R&D, and Sales views.
   - Hover for detailed tooltips or click to filter.
   - Modify visual properties or add new measures as needed.
5. **Export Reports**:
   - Export current page visuals to PDF or PowerPoint via **File > Export**.

---

## 📈 Sample Data Schema

| Column         | Type    | Description                                    |
| -------------- | ------- | ---------------------------------------------- |
| EmployeeID     | Integer | Unique employee identifier                     |
| Age            | Integer | Employee age                                   |
| Gender         | Text    | Male / Female                                  |
| EducationField | Text    | Highest qualification (e.g., Technical Degree) |
| Department     | Text    | Department name (HR, R&D, Sales)               |
| JobRole        | Text    | Role title (e.g., Sales Executive)             |
| MonthlyIncome  | Decimal | Monthly salary (USD)                           |
| Attrition      | Text    | "Yes" or "No" flag                             |
| YearsAtCompany | Decimal | Tenure in years                                |

For a detailed breakdown of transformations and source files, see [docs/data\_dictionary.md](docs/data_dictionary.md).

---

## 🎯 Business Impact

- **Retention Strategy**: Identify high-risk groups (e.g., 26–35 age group with 41 attritions) to implement targeted engagement programs.
- **Cost Optimization**: Analyze salary band attrition to adjust compensation strategies.
- **Recruitment Planning**: Use demographic trends to forecast hiring needs.

---

## 🤝 Contributing

Your contributions are welcome! Please follow these steps:

1. Fork the repo.
2. Create a feature branch: `git checkout -b feature/my-update`.
3. Commit your changes: `git commit -m "Add new visualization"`.
4. Push to branch: `git push origin feature/my-update`.
5. Submit a Pull Request describing your enhancements.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

laxman khedkar 
"# HR_Analytics_Dashboard" 

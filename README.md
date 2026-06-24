# 🎓 Student Performance Analysis Dashboard

A comprehensive and interactive **Power BI dashboard** designed to analyze student academic performance, identify key success factors, and uncover insights related to study habits, attendance, demographics, and educational background.

---

## ✨ Features

* 📊 Interactive academic performance dashboard
* 🎯 KPI tracking for student success metrics
* 📚 Subject-wise performance analysis
* 🏆 Top and lowest-performing student identification
* 📈 Study hours vs performance analysis
* 📝 Attendance impact analysis
* 👨‍👩‍👧 Parent education impact assessment
* 🌐 Internet access performance comparison
* 🎭 Extracurricular activity performance insights
* 📖 Study method effectiveness analysis
* 🔍 Interactive filtering with slicers
* 📱 Clean and recruiter-friendly dashboard design

---

## 🛠️ Tools & Technologies

### Data Analysis & Visualization

* Power BI
* Power Query
* DAX (Data Analysis Expressions)

### Data Preparation

* Data Cleaning
* Data Transformation
* Data Modeling
* Data Validation

---

## 📂 Project Structure

```text
Student-Performance-Analysis/
│
├── Student_Performance_Analysis.pbix
├── README.md
│
├── dashboard_screenshots/
│   ├── Main_Overview.png
│   └── Performance_Drivers.png
│
├── dataset/
│   ├── Student_Performance.csv
│   └── student_performance_cleaned.csv
│
└── docs/
    └── project_notes.txt
```

---

## 📊 Dataset Overview

The dataset contains student-level academic and demographic information, including:

* Student ID
* Age
* Gender
* School Type
* Parent Education
* Study Hours
* Attendance Percentage
* Internet Access
* Extra Activities
* Study Method
* Math Score
* Science Score
* English Score
* Overall Score
* Final Grade

---

## 🧹 Data Cleaning & Preparation

The following data preparation steps were performed:

* Verified data types and column consistency
* Checked for missing and null values
* Validated categorical values
* Identified and removed **10,000 duplicate records**
* Reduced dataset size from **25,000 to 15,000 unique students**
* Created a subject-level analysis table using Power Query unpivoting
* Established relationships between student and subject tables
* Built optimized measures using DAX

---

## 📌 Key Performance Indicators (KPIs)

The dashboard tracks the following metrics:

* 👨‍🎓 Total Students
* 📈 Average Overall Score
* ✅ Pass Percentage
* 📝 Average Attendance
* ⏰ Average Study Hours
* 🏆 Top Performing Subject
* 📉 Lowest Performing Subject

---

## 📄 Dashboard Pages

### 📊 Page 1 — Student Performance Overview

Provides a high-level summary of academic performance.

**Visuals Included**

* KPI Cards
* Average Score by Subject
* Grade Distribution
* Average Overall Score by Gender
* Average Overall Score by School Type

---

### 📈 Page 2 — Performance Drivers & Student Insights

Explores factors that influence academic performance.

**Visuals Included**

* Study Hours vs Overall Score
* Attendance vs Overall Score
* Average Overall Score by Parent Education
* Average Overall Score by Internet Access
* Average Overall Score by Extra Activities
* Average Overall Score by Study Method
* Top Students Table
* Lowest Students Table

---

## 🔍 Key Insights

* Average overall student score is **64.02**
* Pass percentage is **88.03%**
* **Math** is the highest-performing subject
* **English** is the lowest-performing subject
* Higher study hours are associated with better academic performance
* Students with higher attendance generally achieve stronger results
* Students with internet access perform slightly better on average
* Parent education shows a moderate influence on student performance
* Online video learning and coaching methods show slightly higher average scores
* Top-performing students consistently demonstrate high attendance and study hours

---

## 🚀 How to Use

### 1. Download the project

Clone or download the repository.

```bash
git clone https://github.com/your-username/student-performance-analysis.git
```

### 2. Open the dashboard

Open:

```text
Student_Performance_Analysis.pbix
```

using **Power BI Desktop**.

### 3. Explore the dashboard

* Navigate between dashboard pages
* Use slicers to filter data
* Analyze student performance metrics
* Explore relationships between performance drivers and outcomes

---

## 📸 Dashboard Screenshots

### Page 1 — Student Performance Overview

* KPI Summary
* Subject Performance Analysis
* Grade Distribution
* Gender Comparison
* School Type Comparison
  
<img width="1111" height="625" alt="Main_Overview" src="https://github.com/user-attachments/assets/68219fd9-b879-4878-90ba-2f1bd01b60d7" />

### Page 2 — Performance Drivers & Insights

* Study Hours Analysis
* Attendance Analysis
* Parent Education Impact
* Internet Access Comparison
* Study Method Analysis
* Top & Lowest Students
<img width="1116" height="621" alt="Performance_Drivers" src="https://github.com/user-attachments/assets/2bf80464-259d-4193-8bdf-b2615c0c125d" />

---

## 🔮 Future Improvements

* 📅 Academic trend analysis over time
* 🎯 Predictive performance modeling
* 🤖 Machine learning integration
* 📚 Subject-specific intervention recommendations
* 📈 Advanced student segmentation
* 📊 Performance forecasting
* 🌍 School-level benchmarking

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 👨‍💻 Author

Developed with ❤️ by **Anwar Ansari**.

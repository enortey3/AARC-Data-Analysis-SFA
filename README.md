# 📊 AARC Student Attendance & Academic Performance Analysis

## **Project Overview**

This project analyzes student attendance records from the Academic Assistance and Resource Center (AARC) at Stephen F. Austin State University to understand how academic support engagement relates to student academic performance.

The analysis explores:

- Student attendance behavior
- Most utilized academic support centers
- Course-specific attendance trends
- Visit duration patterns
- Relationships between AARC attendance and grades
- Biology-specific attendance patterns
- Peak attendance periods during the semester

---

## **Research Objective**

The primary objective of this study was to investigate whether student engagement with AARC services is associated with academic performance.

Key questions addressed include:

- Which AARC centers experience the highest demand?
- Which courses receive the most academic support visits?
- Do students with higher attendance tend to perform better academically?
- How does attendance vary across academic periods?

---

## **Dataset Summary**

| Variable | Value |
|---|---|
| Total Visit Records | 91,900 |
| Unique Students | 8,891 |
| Academic Terms | 7 |
| Courses | 1,652 |
| AARC Centers | 5 |

### **Grade Encoding**

Grades were transformed into numeric values for correlation analysis.

| Letter Grade | Numeric Value |
|---|---|
| A | 4 |
| B | 3 |
| C | 2 |
| D | 1 |
| F/W | 0 |

---

## **Tools & Technologies**

| Tool | Purpose |
|---|---|
| Python | Data analysis |
| Pandas | Data manipulation |
| NumPy | Numerical computation |
| Matplotlib | Data visualization |
| Jupyter Notebook | Interactive analysis |

---

## **Analytical Workflow**

### **1. Data Preparation**
- Cleaning attendance records
- Encoding grades numerically
- Aggregating student-level attendance metrics

### **2. Exploratory Data Analysis**
- Attendance distribution
- Center-level usage patterns
- Most visited courses
- Visit duration analysis

### **3. Correlation Analysis**
Relationships examined:
- Total visits vs grade
- Total duration vs grade
- Total visits vs total duration
- Biology attendance vs Biology grades

### **4. Temporal Analysis**
- Monthly attendance trends
- Peak attendance periods
- Semester usage behavior

---

# 📈 Key Findings

## **Most Utilized AARC Centers**

| Center | Total Visits |
|---|---|
| Science | 41,661 |
| Math & Business | 25,143 |
| Liberal Arts | 13,034 |
| Writing | 11,863 |
| Workshops | 199 |

### **Observation**
Science and Math-related support centers experienced the highest demand, indicating strong student reliance on STEM academic support services.

---

## **Attendance & Academic Performance**

Students with higher grades generally demonstrated greater AARC engagement.

| Grade Level | Average Visits |
|---|---|
| A | 16.10 |
| B | 9.68 |
| C | 6.50 |
| D | 4.30 |
| F/W | 3.27 |

### **Interpretation**
Students earning higher grades tended to attend AARC services more consistently than students with lower grades.

---

## **Correlation Results**

| Variables Compared | Correlation |
|---|---|
| Total Visits vs Total Duration | 0.9467 |
| Total Visits vs Grade | 0.2945 |
| Total Duration vs Grade | 0.2608 |

### **Interpretation**
- AARC attendance showed a positive relationship with academic performance.
- Correlations were weak-to-moderate, indicating attendance is only one contributing factor to student success.
- Visit frequency and total visit duration were strongly related.

---

## **Biology Course Analysis**

Biology-related attendance displayed weak positive relationships with grades.

| Variables Compared | Correlation |
|---|---|
| Biology Visits vs Grade | 0.1789 |
| Biology Duration vs Grade | 0.1208 |

### **Interpretation**
Biology students who attended AARC services more frequently tended to perform slightly better academically, though attendance alone did not strongly explain outcomes.

---

# 🎯 Practical Implications

The analysis suggests:

- Consistent academic support engagement may improve student outcomes.
- STEM courses generate the highest tutoring demand.
- Early and regular AARC attendance may be more beneficial than reactive attendance near examinations.

---

# ⚠️ Limitations

- Correlation does not imply causation.
- Attendance alone cannot explain academic performance.
- Additional factors such as:
  - prior GPA,
  - motivation,
  - course difficulty,
  - instructor variation,
  - and study habits  
  likely influence outcomes.

---

# 🔮 Future Work

Potential extensions of this project include:

- Predictive modeling of student success
- Early intervention detection systems
- Time-to-first-visit analysis
- Longitudinal student tracking
- Incorporation of GPA, classification, and major information

---

# 📂 Repository Structure

```bash
├── AARC_dataset.html
├── AARC_Attendance_Report.docx
├── notebooks/
├── figures/
└── README.md
```

---

# 👨‍💻 Author

**Evans Nortey**  
Graduate Student — Mathematical Sciences (Statistics)  
Stephen F. Austin State University  

**Supervisor:** Dr. Keith Hubbard

---

# 📌 Project Type

Educational Data Analysis | Student Success Analytics | Exploratory Data Analysis (EDA)

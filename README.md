# 🎓 Universidad de la Costa — Student Analytics Dashboard
**Data Mining · Activity I: Data Visualization and Dashboard Deployment**  
**José Escorcia-Gutierrez, Ph.D. · Dept. of Computer Science and Electronics**

---

## 📋 Project Overview

This project performs exploratory data analysis and builds an interactive Streamlit dashboard on the `university_student_data.csv` dataset, which contains student admission, enrollment, retention, and satisfaction data from 2015 to 2024.

---

## 📂 File Structure

```
├── app.py                        # Streamlit dashboard
├── university_student_data.csv  # Dataset
├── requirements.txt              # Python dependencies
├── Activity_I_Notebook.ipynb    # Google Colab notebook (EDA + visualizations)
└── README.md                    # This file
```

---

## 📊 Dataset Columns

| Column | Description |
|---|---|
| `Year` | Academic year (2015–2024) |
| `Term` | Semester: Spring or Fall |
| `Applications` | Number of applications received |
| `Admitted` | Number of students admitted |
| `Enrolled` | Number of students who enrolled |
| `Retention Rate (%)` | % of enrolled students retained |
| `Student Satisfaction (%)` | Average student satisfaction score |
| `Engineering Enrolled` | Students enrolled in Engineering |
| `Business Enrolled` | Students enrolled in Business |
| `Arts Enrolled` | Students enrolled in Arts |
| `Science Enrolled` | Students enrolled in Science |

---

## 🚀 Running the Dashboard Locally

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/universidad-dashboard.git
cd universidad-dashboard

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the app
streamlit run app.py
```

---

## ☁️ Deployment on Streamlit Cloud

1. Push all files to a **public GitHub repository**.
2. Go to [share.streamlit.io](https://share.streamlit.io) and log in.
3. Click **New app** → select your repository and branch.
4. Set **Main file path** to `app.py`.
5. Click **Deploy**.

Make sure `university_student_data.csv` is in the root of the repository (same level as `app.py`).

---

## 📈 Key Findings

- **Applications** grew consistently from 2,500 (2015) to 3,500 (2024), a **+40% increase**.
- **Retention rates** improved from 85% to 90%, showing stronger student success initiatives.
- **Student satisfaction** rose from 78% to 88%, indicating improved institutional quality.
- **Engineering** is the largest and fastest-growing department.
- **Science enrollment** shows a slight downward trend in recent years.
- Spring and Fall terms are nearly identical in enrollment volume, with minimal seasonal variation.

### 💡 Actionable Insight

The university should investigate the **declining Science enrollment** trend while leveraging the success factors from Engineering to potentially reverse this pattern. Targeted recruitment campaigns for Science programs during Spring admissions could help balance departmental growth.

---

## 🛠️ Technologies Used

- Python 3.10+
- Streamlit
- Pandas
- Matplotlib
- Google Colab (EDA notebook)
- GitHub (version control)
- Streamlit Cloud (deployment)

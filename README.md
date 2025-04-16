# Job Application Tracking & Analytics System (Self-Created)

This project is a personal job tracking system designed to manage and analyze my internship and job applications. It combines Excel for data entry with Python, pandas, DuckDB, and machine learning tools for powerful analysis and predictive modeling.

⚠️ Note: This project uses a sample dataset to demonstrate logic and analysis. The real data includes sensitive personal contacts and has not been uploaded to GitHub.


---

## Tools & Technologies Used
- **Excel** – Initial data entry and manual tracking
- **Python (pandas, numpy)** – Data loading, cleaning, and manipulation
- **DuckDB** – In-memory SQL engine for running SQL queries on pandas DataFrames
- **Matplotlib / Seaborn** – Visual exploration and EDA
- **Power BI** – Optional dashboard for interactive job application tracking
- **Scikit-learn** – Machine learning modeling (planned)

---

## Key Features
- Track job applications, platforms, and follow-ups
- Manage recruiter or employee connections and follow-up response status
- Visualize key metrics using **Matplotlib or Power BI**
- Run SQL queries directly on Excel-imported data using **DuckDB**
- Perform **EDA and feature engineering** to prepare for machine learning models

---

## Visualizations
The project includes charts and visuals such as:
- Application responses by industry, platform, and job type
- Follow-up effectiveness by communication channel
- Company-wise application outcomes
- Timeline of application vs. response
- Connection response rates

>  Visuals are created using either:
> - **Matplotlib/Seaborn** for Python-based EDA
> - **Power BI dashboards** for interactive exploration (optional)

---

##  Planned Machine Learning Models
- **Response Prediction** (`yes/no`)
- **Time-to-Response Estimation** (regression)
- **Connection Engagement Modeling** (`good/neutral/poor`)
- **Unsupervised Clustering** to discover application success patterns

---

##  ML Workflow (Planned)
1. Load Excel data → Clean in pandas
2. Join related sheets using `application_id`, `connection_id`
3. Run EDA and visualize insights
4. Engineer features (e.g., `has_connection`, `followup_count`, `job_type_encoded`)
5. Train and evaluate models using `scikit-learn`

---

## Project Goal
To improve the job search process using real data and self-analysis — and apply practical data analytics and machine learning skills to a real-world challenge.

---

## Dataset Structure
This project includes the following sheets:
- `Applications`
- `ApplicationsResponse`
- `FollowupApplications`
- `Connections`
- `FollowupConnections`
- `ResponsiveConnections`

---

## Status
  In progress: EDA, SQL querying, and Matplotlib visualizations  
  Up next: Feature engineering and ML model development

---

## Let’s Connect
Feel free to reach out if you're building something similar or would like to collaborate!

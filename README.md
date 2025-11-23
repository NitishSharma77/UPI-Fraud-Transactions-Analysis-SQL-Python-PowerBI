
# 💳 UPI Fraud & Transaction Analysis – SQL | Python | Power BI

_An end-to-end analytics project analyzing UPI transactions, detecting fraud patterns, validating data integrity, performing EDA, statistical testing, and building an executive dashboard._

---

<h2 id="toc">📌 Table of Contents</h2>
<ul>
  <li><a href="#overview">Overview</a></li>
  <li><a href="#business-problem">Business Problem</a></li>
  <li><a href="#tools-tech">Tools & Technologies</a></li>
  <li><a href="#project-structure">Project Structure</a></li>
  <li><a href="#data-cleaning">Data Validation & Cleaning</a></li>
  <li><a href="#python-eda">Python EDA & Analysis</a></li>
  <li><a href="#sql-db">SQL Database Design</a></li>
  <li><a href="#insights">Key Insights</a></li>
  <li><a href="#impact">Business Impact</a></li>
  <li><a href="#recommend">Recommendations</a></li>
  <li><a href="#dashboards">Dashboards</a></li>
  <li><a href="#author">Author</a></li>
</ul>

---

<h2 id="overview">📘 Overview</h2>
<p>
This project analyzes UPI transactions (1,00,000 records) to identify fraud patterns, detect risky devices, analyze customer & merchant behaviour, and measure operational performance.
<br>
It includes end-to-end workflow: <b>Excel Validation → SQL Database → Python EDA → Statistical Tests → Power BI Dashboard → Final Insights & Recommendations.</b>
</p>

---

<h2 id="business-problem">🧩 Business Problem</h2>
<ul>
  <li>Rising fraud attempts across devices & channels</li>
  <li>Increasing transaction failures</li>
  <li>Weak fraud alert and risk scoring system</li>
  <li>Merchant disputes and customer churn</li>
  <li>Need for a unified dashboard for leadership</li>
</ul>

---

<h2 id="tools-tech">🛠 Tools & Technologies</h2>
<ul>
  <li><b>MySQL</b> – Database design, constraints, ETL</li>
  <li><b>Python</b> – Pandas, Matplotlib, Seaborn, SciPy</li>
  <li><b>Excel</b> – Data validation & quality checks</li>
  <li><b>Power BI</b> – Interactive dashboard</li>
  <li><b>Git & GitHub</b> – Version control</li>
</ul>

---

<h2 id="project-structure">📁 Project Structure</h2>

<pre>
UPI_Transactions_Analysis/
│
├── README.md
├── .gitignore
│
├── Images/
│   ├── Dashboard.png
│   └── Dashboard1.png
│
├── Notebook/
│   ├── Capstone Project.ipynb
│   └── Capstone Report Chart.ipynb
│
├── Power_BI/
│   └── Capstone_Project.pbix
│
├── PPT_Presentation/
│   └── Capstone_Project_Report.pptx
│
├── Report/
│   └── Capstone_Project_Report.pdf
│
├── SQL_Database/
│   ├── upi_project_customer_feedback_surveys.csv
│   ├── upi_project_customer_master.csv
│   ├── upi_project_device_info.csv
│   ├── upi_project_fraud_alert_history.csv
│   ├── upi_project_merchant_info.csv
│   ├── upi_project_upi_account_details.csv
│   └── upi_project_upi_transaction_history.csv
</pre>

---

<h2 id="data-cleaning">🧼 Data Validation & Cleaning</h2>
<ul>
  <li>Foreign key validation across all 7 tables</li>
  <li>Corrected typos in device type, status, and merchant category</li>
  <li>Standardized date formats</li>
  <li>Flagged missing values & created validation_status column</li>
  <li>Created Data Quality Log</li>
</ul>

---

<h2 id="python-eda">🐍 Python EDA & Analysis</h2>
<ul>
  <li>Trend analysis (daily, monthly fraud & transaction volume)</li>
  <li>Device-level fraud ratio</li>
  <li>Merchant performance segmentation</li>
  <li>Failure rate root-cause analysis</li>
  <li>Correlation heatmaps</li>
  <li>Hypothesis testing (ANOVA, t-test, chi-square)</li>
</ul>

---

<h2 id="sql-db">🗄 SQL Database Design</h2>
<ul>
  <li>7 tables with PK–FK constraints</li>
  <li>Relationship validation (1-to-many, many-to-many)</li>
  <li>CHECK constraints for fraud_flag, amount, status</li>
  <li>ER diagram for reference</li>
</ul>

---

<h2 id="insights">🌟 Key Insights </h2>

### 🔍 UPI Fraud Detection Summary
- Total Fraud Cases: <b>2,000 (2%)</b>  
- Highest Risk Segment: <b>Feature Phones → 1.5× higher fraud (551 cases)</b>  
- Failure Rate: <b>5.87% (5,870 failed transactions)</b>  
- Risk Score: <b>No meaningful correlation → ineffective model</b>  
- Fraud Alerts: <b>248 unresolved</b>  
- Fraud Distribution: <b>Evenly spread across regions & channels → platform-wide issue</b>

---

<h2 id="impact">📈 Expected Business Impact </h2>

- 🔒 Reduce fraud from <b>2% → 1.2%</b> (₹33K yearly savings)  
- 💰 Improve transaction success → failures <b>5.87% → 3.5%</b> (₹1L+ additional successful payments)  
- 🚀 Fraud alert backlog reduced <b>to under 5%</b>  
- 📊 Better monitoring of risky devices  
- 😊 Higher customer trust, regulatory compliance, smoother audits  

---

<h2 id="recommend">💡 Recommendations (Updated)</h2>
<ul>
  <li>Enhance Feature Phone Security (extra OTP + awareness sessions)</li>
  <li>Redesign Risk Scoring using ML + behaviour analytics</li>
  <li>Improve Fraud Alert Workflow & reduce backlog</li>
  <li>Infra improvements to reduce failed transactions</li>
  <li>Merchant & customer awareness workshops</li>
  <li>High-value transaction real-time monitoring</li>
</ul>

---

<h2 id="dashboards">📊 Dashboards</h2>

<h3>🔵 Dashboard 1 – Executive Overview</h3>
<img src="Images/Dashboard.png" width="600">

<h3>🔴 Dashboard 2 – Fraud Analysis</h3>
<img src="Images/Dashboard1.png" width="600">

---

<h2 id="author">👤 Author</h2>
<b>Nitish Sharma</b><br>
📧 Email: <b>nitishsharma.id@gmail.com</b><br>
🔗 GitHub: https://github.com/NitishSharma77/<br>
🔗 LinkedIn: https://www.linkedin.com/in/nitish-sharma7/<br>

<hr>
<p>⭐ If you found this project helpful, consider giving the repository a STAR!</p>

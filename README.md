🔐 **SQL Injection Detection System using Machine Learning Concepts (CodeAlpha Task-2)**

🚀 This project was developed as part of my **CodeAlpha Data Science Internship (Task-02)**, where I built a **secure authentication system** and analyzed how **SQL Injection attacks** can be detected and prevented using **parameterized queries** and **data visualization techniques**.

📌 **Project Objective**

The objective of this project is to **secure a login system from SQL Injection attacks** and demonstrate how unsafe inputs can be blocked using proper query handling techniques in databases.

The project also visualizes login security results using graphs for better understanding of **safe vs malicious attempts**.

📊 **Dataset / Database Description**

Instead of a traditional dataset, this project uses a **SQLite database (users.db)** which contains user credentials:

👤 **Username**
🔑 **Password**
🆔 **User ID (Primary Key)**

Two types of login attempts are tested:

✅ **Safe Login Credentials**
❌ **SQL Injection Attack Inputs (Malicious Queries)**

⚙️ **Workflow**

🔹 **1. Database Creation**

A SQLite database is created with a **users table** and sample user records inserted.

🔹 **2. Secure Login System**

A login function is implemented using **parameterized SQL queries** to prevent SQL Injection attacks.

✅ Inputs are treated as **data, not executable code**
✅ Prevents manipulation of SQL statements

🔹 **3. SQL Injection Simulation**

The system is tested with:

✔️ Valid login credentials
✔️ Malicious input like **' OR '1'='1**

🎯 The system successfully **blocks the attack**.

🔹 **4. Security Analysis**

Results of login attempts are analyzed:

✅ Safe Login → **Allowed (1)**
❌ SQL Injection → **Blocked (0)**

🔹 **5. Data Visualization**

Different graphs are used to visualize system security:

📊 **Bar Chart** → Compares safe vs attack attempts
🥧 **Pie Chart** → Shows blocked vs allowed access ratio
📈 **Line Chart** → Displays login attempt pattern
📍 **Scatter Plot** → Visual representation of detection

🔹 **6. Report Generation**

A CSV file (**security_report.csv**) is generated to store login results for further analysis.

🛠️ **Technologies & Tools**

🐍 **Programming Language:** Python

📦 **Libraries Used:**

* **SQLite3** – Database management
* **Pandas** – Data handling
* **Matplotlib** – Visualization
* **Seaborn** – Advanced graphs

💻 **Environment:** Jupyter Notebook / Python Script

🔐 **Key Features**

✅ Secure login system using parameterized queries
✅ SQL Injection attack detection
✅ Database security implementation
✅ Graph-based security analysis
✅ Automatic report generation

🎯 **Outcome**

This project successfully demonstrates how **SQL Injection attacks work** and how they can be prevented using **secure coding practices**. It also provides **visual insights into system security performance** using different types of graphs.

#Python #DataScience #CodeAlpha #CyberSecurity #SQLInjection #MachineLearning #SQLite #Pandas #Matplotlib #DataAnalytics #InternshipProject #LearningByDoing

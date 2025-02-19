# **Mental Disorder Classification (2023): A Data Analysis Project**

## 📌 **Introduction**  
Mental health is an essential yet often overlooked aspect of well-being. With my background in **psychology, mental health, and data science**, I have witnessed firsthand how psychological symptoms impact individuals' lives. This project integrates these disciplines to analyze patterns in mental disorder symptoms and classifications, aiming to contribute to a deeper understanding of mental health conditions.  

This study explores data from **120 psychology patients and 17 key symptoms**, leveraging **Google Sheets, R, and Tableau** to uncover insights that could aid mental health awareness and research.  

---

## 📖 **Table of Contents**  
1. [Why This Project?](#-why-this-project)  
2. [Project Overview](#-project-overview)  
3. [Data Cleaning & Preprocessing](#-data-cleaning--preprocessing)  
4. [Data Analysis & Feature Exploration](#-data-analysis--feature-exploration)  
5. [Visualizing Data with Tableau](#-visualizing-data-with-tableau)  
6. [Insights & Final Report](#-insights--final-report)  
7. [Tools Used](#-tools-used)  
8. [Dataset Sources & Provenance](#-dataset-sources--provenance)  
9. [Mental Health Resources](#-mental-health-resources)  
10. [Stay Connected](#-stay-connected)  

---

## 🎯 **Why This Project?**  
Mental health disorders are **complex and multifaceted**. A data-driven approach allows us to:  

- Identify **patterns in symptoms** across different mental disorders.  
- Analyze **relationships** between symptoms and expert diagnoses.  
- Utilize **data science techniques** to perform exploratory data analysis and visualizations.  
- Contribute to discussions on **mental health awareness** through data storytelling.  

My firsthand experience working with patients struggling with severe mental health and substance use disorders has shown me the importance of early symptom identification and accurate diagnoses. This project aims to bridge the gap between data science and mental health awareness.

---

## 📂 **Project Overview**  
This project is structured into four key phases:

### **1. Data Cleaning & Preprocessing**  
- Removing unnecessary columns (e.g., patient IDs).  
- Converting text-based responses into numerical values for analysis.  
- Standardizing Yes/No responses for consistency.  
- Assigning numeric values to mental health diagnoses.  

### **2. Data Analysis & Feature Exploration**  
- Investigating symptom severity across different disorders using logical regression machine learning model with R.
- Comparing diagnosis distributions (Bipolar Type 1, Bipolar Type 2, Depression, and Normal).  
- Creating new scores to quantify mental health symptoms.  

### **3. Visualizing Data with Tableau**  
- Developing interactive dashboards to illustrate symptom trends.  
- Highlighting correlations between symptoms and diagnoses.  

### **4. Insights & Final Report**  
- Summarizing key findings.  
- Discussing potential real-world applications.  

🔗 **📎 Dataset Link:** [Google Sheets Dataset](https://docs.google.com/spreadsheets/d/148BXUigQAvB5ID8VKiW5NMGWYK8hgyVnn6YMBGEKIRE/edit?usp=sharing)  

---

## 📊 **Data Cleaning & Preprocessing**  
To ensure the dataset is structured for effective analysis, the following steps were taken:  

### **1. Removed Unnecessary Data**  
- The **"Patient Number"** column was removed as it did not contribute to the analysis.  

### **2. Converted Text Responses to Numerical Values**  
Some symptom responses were originally in text format (e.g., "Usually," "Sometimes," "Seldom"). These were converted into a numerical scale for consistency:  

| Text Response  | Numeric Value |
|---------------|--------------|
| Most-Often    | 4            |
| Usually       | 3            |
| Sometimes     | 2            |
| Seldom        | 1            |
| No            | 0            |
| Yes           | 1            |

### **3. Standardized Yes/No Responses**  
Columns such as **"Mood Swing"** and **"Suicidal Thoughts"** originally contained Yes/No answers. These were converted to numerical values:  

- **Yes → 1**  
- **No → 0**  

### **4. Assigned Numeric Values to Diagnoses**  
To facilitate analysis, categorical diagnoses were converted to numerical labels:  

| Diagnosis        | Numeric Value |
|-----------------|--------------|
| Bipolar Type-1  | 3            |
| Bipolar Type-2  | 2            |
| Depression      | 1            |
| Normal         | 0            |

### **5. Created Symptom Scores**  
To better analyze mental health trends, four composite symptom scores were introduced:  

- **Mood Instability Score** – Measures **mood swings, sadness, and euphoria**.  
- **Cognitive Functioning Score** – Assesses **overthinking, concentration, and optimism**.  
- **Sleep Issues Score** – Tracks **exhaustion and sleep disorders**.  
- **Self-Harm Risk Score** – Highlights signs of **self-harm risk** (e.g., suicidal thoughts, nervous breakdowns).  

---

## 📊 **Data Analysis & Feature Exploration**  
- Investigating symptom severity across different disorders using logical regression machine learning model with R.
- Comparing diagnosis distributions (Bipolar, Depression, Normal).  

*👉 (Details will be updated soon!)*  

---

## 📊 **Visualizing Data with Tableau**  
- Creating interactive Tableau dashboards to illustrate findings.  
- Identifying correlations between symptoms and diagnoses.  

🔗 *Stay tuned for visualizations!*  

---

## 📊 **Insights & Final Report**  
- Summarizing key findings.  
- Discussing real-world applications of the data.  

---

## 🚀 **Tools Used**  
- **Google Sheets** – Data entry and preprocessing.  
- **R** – Statistical analysis and data transformation.  
- **Tableau** – Data visualization and insights.  

---

## 📌 **Dataset Sources & Provenance**  
This dataset originates from a **private psychology clinic** and has been made publicly available for research and analysis.  

🔗 **Primary Source:** [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/0FNET5)  
🔗 **Kaggle Dataset:** [Mental Disorder Classification](https://www.kaggle.com/datasets/cid007/mental-disorder-classification/data)  

---

## 🧠 **Mental Health Resources**  
If you or someone you know is struggling, support is available:  

- [988 Suicide & Crisis Lifeline](https://988lifeline.org/) – Call or text **988** (U.S.).  
- [National Alliance on Mental Illness (NAMI)](https://www.nami.org/) – Mental health advocacy.  
- [Crisis Text Line](https://www.crisistextline.org/) – Text **HOME** to **741741** for 24/7 support.  
- [Befrienders Worldwide](https://www.befrienders.org/) – International mental health support.  
- [WHO Mental Health Resources](https://www.who.int/health-topics/mental-health) – Global mental health guidelines.  

💜 **You are not alone.**  

---

## 📢 **Stay Connected!**  
📩 Want to discuss this project or collaborate? Reach out via [LinkedIn](https://www.linkedin.com/in/yoadabzeleke/)!  

# **Mental Disorder Classification (2023): A Data Analysis Project**  

📌 **Introduction**  
Mental health is a critical yet often overlooked aspect of well-being. Having worked in behavioral and mental health, I have seen firsthand how psychological symptoms impact individuals' lives. This project combines my background in **psychology, mental health, and data science** to explore patterns in mental disorder symptoms and classifications.  

By analyzing data from **120 psychology patients with 17 key symptoms**, I aim to uncover insights that could contribute to a better understanding of mental health conditions.  

---  

## 📖 **Table of Contents**  

1. **Why This Project?** 
2. **Project Contents**
3. **Day 1 - Data Cleaning & Handling Missing Values**
4. **Day 2 - Data Analysis & Feature Exploration**  
5. **Day 3 - Visualizing Data with Tableau**
6. **Day 4 - Insights & Final Report**
7. **Tools Used** 
8. **Dataset Sources & Provenance** 

---  

## 🎯 **Why This Project?**  

Mental health disorders are **complex and multifaceted**. A data-driven approach allows us to:  

- Identify **patterns in symptoms** across different mental disorders.  
- Analyze **relationships** between symptoms and expert diagnoses.  
- Utilize **Google Sheets, R, and Tableau** to perform exploratory data analysis and visualizations.  
- Contribute to discussions on **mental health awareness** through data storytelling.  

---  

## 📂 **Project Contents**  

Each phase of the project is carefully documented, covering **data preparation, analysis, and visualization**:  

### **Day 1 - Data Cleaning & Handling Missing Values**  
- Preprocessing raw patient data  
- Structuring symptom data into numerical and categorical formats  

### **Day 2 - Data Analysis & Feature Exploration**  
- Investigating symptom severity across different disorders  
- Comparing diagnosis distributions (Bipolar Type 1, Bipolar Type 2, Depression, and Normal)  

### **Day 3 - Visualizing Data with Tableau**  
- Creating dashboards to illustrate symptom trends  
- Highlighting correlations between symptoms and diagnoses  

### **Day 4 - Insights & Final Report**  
- Summarizing key findings from the dataset  
- Discussing potential **real-world applications** of the analysis  

---  

## 📊 **Day 1 - Data Cleaning & Handling Missing Values**  

To ensure the dataset is **structured and ready for analysis**, I focused on **cleaning and organizing the data**. Here’s what I did:  

### **1. Removed Unnecessary Data**  
- **Removed the "Patient Number" column** since it wasn’t useful for analysis.  

### **2. Converted Text Responses to Numbers**  
Some symptom responses were in text format (e.g., "Usually," "Sometimes," "Seldom"), which can be difficult for machine learning models to process. I **converted them into a numerical scale (0 to 4)**:  

| Text Response  | Numeric Value |
|---------------|--------------|
| Most-Often    | 4            |
| Usually       | 3            |
| Sometimes     | 2            |
| Seldom        | 1            |
| No           | 0            |
| Yes          | 1            |

### **3. Standardized Yes/No Answers**  
Columns like "Mood Swing" or "Suicidal Thoughts" had **Yes/No answers**, so I standardized them as follows:  

- **Yes → 1**  
- **No → 0**  

### **4. Organized Diagnoses for Machine Learning**  
The **"Expert Diagnose"** column originally contained text labels like "Bipolar Type-2" and "Depression." To make it **easier for machine learning models to process**, I assigned numerical values:  

| Diagnosis        | Numeric Value |
|-----------------|--------------|
| Bipolar Type-1  | 3            |
| Bipolar Type-2  | 2            |
| Depression      | 1            |
| Normal         | 0            |

### **5. Created New Scores to Identify Patterns**  
To **better understand symptom patterns**, I grouped related symptoms into **four new scores**:  

- **Mood Instability Score** – Measures **mood swings, sadness, and euphoria**  
- **Cognitive Functioning Score** – Assesses **overthinking, concentration, and optimism**  
- **Sleep Issues Score** – Tracks **exhaustion and sleep disorders**  
- **Self-Harm Risk Score** – Highlights signs of **self-harm risk** (e.g., suicidal thoughts, nervous breakdowns)  

💾 **📎 Dataset Link:** [Google Sheets Dataset](https://docs.google.com/spreadsheets/d/148BXUigQAvB5ID8VKiW5NMGWYK8hgyVnn6YMBGEKIRE/edit?usp=sharing)  

This **cleaned and structured dataset** is now ready for further analysis! 🚀  

---

## 📊 **Day 2 - Data Analysis & Feature Exploration**  

🔍 Investigating symptom severity across different disorders  
📊 Comparing diagnosis distributions (Bipolar, Depression, Normal)  

*👉 (Details will be updated soon!)*  

---

## 📊 **Day 3 - Visualizing Data with Tableau**  

🎨 **Tableau Dashboards** for clear mental health insights  
🔗 *Stay tuned for visualizations!*  

---

## 📊 **Day 4 - Insights & Final Report**  

📝 Summarizing key findings  
💡 Discussing real-world applications  

---

## 🚀 **Tools Used**  

- **Google Sheets** – Initial data exploration and cleaning  
- **R** – Statistical analysis and machine learning preparation  
- **Tableau** – Data visualization and storytelling  

---

## 📌 **Dataset Sources & Provenance**  

This dataset originates from a **private psychology clinic** and has been made publicly available for research and analysis.  

🔗 **Primary Source:** [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/0FNET5)  
🔗 **Kaggle Dataset:** [Mental Disorder Classification](https://www.kaggle.com/datasets/cid007/mental-disorder-classification/data)  

---

🎭 **Bridging Psychology & Data Science**  
This project showcases how **data science and psychology** intersect to provide meaningful insights into **mental health**. Let's explore mental disorders through data! 🧠📊  

---

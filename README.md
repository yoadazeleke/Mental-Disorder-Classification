# **Mental Disorder Classification (2023): A Data Analysis Project**  

## 📖 **Table of Contents**  
1. [Introduction](#introduction)  
2. [Why This Project?](#why-this-project)  
3. [Project Contents](#project-contents)  
   - [Day 1 - Data Cleaning & Handling Missing Values](#day-1---data-cleaning--handling-missing-values)  
   - [Day 2 - Data Analysis & Feature Exploration](#day-2---data-analysis--feature-exploration)  
   - [Day 3 - Visualizing Data with Tableau](#day-3---visualizing-data-with-tableau)  
   - [Day 4 - Insights & Final Report](#day-4---insights--final-report)  
4. [Tools Used](#tools-used)  
5. [Dataset Sources & Provenance](#dataset-sources--provenance)  
6. [Detailed Analysis](#detailed-analysis)  
   - [Day 1: Cleaning the Data & Handling Missing Values](#day-1-cleaning-the-data--handling-missing-values)  
7. [Google Sheets Link](#google-sheets-link)  

---

## 📌 **Introduction**  
Mental health is a critical yet often overlooked aspect of overall well-being. Having worked in behavioral and mental health, I have seen firsthand how psychological symptoms impact individuals' lives. This project combines my background in **psychology, mental health, and data science** to explore patterns in mental disorder symptoms and classifications. By analyzing data from **120 psychology patients with 17 key symptoms**, I aim to uncover insights that could contribute to better understanding and awareness of mental health conditions.  

---

## 🎯 **Why This Project?**  
Mental health disorders are complex and multifaceted. A data-driven approach allows us to:  
✔️ Identify patterns in symptoms across different mental disorders.  
✔️ Analyze relationships between symptoms and expert diagnoses.  
✔️ Utilize **Google Sheets, R, and Tableau** to perform exploratory data analysis and visualizations.  
✔️ Contribute to discussions on mental health awareness through data storytelling.  

---

## 📂 **Project Contents**  

### 🔹 **Day 1 - Data Cleaning & Handling Missing Values**  
- Preprocessing raw patient data  
- Structuring symptom data into numerical and categorical formats  

### 🔹 **Day 2 - Data Analysis & Feature Exploration**  
- Investigating symptom severity across different disorders  
- Comparing diagnosis distributions (Bipolar Type 1, Bipolar Type 2, Depression, and Normal)  

### 🔹 **Day 3 - Visualizing Data with Tableau**  
- Creating dashboards to illustrate symptom trends  
- Highlighting correlations between symptoms and diagnoses  

### 🔹 **Day 4 - Insights & Final Report**  
- Summarizing key findings from the dataset  
- Discussing potential real-world applications of the analysis  

---

## 🚀 **Tools Used**  
📊 **Google Sheets** – Initial data exploration and cleaning  
📉 **R** – Statistical analysis and machine learning preparation  
📈 **Tableau** – Data visualization and storytelling  

---

## 📌 **Dataset Sources & Provenance**  
This dataset originates from a private psychology clinic and has been made publicly available for research and analysis.  

🔗 **Primary Source:** [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/0FNET5)  
🔗 **Kaggle Dataset:** [Mental Disorder Classification](https://www.kaggle.com/datasets/cid007/mental-disorder-classification/data)  

---

## 📊 **Detailed Analysis**  

### **Day 1: Cleaning the Data & Handling Missing Values**  

For the first day, I focused on **cleaning and organizing the dataset** to make it easier to analyze and use for machine learning. Here’s what I did:  

#### **1. Removed Unnecessary Data**  
- The dataset originally had a *"Patient Number"* column, which wasn’t useful for analysis, so I **removed it**.  

#### **2. Converted Text Responses to Numbers**  
- Some columns had answers like *"Usually," "Sometimes," and "Seldom."* Since machine learning works better with numbers, I changed these into a **scale from 0 to 4**:  
  - *Most-Often → 4*  
  - *Usually → 3*  
  - *Sometimes → 2*  
  - *Seldom → 1*  
  - *No → 0, Yes → 1*  

#### **3. Standardized Yes/No Answers**  
- Some columns had simple **Yes/No responses** (like *"Mood Swing"* or *"Suicidal Thoughts"*). I changed these to **0 for No** and **1 for Yes** to keep things consistent.  

#### **4. Organized Diagnoses for Machine Learning**  
- The *"Expert Diagnose"* column had text labels like **"Bipolar Type-2" and "Depression."** I assigned them **numbers** so that a model can understand them better:  
  - *Bipolar Type-1 → 3*  
  - *Bipolar Type-2 → 2*  
  - *Depression → 1*  
  - *Normal → 0*  

#### **5. Created New Scores to Find Patterns**  
To get a **better understanding of mental health patterns**, I grouped related symptoms into **four new scores**:  
- **Mood Instability Score** – Based on mood-related symptoms (Sadness, Mood Swings, Euphoric)  
- **Cognitive Functioning Score** – Measures thinking patterns (Overthinking, Concentration, Optimism)  
- **Sleep Issues Score** – Tracks exhaustion and sleep disorders  
- **Self-Harm Risk Score** – Highlights signs of self-harm risk (Suicidal Thoughts, Nervous Breakdowns)  

---

## 🔗 **Google Sheets Link**  
Here is the dataset with all three data sheets:  
📊 **[Google Sheets: Mental Disorder Classification Data](https://docs.google.com/spreadsheets/d/148BXUigQAvB5ID8VKiW5NMGWYK8hgyVnn6YMBGEKIRE/edit?usp=sharing)**  

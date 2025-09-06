# 💤 Sleep Disorder Analysis Dashboard  
![Dashboard](https://github.com/user-attachments/assets/f4fbbc61-053e-4ab0-a49a-523a0a6a45a1)


Welcome to the **Sleep Disorder Analysis Dashboard Project**!  
This repository contains a comprehensive **Power BI dashboard** that uncovers meaningful insights into sleep disorders such as **Insomnia** and **Sleep Apnea**. The project highlights how **data analytics, visualization, and storytelling** can be combined to drive awareness and actionable insights around sleep health.  

---


## 📊 Project Overview  

Sleep is one of the most essential aspects of human health, directly affecting productivity, mental well-being, and quality of life. Disorders like **Insomnia** and **Sleep Apnea** are becoming increasingly common due to lifestyle changes, stress, and unhealthy habits.  

The aim of this project is to:  
- Analyze sleep disorder data using **data analytics** techniques.  
- Develop a **Power BI dashboard** that highlights sleep patterns and identifies areas of concern.  
- Provide **clear, visual insights** that could help healthcare professionals, researchers, and individuals understand sleep health better.  

---

## 📂 Dataset Description  

The dataset contains multiple attributes related to individuals and their sleep patterns.  

### Key Columns:  
- **Person ID** – Unique identifier for each individual.  
- **Gender** – Male or Female.  
- **Age** – Age in years.  
- **Occupation** – Job role of the individual.  
- **BMI Category** – Underweight, Normal, Overweight, Obese.  
- **Sleep Disorder** – Type of disorder (Insomnia, Sleep Apnea, or None).  
- **Sleep Duration (hours)** – Average daily sleep duration.  
- **Quality of Sleep (scale 1–10)** – Self-reported sleep quality score.  
- **Stress Level (scale 1–10)** – Reported stress levels.  
- **Daily Steps** – Average steps taken daily.  



## 🎯 Objective of the Project  

The core objectives include:  
1. **Understanding Sleep Patterns** – Identify how duration, quality, and stress levels vary across individuals.  
2. **Identifying Disorders** – Quantify prevalence of **Insomnia** and **Sleep Apnea**.  
3. **Building KPIs** – Derive performance metrics for quick insights.  
4. **Segmentation** – Compare sleep health across **age groups, gender, BMI, and occupation**.  
5. **Storytelling with Data** – Present insights in a way that’s **interactive, visually engaging, and informative**.  

---

## 🛠️ ETL Process (Data Preparation)  

Data preparation followed a structured ETL pipeline:  

1. **Extract**  
   - Imported the dataset from CSV format into **Power BI Desktop**.  

2. **Transform**  
   - Verified column headers and corrected formatting issues.  
   - Checked for **null values** and handled them appropriately.  
   - Removed **duplicate rows**.  
   - Converted data types (e.g., integers for age, text for categories).  
   - Created new calculated columns, such as:  
     - **Weekend vs Weekday classification**.  
     - **Sleep Score formula**.  
     - **Shipping days (for other projects)** – applied same methodology here for consistency.  

3. **Load**  
   - Loaded the cleaned dataset into **Power BI** for visualization and modeling.  

---


## 📌 KPIs and Metrics  

### Core KPIs Built in Power BI:  
1. **Insomnia Count** – Total individuals diagnosed with insomnia.  
2. **Sleep Apnea Count** – Total individuals diagnosed with sleep apnea.  
3. **Average Sleep Duration (Insomnia)** – Average hours of sleep for insomniacs.  
4. **Average Sleep Duration (Apnea)** – Average hours of sleep for sleep apnea patients.  
5. **Sleep Score (Insomnia)** – Weighted score based on duration, quality, and stress.  
6. **Sleep Score (Apnea)** – Same metric applied to sleep apnea cases.  
7. **Average Quality of Sleep** – By disorder type.  
8. **Average Stress Level** – By disorder type.  
9. **Insomnia %** – Proportion of dataset with insomnia.  
10. **Apnea %** – Proportion of dataset with sleep apnea.  
11. **Sleep Disorder % (overall)** – Share of population with any disorder.  

---

## 🖼️ Dashboard Walkthrough  

The dashboard was designed to be **clean, professional, and interactive**.  

### Key Visuals:  
- **Cards** – Show disorder counts, percentages, and average metrics.  
- **Line Charts** – Track how quality and stress levels vary across **age groups**.  
- **Stacked Bar Charts** – Display BMI distribution for Insomnia vs Apnea patients.  
- **Column Charts** – Show steps taken by individuals across occupations.  
- **Donut Charts** – Provide a snapshot of overall disorder percentages.  
- **Slicer** – Gender filter for dashboard-wide impact.  

### Layout:  
- **Top Section**: Quick KPIs (snapshot view).  
- **Middle Section**: Disorder comparison visuals.  
- **Bottom Section**: Demographic and lifestyle segmentation.  

---

## 🔍 Insights & Findings  

Here are some highlights derived from the dashboard:  

- **Prevalence**  
  - Insomnia is more prevalent than Sleep Apnea in the dataset.  

- **Duration vs Quality**  
  - Many insomnia patients get **less than 6 hours** of sleep on average, significantly affecting quality scores.  

- **Stress Correlation**  
  - Higher stress levels correlate with **lower quality sleep**.  
  - This is most visible among working-age adults (25–45).  

- **Age Trends**  
  - Sleep quality tends to decline with age.  
  - Stress is highest among middle-aged groups compared to younger or older groups.  

- **BMI Distribution**  
  - Overweight and obese individuals show a higher prevalence of sleep apnea.  

- **Lifestyle Factors**  
  - Occupations with **higher physical activity** (e.g., labor-intensive jobs) show higher daily steps and relatively fewer sleep disorder cases.  

---

## ⚙️ Tools & Technologies  

- **Power BI Desktop** – Core visualization and dashboarding.  
- **DAX (Data Analysis Expressions)** – Custom measures and KPIs.  
- **Excel** – Initial data cleaning and exploration.  
- **ETL Concepts** – Applied in Power Query for data preparation.  
- **Visualization Design** – Best practices for readability and storytelling.  

---

## 🚧 Challenges Faced  

1. **Data Cleaning** – Handling null values and inconsistent data types.  
2. **DAX Formulas** – Creating accurate measures for **Sleep Score** and percentages.  
3. **Visualization Clarity** – Balancing detail with simplicity in charts.  
4. **Small Dataset Limitation** – Dataset was relatively small, limiting generalizability.  
5. **Storytelling Flow** – Ensuring the dashboard followed a **logical narrative**.  

---

## 🌱 Future Improvements  

1. **Integration with Real-Time Data** – Connect with **IoT devices** (e.g., smartwatches).  
2. **Predictive Modeling** – Apply ML techniques to forecast sleep disorders.  
3. **Expand Demographics** – Include factors like diet, exercise, medical history.  
4. **Mobile Optimization** – Create a Power BI Mobile layout.  
5. **Export Features** – Automated PDF/Excel exports for reports.  

---

## 📊 Dashboard Preview  

👉 [Access Datasets and PBIX File on Google Drive](https://drive.google.com/drive/folders/1V0H1ftWpXpsHngMo6f1vYGDvkZSReOHM?usp=sharing)  

---

## 📬 Contact Information  

📧 Email: [mavuri12558@gmail.com](mailto:mavuri12558@gmail.com)  
🔗 LinkedIn: [Sekhar Mavuri](https://www.linkedin.com/in/sekhar-mavuri-244037200/)  

---


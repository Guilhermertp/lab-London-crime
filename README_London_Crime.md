# 🕵️‍♂️ Project London Crime  
### *Tableau Dashboard Mini Project*

---

Welcome to **Project London Crime**, a data visualization mini project focused on analyzing crime trends in London.  
The goal of this project was to extract insights from crime data and present them in an **interactive** and **visually compelling** Tableau dashboard.

---

## 📊 Project Overview

This project involved several key steps:

- 🔍 **Data Exploration in Jupyter Notebook**  
- 🧹 **Data Preparation for Visualization** *(no cleaning was required)*  
- 🎨 **Dashboard Design in Tableau**  
- 📢 **Publishing the Final Dashboard**

---

## 📦 Dataset

- **Source**: Kaggle  
- **Title**: *London Crime Data – Reported crime in London by borough and LSOA (BigQuery Dataset)*  
- **Link**: [https://www.kaggle.com/datasets/LondonDataStore/london-crime](https://www.kaggle.com/datasets/LondonDataStore/london-crime)

> 📁 A **Jupyter Notebook** is included in this repo for **data exploration only**.  
> No data cleaning was necessary before loading the dataset into Tableau.

---

## 🔗 Live Dashboard

> 📍 **View the interactive dashboard on Tableau Public:**  
> 👉 [**Crime London Dashboard**](https://public.tableau.com/app/profile/guilherme.pereira1124/viz/CrimeLondon_Proj/Dashboard1)

---

## 🧰 Tools & Technologies

- **Tableau** – For building interactive dashboards  
- **Python / Jupyter Notebook** – For data exploration  
- **CSV** – Dataset format  

---

## 🔍 Dashboard Highlights

- 📍 **Crime by Borough** – Geographic distribution of crimes  
- 📅 **Crime Over Time** – Yearly and monthly trends  
- 🧾 **Crime Categories** – Most reported crime types  
- 🔧 **Interactive Filters** – Explore by borough or category  

---

## 🗂️ Project Structure

```
📁 project-london-crime/
├── data/
│   └── london_crime_raw.csv             # Original dataset
├── cleaned_data/
│   └── london_crime_cleaned.csv         # Ready for Tableau (no cleaning needed)
├── exploration/
│   └── london_crime_exploration.ipynb   # Jupyter notebook for data analysis
├── screenshots/
│   └── dashboard-preview.png            # Dashboard preview image
├── tableau/
│   └── london_crime_dashboard.twb       # Tableau workbook file
├── README.md
└── notes.md                             # Optional: reflections or progress notes
```

---

## 📎 How to Use Locally

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/project-london-crime.git
   ```

2. **Open Tableau Desktop**, and load the workbook:

   ```
   tableau/london_crime_dashboard.twb
   ```

3. **Reconnect the data source** if needed, pointing it to:

   ```
   cleaned_data/london_crime_cleaned.csv
   ```

4. Explore, filter, and analyze the dashboard!

---

## 📸 Dashboard Preview

![Dashboard Screenshot](screenshots/dashboard-preview.png)

---

## 💡 Lessons Learned

- ✅ Working with real-world datasets from Kaggle  
- ✅ Performing data exploration using Python & Jupyter  
- ✅ Designing intuitive and effective dashboards in Tableau  
- ✅ Turning raw data into clear, actionable visual insights  

---

## 📝 Credits

Project completed as a **mini coursework project** by [Your Name/Team Name].  
Dataset provided by [Kaggle – London Crime Data](https://www.kaggle.com/datasets/LondonDataStore/london-crime).

---
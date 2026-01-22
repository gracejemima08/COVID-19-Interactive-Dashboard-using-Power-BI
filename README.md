# 🦠 COVID-19 Data Analysis Dashboard using Python & Power BI

This project presents an interactive **COVID-19 Data Analysis Dashboard** built using **Power BI**, where the dataset was first **cleaned and preprocessed using Python (Pandas)** and then visualized using Power BI.

The dashboard helps analyze the spread of COVID-19 cases, deaths, and recoveries across different countries/states over time.

---

## 🎯 Project Objective

The main objective of this project is:

* To clean and preprocess raw COVID-19 data using Python
* To create meaningful insights using Power BI visualizations
* To track trends of confirmed, deaths, and recovered cases
* To build an interactive dashboard for easy data analysis

---

## 🧹 Data Cleaning Using Python

Before importing the dataset into Power BI, the following preprocessing steps were performed in Python:

* Handling missing values
* Converting date columns to proper datetime format
* Removing unnecessary columns
* Renaming columns for better understanding
* Exporting the cleaned dataset to CSV format

```python
df.to_csv("CoranaVirus Data.csv", index=False)
```

---

## 📊 Dashboard Visualizations

The Power BI dashboard includes:

* 📈 Line chart for Confirmed cases over time
* 📉 Line chart for Death cases over time
* 📈 Line chart for Recovered cases over time
* 🔢 Cards for Total Confirmed, Deaths, and Recovered
* 🌍 Map visualization for country/state-wise cases
* 🎚️ Slicer to filter data by Country/State and Date

---

## 🛠️ Tools & Technologies Used

* Python (Pandas, NumPy)
* Power BI Desktop
* Data Visualization Techniques

---

## 📁 Project Workflow

1. Raw COVID-19 dataset collection
2. Data cleaning and preprocessing using Python
3. Export cleaned data to CSV
4. Import CSV into Power BI
5. Create interactive dashboard with visuals and measures

---

## ▶️ How to Use

1. Open the `covid_cleaned_data.csv` file in Power BI
2. Load the dataset
3. Use visuals to explore trends and insights

---

## 📌 Key Insights

* Growth trend of COVID-19 over time
* Comparison of cases across regions
* Analysis of recovery and death rates
* Impact of time on case spread

---

## 👨‍💻 Author

**Grace**

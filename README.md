
# 🎬 Netflix Data Analysis Dashboard

## 📌 Project Overview

This project focuses on **analyzing Netflix data** to uncover insights about content distribution, trends, and audience preferences. Using **Python (Pandas, NumPy, Matplotlib)** for data cleaning and exploratory analysis, and **Power BI** for storytelling through interactive visualizations, this project demonstrates the complete data analysis workflow — from raw data to a professional dashboard.

---

## 🎯 Objectives

* Clean and preprocess Netflix dataset for accurate analysis.
* Explore data to identify trends in content type, ratings, release years, and countries.
* Visualize insights using Matplotlib.
* Build a professional **Power BI dashboard** for interactive storytelling.

---

## 🧠 Key Insights

* Which countries produce the most Netflix content.
* Distribution of **Movies vs TV Shows** on Netflix.
* Content trend analysis over the years.
* Top genres and ratings contributing to Netflix’s library.
* Release pattern insights (year-wise and country-wise).

---

## 🧰 Tools & Technologies

| Tool / Library | Purpose                                     |
| -------------- | ------------------------------------------- |
| **Python**     | Programming language used for data analysis |
| **Pandas**     | Data cleaning, transformation, and analysis |
| **NumPy**      | Numerical operations and data handling      |
| **Matplotlib** | Data visualization using charts and graphs  |
| **Power BI**   | Dashboard creation and data storytelling    |

---

## 📂 Dataset Information

The dataset used in this project is the **Netflix Titles Dataset**, available from **Kaggle**.
**Columns include:**

* `show_id`: Unique ID of each show
* `type`: Movie or TV Show
* `title`: Title of the content
* `director`: Director name
* `cast`: Main actors
* `country`: Country of production
* `date_added`: Date when added to Netflix
* `release_year`: Release year of the content
* `rating`: Content rating (e.g., PG-13, TV-MA)
* `duration`: Duration of movie or number of seasons
* `listed_in`: Genre/category
* `description`: Summary of the content

---

## 🧹 Data Cleaning Steps (Pandas + NumPy)

1. **Importing dataset** using `pandas.read_csv()`
2. **Checking for null values** using `isnull()` and `sum()`
3. **Handling missing values**

   * Filled missing `country`, `rating` using mode/NaN replacement
   * Dropped unnecessary columns if required
4. **Removing duplicates** using `drop_duplicates()`
5. **Feature extraction**

   * Extracted `year` from `date_added`
   * Split genres and counted frequency
6. **Data type conversions** for date columns
7. **Statistical summary** using `describe()` and `info()`

---

## 📊 Exploratory Data Analysis (Matplotlib)

Key visualizations created with **Matplotlib** include:

* **Bar Chart** → Count of Movies vs TV Shows
* **Pie Chart** → Ratings distribution
* **Line Chart** → Trend of content releases over the years
* **Horizontal Bar Chart** → Top 10 countries with most Netflix titles
* **Histogram** → Distribution of movie durations

---

## 📈 Power BI Dashboard

After cleaning and preparing the data in Python, the dataset was imported into **Power BI** to build an interactive dashboard.
The dashboard includes:

* Slicers for **Year**, **Country**, and **Content Type**
* KPIs showing total movies, TV shows, and unique directors
* Visuals for:

  * Country-wise content distribution
  * Top-rated content
  * Year-wise growth trend
  * Genre/category distribution

---

## 💡 Insights from Dashboard

* Movies dominate Netflix’s catalog compared to TV shows.
* USA and India are top contributors to Netflix content.
* The number of titles has significantly increased after 2015.
* The most common rating is **TV-MA**, showing Netflix’s focus on mature content.

---

## 🪄 How to Run the Project

### **1️⃣ Clone this repository**

```bash
git clone https://github.com/yourusername/netflix-analysis.git
```

### **2️⃣ Install Dependencies**

```bash
pip install pandas numpy matplotlib
```

### **3️⃣ Run the Python Script**

```bash
python netflix_analysis.py
```

### **4️⃣ Open the Power BI File**

* Open `netflix_dashboard.pbix` in Power BI Desktop to explore the visuals interactively.

---

## 📁 Project Structure

```
Netflix_Analysis/
│
├── netflix_titles.csv          # Raw dataset
├── netflix_cleaned.csv         # Cleaned dataset for Power BI
├── netflix_analysis.py         # Python analysis script
├── netflix_dashboard.pbix      # Power BI dashboard file
├── README.md                   # Project documentation
└── images/                     # Screenshots for GitHub or LinkedIn post
```

---

## 🧩 Skills Demonstrated

* Data Cleaning & Wrangling (Pandas, NumPy)
* Data Visualization (Matplotlib, Power BI)
* Dashboard Design & Storytelling
* Exploratory Data Analysis (EDA)
* Data-driven insights presentation

---

## 🧑‍💻 Author

**Name:** Madiha Umer
**Role:** Data Analyst | Python | Power BI | Pandas | Matplotlib
**LinkedIn:** [linkedin.com/in/madihaumer](https://linkedin.com/in/madihaumer)


Dataset Source: [Netflix Titles on Kaggle](https://www.kaggle.com/shivamb/netflix-shows)
Tools: Python, Power

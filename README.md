 

## 🧾 Zomato Data Analysis Project

### 📌 Overview

This project focuses on **exploring and analyzing Zomato restaurant data** to uncover insights about restaurant trends, ratings, pricing, and food preferences.
The analysis helps understand how different factors — such as price range, restaurant type (buffet, cafe, etc.), and location — impact restaurant ratings and popularity.

---

### 🎯 Objectives

* Analyze the relationship between **price range** and **customer ratings**
* Compare different types of restaurants such as **Buffets, Cafes, and Shells**
* Identify **top-rated** and **most affordable** restaurants
* Visualize trends using Python libraries to gain business insights

---

### 📊 Dataset

* **Source:** Zomato Restaurant Dataset (public data from Kaggle)
* **Format:** CSV
* **Key Columns:**

  * `Restaurant Name`
  * `Cuisines`
  * `City`
  * `Price Range`
  * `Aggregate Rating`
  * `Votes`
  * `Restaurant Type`

---

### 🧠 Key Insights

* Higher-rated restaurants often belong to **mid-range price categories**.
* **Cafes and Buffets** tend to attract more votes and engagement.
* The **average rating** varies significantly by cuisine type and city.
* Restaurant “Shells” (small standalone outlets) offer competitive pricing with decent ratings.

---

### 🧰 Technologies Used

| Category      | Tools / Libraries           |
| ------------- | --------------------------- |
| Programming   | Python 3                    |
| Data Analysis | Pandas, NumPy               |
| Visualization | Matplotlib, Seaborn         |
| Environment   | Jupyter Notebook (Anaconda) |

---

### 📈 Analysis Performed

1. **Data Cleaning & Preprocessing**

   * Removed missing and duplicate records
   * Converted categorical data to numeric form (where required)

2. **Exploratory Data Analysis (EDA)**

   * Price vs Rating comparison
   * Top restaurant types (Buffet, Cafe, Shells, etc.)
   * Correlation heatmaps
   * City-wise distribution of restaurants

3. **Visualization**

   * Bar plots for price categories
   * Pie charts for restaurant types
   * Scatter plots for rating comparison

---

### 📍 Results

* Identified **top-performing restaurant categories** based on customer ratings.
* Found strong correlation between **restaurant pricing** and **average ratings**.
* Derived insights that can help food businesses optimize pricing and restaurant type strategies.

---

### 📁 Project Structure

```
Zomato_Project/
│
├── data/
│   └── zomato.csv
│
├── notebooks/
│   └── zomato_project.ipynb
│
├── README.md
│
└── requirements.txt
```

---

### ⚙️ How to Run

1. Clone the repository

   ```bash
   git clone https://github.com/<your-username>/zomato-data-analysis.git
   cd zomato-data-analysis
   ```
2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook

   ```bash
   jupyter notebook
   ```
4. Open and run `zomato_project.ipynb`

---

### 📚 Future Enhancements

* Build a **dashboard** for interactive visualization (using Streamlit or Power BI)
* Apply **machine learning models** to predict restaurant ratings
* Perform **sentiment analysis** on user reviews

---

### 👨‍💻 Author

**Aman Jaiswal**
📍 Data Science Enthusiast | Python Developer
📧 [amanjaiswal714355@gmail.com]
🔗 [https://www.linkedin.com/in/aman-jaiswal-09783935b/]

 

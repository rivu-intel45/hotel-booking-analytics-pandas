# 🌐 Hotel Booking Data Analysis with Pandas

Explore a real-world hotel booking dataset using pandas and NumPy.  
Run interactive tasks, answer business questions, and extend the notebook with your own analysis.

---

## ✨ Features at a Glance

- 📊 End-to-end exploratory data analysis (EDA) on hotel bookings.  
- 🧹 Missing data detection and cleanup (e.g., dropping sparse `company` column).
- 💵 Revenue-focused metrics: ADR, total stay cost, average spend.  
- 🧍 Guest behavior insights: repeat guests, length of stay, children/babies.  
- 🌍 Demographics: country distributions and most common last names.
- 📅 Arrival patterns by day of month and day of week.

---

## 🚀 Getting Started
1. Clone the repo
   -git clone https://github.com/rivu-intel45/hotel-booking-analytics-pandas.git cd hotel-booking-data-analysis
3. (Optional) Create a virtual environment
   -python -m venv venv
4. Windows
   -venv\Scripts\activate
5.macOS / Linux
   -source venv/bin/activate
6.Install dependencies
   -pip install -r requirements.txt
7.Launch Jupyter

Then open **`hotel-data-pandas.ipynb`** to start exploring.

---

## 🎯 What You’ll Do Inside the Notebook

### 1. Understand the Data
- Inspect shape, column types, and memory usage of the dataset. 
- Detect missing values and identify the column with the most missing data (`company`). 

### 2. Clean and Prepare
- Drop or handle columns with excessive missing data.  
- Create helper columns like total stay nights (`weeknights + weekend nights`). 

### 3. Answer Business Questions
- What percentage of bookings are from repeat guests (`isrepeatedguest`)?  
- What is the mean ADR (average daily rate) across all stays?  
- What is the average stay length and total revenue per booking?  
- Who paid the highest ADR and how much was it? 

### 4. Explore Patterns
- Top 5 most common guest last names. 
- Top 5 guest country codes.  
- How many arrivals happened between the 1st and 15th of each month? 
- Arrivals by weekday (Monday, Tuesday, etc.).  

---

## 🧪 Try These Interactive Tasks

Use these as prompts while editing or running the notebook:

- Change filters to analyze:
  - Only resort hotels vs city hotels.  
  - Specific years (e.g., 2015 vs 2017).  
  - Bookings from a specific country.  

- Create your own metrics:
  - Revenue per night segment (short vs long stays).  
  - Average ADR per month or season.  
  - Impact of special requests on total cost.  

- Extend the analysis:
  - Visualize distributions (histograms, bar charts, boxplots).  
  - Compare repeat vs non-repeat guests on key metrics.  

---
## ✅ Requirements

-numpy
-pandas
-matplotlib
-seaborn
-jupyter

---

## 💡 Ideas for Further Improvement

- Add interactive widgets with `ipywidgets` to filter by year, country, or hotel type.  
- Turn key tasks into functions so others can easily reuse the analysis.


# ✈️ British Airways Reviews Analysis 📊

## 📌 Project Overview  
The **British Airways Reviews Analysis** project aims to analyze customer feedback and ratings to uncover insights about passenger experience.  
We cleaned the data in **Excel** and created an **interactive dashboard in Tableau**, featuring key performance indicators (KPIs) and visualizations.

---

## 📂 Dataset Description  
The project includes **two** datasets:  

### **1️⃣ ba_reviews.csv** (Customer Reviews Data)  
| Column Name            | Description |
|------------------------|-------------|
| `header`              | Title of the review |
| `author`              | Name of the reviewer |
| `date`                | Date when the review was posted |
| `place`               | Location of the reviewer |
| `content`             | Full review content |
| `aircraft`            | Aircraft type mentioned in the review |
| `traveller_type`      | Type of traveler (Solo, Business, Family, etc.) |
| `seat_type`           | Seat class (Economy, Business, First Class) |
| `route`               | Flight route (departure → arrival) |
| `date_flown`          | Date when the flight took place |
| `recommended`         | Whether the passenger recommends the airline (`Yes/No`) |
| `trip_verified`       | Whether the review was verified (`Yes/No`) |
| `rating`              | Overall rating (out of 10) |
| `seat_comfort`        | Comfort level of the seat |
| `cabin_staff_service` | Rating of the cabin crew service |
| `food_beverages`      | Rating of food & drinks |
| `ground_service`      | Rating of check-in, boarding, etc. |
| `value_for_money`     | Rating of the price-to-service ratio |
| `entertainment`       | Rating of in-flight entertainment |

### **2️⃣ countries.csv** (Country Information Data)  
| Column Name  | Description |
|-------------|-------------|
| `Country`   | Name of the country |
| `Code`      | Country code (ISO standard) |
| `Continent` | Continent where the country is located |
| `Region`    | Specific region of the country |

---

## 🛠️ Data Cleaning & Transformation (Excel)  
- **Handled missing values** in key columns.  
- **Removed duplicates** and inconsistent formatting.  
- **Converted dates** into proper datetime format.  
- **Created new columns** for analysis, such as `Month-Year` for trends.  

---

## 📊 Dashboard & Visualizations (Tableau)  
We designed an **interactive dashboard** with filters & drill-down capabilities.  

### **1️⃣ Key Performance Indicators (KPIs)**
✅ **Avg. Overall Rating**  
✅ **Avg. Cabin Staff Service**  
✅ **Avg. Entertainment**  
✅ **Avg. Food & Beverages**  
✅ **Avg. Ground Service**  
✅ **Avg. Seat Comfort**  
✅ **Avg. Value for Money**  

### **2️⃣ Charts & Visualizations**
📈 **Line Chart:** Average overall rating by month 📅  
🌍 **Map:** Average rating by country 🗺️  
📊 **Bar Chart:** Average rating by aircraft ✈️  
🔽 **Dropdown Filters:**  
  - **Traveller Type** (Solo, Business, Family, etc.)  
  - **Seat Type** (Economy, Business, First Class)  
  - **Aircraft Group**  
  - **Continent**  

---

## 🚀 How to Use This Project  
1️⃣ **Download the cleaned datasets** from the repository.  
2️⃣ **Open Tableau** and load the dataset.  
3️⃣ **Explore the dashboard** to analyze different trends & insights.  

---

## 📥 Dataset Access  
📌 The cleaned dataset is available in the repository.    

---

## 🔗 Project Files  
📁 `ba_reviews.csv` – customer reviews data  
📁 `countries.csv` – Country details data   
📁 `BA_Reviews_Dashboard.twbx` – Tableau dashboard file  
📁 `README.md` – Project documentation  

---

## 📌 Technologies Used  
✅ **Excel** – Data cleaning & transformation  
✅ **Tableau** – Data visualization & dashboard creation  
✅ **GitHub** – Version control & project sharing  

---

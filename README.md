# 🚗 Toronto Motor Vehicle Collision Analysis  
### 📊 Capstone Project – Master of Data Analytics

---

## 📌 Project Overview  
This project analyzes **motor vehicle collision data in Toronto** using real-world data from the **Toronto Police Service Open Data Portal**.

The objective is to identify **patterns in collisions**, understand **high-risk factors**, and build **predictive models** to estimate the likelihood of fatal accidents.

This project combines:
- Python (Data Analysis & Machine Learning)
- Power BI (Interactive Dashboard)
- Data Visualization & Storytelling

---

## 📂 Dataset  
- **Source:** Toronto Police Service Open Data  
- **Records:** 770,000+ collisions  
- **Time Period:** 2014 – 2025  

---

## ⚙️ Project Workflow  

### 1️⃣ Data Preprocessing  
- Removed duplicates  
- Handled missing values  
- Converted data types  
- Standardized categorical variables  

### 2️⃣ Feature Engineering  
- Night indicator  
- Weekend indicator  
- Rush hour indicator  

### 3️⃣ Exploratory Data Analysis (EDA)  
- Yearly and monthly trends  
- Day-of-week patterns  
- Hourly collision distribution  
- Neighbourhood & division hotspots  

---

## 📊 Power BI Dashboard  

### 🔹 Dashboard Home  
![Dashboard Home](home.png)

### 🔹 Collision Overview  
![Overview](overview.png)

### 🔹 Neighbourhood Analysis  
![Neighbourhood](neighbourhood.png)

### 🔹 Time Analysis  
![Time Analysis](time.png)

### 🔹 Geography Analysis  
![Geography](geography.png)

### 🔹 Division Analysis  
![Division](division.png)

### 🔹 Decomposition Tree  
![Decomposition Tree](decomposition.png)

### 🔹 Key Influencers  
![Key Influencers](key_influencers.png)

### 🔹 Methodology  
![Methodology](methodology.png)

### 🔹 Recommendations  
![Recommendations](recommendations.png)

---

## 🔍 Key Insights  

- 📈 Collision frequency peaks during **afternoons (12 PM – 6 PM)**  
- 📅 **Fridays** have the highest collision volume  
- 🍂 **Late summer & early fall (September)** show increased activity  
- 📍 Hotspots:
  - Wexford/Maryvale  
  - Division D42  
- 🚶 Pedestrians are more vulnerable to severe outcomes  

---

## 🤖 Machine Learning  

### Models Used:
- Logistic Regression  
- Random Forest  
- XGBoost  

### Final Model:
**Tuned Random Forest**

### Performance:
- Accuracy: ~67%  
- Recall (Fatal): ~44%  
- Precision: ~25%  

📌 Focus was on **recall**, as detecting fatal collisions is more critical than overall accuracy.

---

## ⚠️ Challenges  

- Class imbalance (~17% fatal cases)  
- Missing real-world variables (weather, speed, driver behavior)  
- Precision vs Recall trade-off  

---

## 💡 Recommendations  

- Target enforcement during **peak hours (afternoon & Fridays)**  
- Focus on **high-risk areas**  
- Improve **road infrastructure & safety measures**  
- Increase **public awareness campaigns**  

---

## 🛠️ Tools & Technologies  

- Python (Pandas, NumPy, Scikit-learn)  
- Power BI  
- Machine Learning  
- Data Visualization  

---

## 👨‍💻 Contributors  

- Sumit Chhillar  
- Team Members  

---

## ⭐ Conclusion  

This project demonstrates how **data analytics and machine learning** can be used to solve **real-world public safety problems** and support **data-driven decision-making**.

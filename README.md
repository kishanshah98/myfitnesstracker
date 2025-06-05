# 🏃‍♂️ Running Performance Tracking & Analysis

![Data Screenshot](images/image1.jpg)

## 📌 Project Overview  
This project tracks and analyzes my personal running data using **Microsoft Excel** for data logging and **Tableau** for interactive dashboards. The goal is to uncover trends in **pace**, **distance**, **duration**, and external factors (like environment and time of day) to evaluate performance improvement over time.

---

## 📊 Data Summary  
The dataset includes running logs from **July 2024 to present**, capturing the following metrics:

- **Date**
- **Distance (miles)**
- **Length of Time Running (minutes)**
- **Avg Pace (min/mile)**
- **Environment** (Indoor/Outdoor)
- **Time of Day** (Morning/Afternoon/Evening)

Runs are recorded manually in Excel and visualized through Tableau Public for ongoing performance insights.

![Data Screenshot](images/image2.png)

---

## 📈 Dashboard Highlights  

- **Fastest Pace:** 8.2 min/mile  
- **Longest Run:** 13.8 miles  
- **Total Runs:** 91  
- **Improvement in Avg Pace:** -2.0 min/mile  

📊 **Interactive Dashboard**:  
[View on Tableau Public](https://public.tableau.com/shared/FQK4J32JH?:display_count=n&:origin=viz_share_link)

![Dashboard Screenshot](images/image3.png)

---

## 🔍 Key Insights  

### ✅ Pace & Distance Trends  
- Steady **improvement in average pace** over time  
- **Distances gradually increased**, indicating improving endurance

### 🌅 Time of Day Performance  
- **Morning runs** had the fastest pace on average  
- Run breakdown: 45 morning, 29 afternoon, 17 evening  
- Time of day seems to impact pace more than distance

### 🏠 Indoor vs Outdoor  
- Most runs were **indoor** (65 out of 91)  
- **Indoor runs** were significantly faster on average based on experimentation  
- See analysis below for full A/B test results

---

## 🧪 Experimentation: Indoor vs. Outdoor Running Performance

To explore how environment impacts performance, I conducted a simulated A/B test comparing **indoor** versus **outdoor** runs using my personal running data.

- **Group A (Indoor runs)**: 9.10 min/mile (average pace)  
- **Group B (Outdoor runs)**: 9.33 min/mile (average pace)  
- **T-Statistic**: -2.37  
- **P-Value**: 0.0219

Using a **t-test**, I found that indoor runs were approximately **0.23 minutes per mile faster** on average, and the result was **statistically significant** (p < 0.05). This suggests that controlled environments may lead to better pacing — a meaningful insight into training conditions.

This experiment demonstrates how A/B testing and statistical analysis can be applied to behavioral performance data, reflecting the kind of data-driven experimentation I’d apply in real-world business scenarios.

---

## 🧪 Experimentation: Time of Day and Running Performance

To further explore how **time of day** impacts performance, I conducted a **one-way ANOVA** comparing average pace across **Morning**, **Afternoon**, and **Evening** runs.

- **Average Morning Pace**: 9.06 min/mile  
- **Average Afternoon Pace**: 9.24 min/mile  
- **Average Evening Pace**: 9.30 min/mile  
- **F-Statistic**: 2.46  
- **P-Value**: 0.0913

Although **morning runs were the fastest on average**, the ANOVA test showed that the difference was **not statistically significant** (p > 0.05). This suggests there may be a trend, but more data is needed to confirm a real difference.

This experiment demonstrates the use of **A/B/C testing and variance analysis** to assess how behavioral conditions impact outcomes — a concept widely applicable in experimentation-heavy business environments like personalization or promo testing.

---

## 🔮 Future Work  
- Add new metrics like heart rate and elevation 
- Use time series forecasting to estimate future pace improvements  
- Develop automated alerts using Excel VBA to flag high/low performance days  

---

## 🧠 Tools Used  
- **Microsoft Excel** – Data logging  
- **Tableau Public** – Dashboard creation and data visualization

Stay tuned for ongoing updates as I continue tracking and analyzing my performance!


# 🚲 San Francisco Bay Area Bike-Sharing Analysis

## 📌 Overview
This project analyzes bike-sharing trip data from the San Francisco Bay Area, consisting of **183,412 entries** across **16 attributes**.  
The dataset includes details such as:
- **Trip Duration** (in seconds)
- **Start & End Time** (with timestamps and dates)
- **Start & End Station Names** with coordinates
- **Customer Type** (Subscriber or Customer)
- **Bike Share for Entire Trip** flag
- **Rental Access Method**
- **User Demographics** (birth year, gender)

A 3D chart combining multiple variables was used to illustrate the correlation between **start time**, **end time**, and **trip duration**.

---

## 📊 Key Findings

### 🔍 Relationships Observed
- Trip durations are evenly and reasonably distributed between start and end times.
- **Age & Duration:** Users born since 1980 tend to take longer trips, indicating younger riders generally ride longer.
- **Gender Distribution:** Males constitute the majority of riders across all trips.

### 🤝 Feature Interactions
- No unusual or surprising interactions were found between the investigated features.
- The data patterns align logically with expectations based on user demographics and trip behavior.

---

## 📈 Conclusions
- **Age Group:** Most bike-sharers are between **20–40 years old**.
- **Trip Duration vs Age:** Younger users take longer trips; trip duration is inversely proportional to user age.
- **Gender:** Males outnumber other genders in trip counts.
- **User Type:** Around **90% of participants are registered subscribers**.
- **Trip Duration Distribution:** Evenly and reasonably distributed from start to finish times.

---

## 🛠 Tools & Libraries
- **Python**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, Plotly (3D visualization)
- **Environment**: Jupyter Notebook

---

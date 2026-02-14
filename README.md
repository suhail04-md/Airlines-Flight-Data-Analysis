# ✈️ Airline Ticket Price Analysis

## 📊 Project Overview
This project performs Exploratory Data Analysis (EDA) on airline flight data to understand ticket pricing patterns and factors influencing airfare.

The objective is to analyze how different variables such as airline, route, class, duration, stops, and booking time impact ticket prices.

---

## 🎯 Project Goals

- Analyze ticket price variation with booking timing
- Compare pricing between Economy and Business classes
- Identify most expensive routes
- Study impact of stops and duration on price
- Understand airline pricing behavior
- Explore correlation between duration and ticket price

---

## 🛠️ Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📌 Key Analysis Questions

1. Which airline offers the cheapest average price?
2. How does ticket price vary with days left before departure?
3. Which routes are most expensive?
4. Is there a significant difference between Economy and Business class pricing?
5. Do non-stop flights cost more?
6. What is the correlation between flight duration and ticket price?

---

## 📈 Key Insights

✔ Ticket prices increase as departure date approaches  
✔ Business class tickets are significantly more expensive  
✔ Non-stop flights generally cost more  
✔ Some routes show high price fluctuation  
✔ Duration has a positive correlation with ticket price  

---

## 📊 Sample Visualization

Example: Duration vs Price (Correlation Analysis)

```python
sns.regplot(x="duration", y="price", data=df)
plt.show()

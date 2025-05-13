# 🧬 What Makes a Pokémon Strong?

This project explores the question: **what makes a Pokémon statistically strong?**  
Using the official Pokémon dataset, we analyze base stats, type influence, and legendary status to uncover patterns in how Pokémon strength is distributed across the franchise.

---

## 📊 Project Highlights

- 📈 **Base Stat Exploration** – Visualized the distribution and correlation of HP, Attack, Defense, etc.
- 🧠 **Type-Based Insights** – Identified which primary Pokémon types excel in each base stat
- 🌟 **Legendary Comparison** – Compared stat averages and resistance profiles between legendary and non-legendary Pokémon
- 💥 **Machine Learning Feature Importance** – Used Random Forest to rank which stats best predict if a Pokémon is legendary
- 🦾 **Proportional Stat Contribution** – Calculated how much each stat contributes to total strength on average

---

## 📁 Dataset

The dataset contains all core Pokémon up to Gen 7, including:
- Base stats (`hp`, `attack`, `defense`, etc.)
- Primary and secondary types
- `is_legendary` classification
- Type effectiveness vs. all types (`against_*` columns)

---

## 🛠 Tech Stack

- **Python** (Jupyter / Colab)
- **pandas** for data wrangling
- **seaborn** & **matplotlib** for visualization
- **scikit-learn** for machine learning models

---

## 📌 Key Insights

- 🐉 **Dragon** types dominate in average Attack and HP
- 🔋 **Flying** types lead in Speed
- 🧠 **Psychic** types excel in Special Attack
- 🛡️ **Steel** types are the most defensively durable
- 💡 Sp. Attack and Speed are the most predictive of being legendary

---

## 📈 Sample Visualizations

### 💪 Top 10 Strongest Pokémon by Base Total
![top10_base_total](https://github.com/user-attachments/assets/e12565c6-ef78-4e27-9396-7f214bced230)

### 🧬 Average Base Total by Pokémon Type
![avg_base_total_by_type](https://github.com/user-attachments/assets/f9cb2179-d52b-4ae8-9c43-08acd4e0e866)

### 🌟 Average Stats: Legendary vs Non-Legendary
![legendary_vs_nonlegendary](https://github.com/user-attachments/assets/321b259a-09d4-4826-a94b-a11c3bf5f225)

### 🌲 Feature Importance vs Correlation (Legendary Prediction)
![correlation_vs_rf_importance](https://github.com/user-attachments/assets/4edcc050-eb3a-4a90-bc3d-958e4ffc874d)

### ⚖️ Average Stat Contribution to Base Total
![avg_stat_contribution](https://github.com/user-attachments/assets/617e2052-262f-4d67-a4f4-b0e495087714)

---

## ▶️ How to Run

1. Clone the repo or open the notebook in Google Colab
2. Ensure `pokemon.csv` is in the same directory
3. Run all cells for full analysis and visualizations

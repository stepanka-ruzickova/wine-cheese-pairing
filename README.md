# 🧀🍷 Wine & Cheese Pairing

A data project that pairs wines with cheeses using simple logic, translations, and structured preprocessing.  
Created by two data enthusiasts on a journey from curiosity to visualization.

---

## 🧭 About the project

What cheese goes best with your favorite wine?  
This playful (yet technically involved) project explores taste matching through:

- multilingual datasets,
- translation mapping,
- and basic pairing logic.

The idea started as a fun exercise – and grew into a full data processing pipeline. 💡

📖 **Read our full story & method in the Medium article:**  
👉 [Pair it! Cheese & Wine Edition](https://medium.com/@stefandula2024/pair-it-cheese-wine-edition-4dc3d1f31913)

---

## 📚 Data sources

The datasets used in this project were obtained from public resources on [Kaggle](https://www.kaggle.com/).  
They include information about cheese characteristics and wine pairings, originally in multiple languages.

---

## 🧪 Our process (summary)

1. 🔎 Data cleaning & inspection  
   - Cheese data with features like texture, milk type, origin  
   - Wine & cheese pairings originally in Portuguese

2. 🌍 Translation & normalization  
   - Translated to English using ChatGPT and manual checks  
   - Standardized descriptors (e.g. "hard", "soft", "creamy")  

3. 🧠 Matching logic  
   - Merged datasets by cheese names and features  
   - Encoded attributes using `pandas.get_dummies()` for comparison

4. 📊 Visualization  
   - Matching score based on texture compatibility  
   - Output presented as a table + visual highlights (Tableau dashboard planned)

---

## ▶️ How to run it

1. Clone or download this repository  
2. Open `wine_cheese_pairing.ipynb` in Jupyter Notebook  
3. Make sure the `data/` folder is in the same directory  
4. Run all cells to explore the pairing results

---

## 📊 Example result

| 🍷 Wine           | 🧀 Suggested Cheese | ✅ Match % |
|------------------|---------------------|------------|
| Merlot           | Gouda               | 87%        |
| Chardonnay       | Brie                | 84%        |
| Sauvignon Blanc  | Goat Cheese         | 82%        |

---

## ✨ What we learned

- How to process multilingual datasets  
- How to structure a logic-based matching system  
- How to translate, clean, and standardize real-world food data  
- How to tell a data story from exploration to presentation

> _This project started with curiosity and turned into a lesson in cleaning, matching, and communicating through data._

---

## 👩‍💻 Authors

**Štěpánka Růžičková** & **Vendula Dvořáčková**  
Two data explorers who believe learning is better when it’s tasty.

---

🍷🧀 Cheers to good pairings – in data and in life!


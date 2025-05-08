# 🧠 Sentiment Analysis on the 2025 Revision of Indonesia’s TNI Law

This repository contains a data science project that analyzes **public sentiment** regarding the **2025 revision of the TNI Law (RUU TNI)**, based on Twitter data collected during the discussion and ratification period.

## 📌 Project Objective

To collect, clean, and analyze social media opinions related to the **Revisi Undang-Undang TNI (RUU TNI)**, with the goal of understanding public perception and identifying dominant narratives and keywords across sentiment categories (positive, neutral, negative).

---

## 🧩 Project Structure

| Module | Description |
|--------|-------------|
| 📰 `1. TWT Scraping Twitter/` | Twitter scraping using keyword-based queries |
| 🧼 `2. TWT Data Cleaning/` | Preprocessing and cleaning of raw tweet data |
| 📊 `3. TWT Analysis & Visualization/` | Exploratory analysis, sentiment breakdown, and visualization of top keywords |

---

## 📂 Data Sources

- **Primary**: Twitter (via scraping using relevant keywords such as `RUU TNI`, `dwifungsi`, `militer`, `sipil`, etc.)

---

## 📌 Context

The 2025 **Revisi UU TNI** was passed on March 20, 2025, triggering widespread public criticism due to its **closed and rushed process**, as well as perceived threats to civil liberties. Key revised articles include:

- **Pasal 3**: Administrative updates  
- **Pasal 7**: Expanded OMSP operations overseas & reduced DPR oversight  
- **Pasal 8**: Greater military involvement in civilian space  
- **Pasal 47**: More public positions open to active TNI officers  
- **Pasal 53**: Raised retirement age limits  

Revisions to **Articles 8 and 47** were heavily criticized for weakening civil supremacy.

---

## 📈 Key Findings

- **4472 tweets** were analyzed.
- **Sentiment distribution**:
  - 🔴 Negative: **75.8%**
  - ⚪ Neutral: **22.7%**
  - 🟢 Positive: **1.5%**

### Top Keywords per Sentiment:

- ✅ *Positive*: "TNI", "dwifungsi", "RUU", "sipil"
- ⚪ *Neutral*: "TNI", "dwifungsi", "baru", "jadi", "DPR", "demo"
- ❌ *Negative*: "Tolak", "RUU", "TNI", "Indonesia"

---

## 🛠️ Methods & Tools

- Python (Pandas, Sastrawi, Sklearn, Matplotlib, etc.)
- Sentiment analysis with lexicon-based or model-based approach
- Tokenization and keyword frequency extraction
- Data visualization

---

## 📅 Timeline

| Stage | Description | Status |
|-------|-------------|--------|
| Twitter Scraping | Collect tweets on RUU TNI | ✅ Done |
| Data Cleaning | Clean and preprocess tweets | ✅ Done |
| Sentiment Analysis | Classify tweets into sentiment categories | ✅ Done |
| Visualization | Generate insights and graphs | ✅ Done |
| Documentation | Create media & report assets | ✅ Done |

---

## 🤝 Contributors

- Farhan Adiwidya Pradana  
- Yusuf Imantaka Bastari  
- Muhammad Javier  
- Deira Aisya Rifani
- Danar Fathurahman

---

## 💬 Notes

This project is part of the **Gamadata-1 initiative** under **RISDAT BEM KM UGM**, aimed at using data science for social awareness and advocacy, particularly in supporting democratic oversight and civic participation in policymaking.

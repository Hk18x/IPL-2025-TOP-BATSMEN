# 📊 IPL 2025 - Phase-Wise Batting Impact Analysis

This repository contains Python code used to identify the **most impactful batsmen** across all three phases of IPL 2025 — **Powerplay**, **Middle Overs**, and **Death Overs** — using **custom-built metrics** that go beyond traditional stats like runs and strike rate.

## 🧠 Motivation

In T20 cricket, **context matters**. Scoring runs in the death overs against elite bowlers at a low-scoring venue is far more valuable than runs on a flat deck against average bowling. That's why we built **context-aware metrics** to uncover the **true impact** of batsmen across different match phases.

## 📌 What’s Inside?

- Cleaned ball-by-ball IPL 2025 dataset
- Custom code for:
  - Venue-wise average phase performance
  - Batsman performance at different venues
  - Impact vs top bowlers in each phase
  - Combined **Impact Scores** for Powerplay, Middle Overs, and Death Overs
- Final ranking of top batsmen in each phase based on:
  - 🟡 **Powerplay Mastery Index (PMI)**
  - 🔵 **Middle Overs Mastery Index (MMI)**
  - 🔴 **Death Overs Impact Index (DDI)**

## 🏆 Key Metrics Explained

Each metric uses a custom formula based on:
- **Run Volume**
- **Strike Rate**
- **Venue Difficulty**
- **Bowler Quality**

Runs are weighted higher in each phase (2× for Powerplay/Middle, 3× for Death) to reward sustained scoring ability alongside acceleration.

## 📈 Sample Output

- **Top 5 Powerplay Batsmen (PMI):** Jaiswal, Priyansh Arya, Kohli, Prabhsimran, Rahane
- **Top MMI and DDI performers** are also calculated and included in the code.

## 📖 Read Full Analysis

Dive deeper into the methodology and insights in the full Medium article:

🔗 **[Read on Medium → https://medium.com/@harshit18mishra/ipl-2025-season-xi-the-most-impactful-players-backed-by-data-6c257535511a ]**
*(Replace with actual Medium article URL)*

## 🛠️ Requirements

- Python 3.8+
- Pandas
- Numpy

Install dependencies using:
```bash
pip install -r requirements.txt

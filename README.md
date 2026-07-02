# ⚽ FIFA World Cup 2026 Winner Prediction 🏆

A Machine Learning project that predicts FIFA World Cup 2026 tournament outcomes using historical team performance data and Random Forest Classification.

---

## 📊 Model Performance (AUC-ROC Scores)

| Prediction Target | AUC Score | Rating |
|------------------|-----------|--------|
| 🏆 Winner | 84.5% | Excellent |
| 🥈 Finalist | 76.2% | Good |
| 🥉 Semi-Finalist | 81.3% | Very Good |
| 🎖️ Quarter-Finalist | 79.6% | Good |

> AUC score above 0.8 is considered very good in Machine Learning!

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data manipulation |
| NumPy | Numerical computation |
| Scikit-Learn | ML model building |
| Matplotlib | Data visualization |
| Seaborn | Statistical plots |

---

## 📁 Project Structure

```
FIFA-WC-2026-Prediction/
│
├── FIFA_World_Cup_2026_prediction.ipynb  # Main notebook
├── train.csv                              # Training dataset
├── test.csv                               # Test dataset
├── wc2026_predictions.csv                 # Final predictions
└── README.md                              # Project documentation
```

---

## 🔧 Key Steps

### 1. Data Preprocessing
- Cleaned and handled missing values
- Encoded categorical variables
- Normalized numerical features

### 2. Feature Engineering
- Team rankings and FIFA points
- Goal differentials
- Head-to-head historical statistics
- Win/Draw/Loss ratios

### 3. Model Building
- Algorithm: **Random Forest Classifier**
- Handled class imbalance using `class_weight='balanced'`
- Tuned hyperparameters: `n_estimators=300`, `max_depth=4`

### 4. Model Validation
- Used **5-Fold Cross Validation**
- Evaluated using **AUC-ROC Score**
- Trained separate models for each tournament stage

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/omkarpatilop-123/Football-WC-2026-Prediction

# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn

# Open the notebook
jupyter notebook FIFA_World_Cup_2026_prediction.ipynb
```

---

## 💡 Key Learnings

- Class imbalance handling significantly improves prediction for rare outcomes like tournament winners
- Cross validation gives more reliable performance estimate than simple train/test split
- AUC-ROC is better than accuracy for imbalanced sports datasets

---

## 👤 Author

**Omkar Patil**
- GitHub: https://github.com/OmkarPatilML
- LinkedIn: linkedin.com/in/omkarpatilml

---

## 📄 License

This project is licensed under the MIT License.

---

⭐ If you found this project helpful, please give it a star!

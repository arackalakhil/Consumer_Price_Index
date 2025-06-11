# Consumer Price Index (CPI) Prediction

Analyze and predict CPI values using Python and machine learning

## 📌 Project Overview
The goal of this project is to analyze trends in the All India Consumer Price Index and build a predictive model using Linear Regression.

## 📊 Dataset
**File:** `All India Consumer Price Index (RuralUrban) upto March 2023.csv`  
Monthly CPI data for multiple item categories and sectors.

## ⚙️ Installation
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
🚀 Usage
Clone the repo

Add the dataset in the notebook folder

Open consumer_price_predicition.ipynb

Run the cells in order

🔬 Methodology
Data Cleaning
Dropped Housing column (too many nulls)

Fixed month typo: “Marcrh” → “March”

Removed outliers from several columns

EDA
Yearly general index trend

Category-wise comparisons

Monthly vegetable price variation

Rural vs. Urban comparisons

ML Model
Linear Regression

StandardScaler for normalization

Train/Test split

Evaluated with R², MAE, MSE

📈 Results
Clear upward CPI trend

Seasonal spike in vegetables

Satisfactory model fit in actual vs. predicted plot

🤝 Contributing
Feel free to fork and submit a pull request.

📄 License
Licensed under the MIT License.

Paste that into your `README.md`, and it will look clean and professional on GitHub.

---

#### ✅ Option 2: Create a separate `index.html` for GitHub Pages

1. Create a file called `index.html`.
2. Paste the **full HTML code** (with `<html>`, `<head>`, `<style>`, `<body>`, etc.)
3. Push to your repo.
4. Enable GitHub Pages:
   - Go to **Settings → Pages**
   - Select source: `main` branch
   - Choose `/root` folder
   - Save
5. Visit the link GitHub gives you (e.g. `https://yourname.github.io/repo-name`)

This will show your styled version like a proper webpage.

---

Would you like both a `.md` and `.html` version ready to copy-paste?

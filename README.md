# Diamond Price Analysis using PCA

## 📌 Project Overview
This project analyzes a dataset of nearly 54,000 round-cut diamonds to explore the key factors influencing their prices. Using statistical methods and Principal Component Analysis (PCA), we reduce dimensionality and identify significant trends in the data.

## 📂 Dataset Description
The dataset contains the following variables:

- **carat**: Weight of the diamond in carats.
- **cut**: Quality of the cut (Fair, Good, Very Good, Premium, Ideal).
- **color**: Diamond color, ranging from D (best) to J (worst).
- **clarity**: Purity of the diamond (I1 to IF).
- **depth**: Total depth percentage.
- **table**: Width of the top table relative to the widest point.
- **price**: Price of the diamond in USD.
- **x, y, z**: Dimensions of the diamond (length, width, depth).

## 🔍 Key Analyses
1. **Price Distribution Analysis**: Examining how diamond prices are distributed.
2. **Correlation Matrix**: Identifying relationships between numerical variables.
3. **Boxplots for Categorical Variables**: Exploring price variations based on cut, color, and clarity.
4. **Scatter Plots**: Visualizing how price is influenced by multiple variables.
5. **Principal Component Analysis (PCA)**: Reducing dimensionality while retaining key information.

## 📊 Findings
- **Carat is the strongest predictor of price.**
- **A strong correlation exists between carat and dimensions (x, y, z).**
- **PCA shows that the first two components explain ~86% of variance.**
- **Some anomalies, such as diamonds with zero dimensions, were identified and removed.**
- **Cut, clarity, and color influence price, but their effect is more apparent when analyzed with carat.**

## ⚙️ Requirements
To run the analysis, install the necessary dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 📜 Usage
Run the Jupyter Notebook to explore the dataset and visualizations:

```bash
jupyter notebook TP_ANAD_git.ipynb
```

## 📌 Authors
- **Benameur Tarek**
- **Touil Nihel**

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
```
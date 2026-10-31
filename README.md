# 🛒 Online Retail BI

📊 Analyse Business Intelligence du dataset **Online Retail** : les transactions d'un détaillant en ligne britannique entre décembre 2010 et décembre 2011.

## 🎯 Objectif

Explorer et analyser les ventes pour en tirer des indicateurs utiles à la prise de décision : chiffre d'affaires, produits, clients et pays.

## 📦 Dataset

- 🌐 **Source** : [UCI Machine Learning Repository, Online Retail](https://archive.ics.uci.edu/dataset/352/online+retail)
- 📄 **Fichier** : `data/Online Retail.xlsx`
- 🔢 **Taille** : environ 540 000 lignes
- 🧾 **Colonnes** : InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

## 📁 Contenu du dépôt

```
Online-Retail-BI/
├── 📂 data/
│   └── 📊 Online Retail.xlsx
├── 📂 notebooks/
│   ├── 📓 l1-bi-tp1.ipynb       # TP1 : (exploration de la dataset et identification des questions décisionnels)
│   └── 📓 l2-bi-tp2.ipynb   # TP2 : (préparation de la qualité des données de la source)
└── 📝 README.md
```

## 🔍 Analyses réalisées

- 🧹 Nettoyage des données (valeurs manquantes, doublons, retours)
- 🌍 Chiffre d'affaires par pays et par mois
- 🏆 Top produits les plus vendus
- 👥 Comparaisons entre périodes ou segments de clients

## 👀 Visualiser les notebooks

- 📓 [TP1 sur nbviewer](https://nbviewer.org/github/TON_PSEUDO/Online-Retail-BI/blob/main/notebooks/l1-bi-tp1.ipynb)
- 📓 [TP2 sur nbviewer](https://nbviewer.org/github/TON_PSEUDO/Online-Retail-BI/blob/main/notebooks/l2-bi-tp2%20(1).ipynb)

## 🚀 Lancer le projet

1. 📥 Cloner le dépôt :
   ```
   git clone https://github.com/TON_PSEUDO/Online-Retail-BI.git
   ```
2. 📦 Installer les bibliothèques :
   ```
   pip install pandas matplotlib seaborn openpyxl jupyter
   ```
3. ▶️ Ouvrir les notebooks avec Jupyter :
   ```
   jupyter notebook
   ```

## 🛠️ Outils

🐍 Python · 🐼 Pandas · 📈 Matplotlib · 🎨 Seaborn · 📓 Jupyter

## 👩‍💻 Auteur

**Amako** · 🎓 (Master artificial intelligence applied /ENSA Berrchid)

---

⭐ N'hésite pas à laisser une étoile si ce projet t'a plu !

# Analýza závažnosti priebehu COVID-19 pomocou dátovej analytiky

Tento repozitár obsahuje podklady k bakalárskej práci zameranej na predikciu závažnosti priebehu
ochorenia COVID-19 pomocou dátovej analytiky a strojového učenia. Dátová analýza bola realizovaná na reálnych údajoch 
pacientov z Univerzitnej nemocnice v Košiciach počas štyroch vĺn pandémie.

## Štruktúra repozitára

### Dáta
- `1. vlna všetko 28-11-2024.xlsx`
- `2. vlna všetko 28-11-2024.xlsx`
- `3. vlna všetko 28-11-2024.xlsx`
- `4. vlna všetko 28-11-2024.xlsx`
- `wave1_imputed.xlsx` až `wave4_imputed.xlsx` – očistené a doplnené datasety pripravené na modelovanie

### Notebooky
- `Priprava_dat.ipynb` – predspracovanie a imputácia chýbajúcich dát
- `Bakalárka_pocty.ipynb` – analýza počtov a vizualizácie demografických údajov
- `LOGREG.ipynb`, `RANFOR.ipynb`, `SVM.ipynb`, `KNN.ipynb`, `XGBOOst.ipynb` – implementácia a vyhodnotenie jednotlivých modelov strojového učenia

### Výsledky
- `results_*.csv` – výsledky klasifikačných metrík pre každý model
- `conf_matrix_*.png` – confusion matrix vizualizácie
- `roc_curve_*.png` – ROC krivky pre každý model a vlnu

## Použité algoritmy
- Logistická regresia (LR)
- Random Forest (RF)
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- XGBoost (XGB)

## Cieľ
Cieľom projektu je využiť historické laboratórne, demografické a biochemické údaje
na predikciu závažnosti priebehu COVID-19 pomocou rôznych modelov strojového učenia a porovnať ich výkonnosť.

## Prostredie
Projekt bol vyvíjaný v prostredí Jupyter Notebook (Python 3.x). Požadované knižnice:
- pandas, numpy, matplotlib, seaborn
- scikit-learn, xgboost
- imblearn (voliteľne)

## Autor
Jakub Fazekaš – bakalárska práca, FEI TUKE (2025)



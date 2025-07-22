# 💼 Berka Bank Dataset Analysis

## 📊 Objectif du projet

Ce projet a pour but d’explorer et d’analyser les données bancaires issues de la base **Berka Bank**, un dataset public utilisé pour des projets de Data Science et d’analyse financière. L’objectif principal est de comprendre les comportements des clients, segmenter les profils, analyser le risque de crédit et créer un pipeline analytique prêt pour des dashboards (Power BI, Python, SQL).

---

## 📁 Contenu du dataset

Le jeu de données est divisé en plusieurs fichiers `.csv`, chacun représentant une entité bancaire :

| Fichier      | Description |
|--------------|-------------|
| `account.csv` | Informations sur les comptes bancaires (fréquence, date d’ouverture, district) |
| `client.csv`  | Informations personnelles sur les clients (ID, date de naissance, district) |
| `card.csv`    | Cartes bancaires associées à un compte (type, date d’émission) |
| `district.csv`| Statistiques socio-économiques par région (revenu, chômage, criminalité…) |
| `disp.csv`    | Rôle d’un client sur un compte (titulaire ou procuration) |
| `loan.csv`    | Détails des prêts (montant, durée, statut de remboursement) |
| `order.csv`   | Ordres de paiement émis (banque destinataire, montant, symbole de paiement) |
| `trans.csv`   | transactions (banque destinataire, montant, symbole de paiement) |

---

## 🧠 Analyse réalisée

- Étude exploratoire des données (EDA) sous **Python** :
  - Nettoyage des données (dates, doublons, valeurs manquantes)
  - Segmentation des clients par âge, rôle, région
  - Analyse des prêts (montants, retards, défauts)
  - Corrélations entre variables socio-économiques et défauts de paiement

- Intégration Power BI :
  - Dashboard interactif avec KPI :
    - Taux de défauts
    - Répartition des prêts par région et âge
    - Montant moyen des prêts
    - Répartition des types de cartes
    - Score risque client

---

## 🛠️ Technologies utilisées

- `Python` : pandas, seaborn, matplotlib, plotly
- `Power BI` : Modèle relationnel, DAX, dashboards dynamiques
- `SQL` : Jointures, agrégats, segmentation clients
- `Jupyter Notebook` : pour EDA et pipeline analytique

---

## 📌 Objectifs métiers

- ⚠️ Détection des clients à risque
- 💰 Suivi des remboursements et impayés
- 👥 Segmentation marketing client
- 🧭 Analyse socio-géographique par district
- 🏦 Visualisation dynamique pour le pilotage financier

---

## 📂 Structure du projet
berka-bank-analysis/
│
├── data/
│ ├── account.csv
│ ├── client.csv
│ ├── card.csv
│ ├── district.csv
│ ├── disp.csv
│ ├── loan.csv
│ └── order.csv
│ └── trans.csv
|
├── notebooks/
│ └── 0.Final_the_berka_bank_20_06.ipynb
│
├── powerbi/
│ └── the_berka_bank_PBI_DB25_2025_.pbix




---

## 🔗 Prochaines étapes

- Implémenter un modèle de classification pour prédire les défauts de prêts 
- Créer un scoring client basé sur les données disponibles
- Déployer une version interactive sur  `Power BI`

---

## 🧑‍💻 Auteur

Hamza Guizani  
📍 Data Analyst 
guizanihamza44@gmail.com 
https://www.linkedin.com/in/hamza-guizani/ 
https://www.malt.fr/profile/hamzaguizani

---

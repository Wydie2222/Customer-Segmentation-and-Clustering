# Clustering de Clients - Wholesale Customers Dataset

## 📌 Description du Projet

Ce projet vise à analyser et segmenter les clients d'un distributeur en gros à l'aide de techniques de Machine Learning. Nous utilisons une analyse exploratoire des données, une Analyse en Composantes Principales (ACP) et un clustering K-Means.

## 💊 Données Utilisées

Le dataset **Wholesale Customers** contient des informations sur 440 clients, incluant leurs dépenses annuelles dans différentes catégories de produits.  

### 📌 Caractéristiques des Données :
- **Nombre d'observations :** 440 clients  
- **Nombre de variables :** 7  
- **Types de variables :** Entiers et catégoriques  
- **Colonnes principales :**  
  - **Channel** : Type de client (HoReCa, Retail)  
  - **Region** : Localisation du client (Lisbonne, Porto, Autres)  
  - **Fresh, Milk, Grocery, Frozen, Detergents_Paper, Delicatessen** : Montants annuels de dépenses  

## 🛠️ Technologies utilisées

- **Python**
- **Pandas, NumPy** (Manipulation des données)
- **Matplotlib, Seaborn** (Visualisation)
- **Scikit-learn** (ACP, Standardisation, K-Means)
- **Yellowbrick** (Visualisation du K-Elbow)

## 🚀 Étapes du projet

1. **Analyse exploratoire des données**
   - Chargement et nettoyage des données
   - Visualisation des distributions et des corrélations
2. **Analyse en Composantes Principales (ACP)**
   - ACP linéaire et non linéaire (Kernel PCA)
3. **Clustering des clients avec K-Means**
   - Standardisation des données
   - Détermination du nombre optimal de clusters avec la méthode du coude (Elbow Method)
   - Segmentation des clients en groupes

## 📂 Structure du projet

```
💃 Clustering_Project
️└️ 📄 Clustering.ipynb      # Notebook Jupyter avec le code et l'analyse
️└️ 📄 README.md             # Documentation du projet
️└️ 👉 Wholesale customers data.csv  # Jeu de données utilisé

```

## 🔧 Comment exécuter le projet ?

1. **Cloner le projet :**  
   ```bash
   git clone https://github.com/user/Customer-Segmentation-and-Clustering.git

3. **Exécuter le notebook dans Jupyter :**  
   ```bash
   jupyter notebook Clustering.ipynb
   ```

## 📌 Résultats attendus

- Segmentation des clients en différents groupes selon leurs habitudes d’achat.
- Visualisation des clusters obtenus avec ACP et K-Means.
- Identification des principales caractéristiques de chaque groupe de clients.

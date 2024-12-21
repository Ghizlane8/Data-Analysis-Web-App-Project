# 📊 **Data Analysis Web App Project**

Bienvenue dans ce projet de Web App interactif dédié à l'analyse de données, construit avec **Streamlit**. Cette application vise à simplifier l'exploration, la visualisation et l'analyse statistique des données, tout en offrant une expérience utilisateur fluide et intuitive.

---

## 🎯 **Objectifs du Projet**

1. **Automatiser l'analyse des données** : Offrir des outils interactifs pour charger, nettoyer, et explorer les jeux de données.
2. **Simplifier les visualisations** : Générer des graphiques interactifs adaptés aux données analysées.
3. **Faciliter les tests statistiques** : Fournir des outils statistiques essentiels (t-tests, ANOVA, régressions, etc.) directement intégrés dans l'application.

---

## 🛠️ **Fonctionnalités Clés**

### 📂 **Chargement des Données**
- **Support de plusieurs formats** :
  - CSV, Excel (.xls, .xlsx), TXT.
- **Deux méthodes de chargement** :
  - Upload de fichiers locaux.
  - Téléchargement à partir d’un lien externe.
- **Options avancées** :
  - Sélection de feuilles spécifiques dans les fichiers Excel.
  - Gestion des erreurs pour les formats non pris en charge ou fichiers vides.

### 🧹 **Nettoyage et Manipulation des Données**
- Affichage des statistiques descriptives (moyenne, médiane, écart-type, etc.).
- Gestion des valeurs manquantes (affichage et suppression).
- Sélection dynamique des colonnes ou lignes spécifiques.
- Calculs avancés :
  - Valeurs uniques.
  - Fréquence des catégories.
  - Opérations globales comme la somme, le maximum et le minimum.

### 📊 **Visualisations Dynamiques**
- Graphiques interactifs pris en charge :
  - **Line Plot** : Courbes temporelles ou relationnelles.
  - **Scatter Plot** : Analyse des relations entre deux variables.
  - **Box Plot** : Distribution et détection des valeurs aberrantes.
  - **Histogrammes** : Distribution des fréquences.
  - **Heatmaps** : Cartes de corrélation.
  - **Violin Plots** : Distribution avec densité.
  - **Pie Charts** : Répartition des catégories.
  - **Pair Plots** : Matrices de dispersion pour plusieurs variables.
- Génération de **KDE (Kernel Density Estimation)** pour identifier les distributions des données.

### 🧮 **Tests Statistiques**
1. **T-Test** :
   - Comparaison entre deux groupes indépendants.
2. **Z-Test** :
   - Analyse à un ou deux échantillons.
3. **Test du Khi-2** :
   - Relation entre deux variables catégoriques.
4. **ANOVA** :
   - Comparaison des moyennes entre plusieurs groupes (unidirectionnelle ou bidirectionnelle).
5. **Régression linéaire** :
   - Analyse de la relation entre deux variables quantitatives.

### 📈 **Analyse Statistique Avancée**
- Calcul des statistiques :
  - Moyenne, médiane, variance, écart-type, IQR.
  - Cumulatif (somme, produit).
  - Corrélations et covariances.
  - Skewness (asymétrie) et kurtosis (aplatissement).
- Détection des types de distributions :
  - Normale, exponentielle, uniforme, binomiale, etc.

---

## 🗂️ **Structure des Fichiers**

- **`app.py`** :
  - Script principal contenant toute la logique de l'application.
- **`README.md`** :
  - Ce fichier explicatif.
- **`data/`** :
  - Répertoire optionnel pour stocker des exemples de fichiers de données.
- **`requirements.txt`** :
  - Liste des bibliothèques Python nécessaires à l'exécution.

---

## 🔍 **Cas d’Utilisation**
1. **Exploration Initiale des Données**
  - Chargez des fichiers CSV ou Excel.
  - Analysez les statistiques descriptives pour une vue d’ensemble rapide.
2. **Visualisation Dynamique**
  - Explorez la répartition des variables avec des graphiques interactifs.
  - Analysez les corrélations grâce à des heatmaps.
3. **Nettoyage des Données**
  - Identifiez et gérez les valeurs manquantes ou aberrantes.
  - Simplifiez vos données en supprimant les colonnes inutiles.
4. **Tests Statistiques**
  - Comparez les moyennes de groupes avec des tests T ou ANOVA.
  - Évaluez la relation entre variables catégoriques avec le test du Khi-2.
  - Modélisez vos données grâce à des régressions linéaires.

---

## 👩‍💻 Auteurs
- Baali Ghizlane
- Imane Taghzout

## 💻 **Installation et Exécution**

### 🔧 **Prérequis**
- **Python 3.8 ou supérieur**.
- Bibliothèques nécessaires (installées via `pip`) :
  ```bash
  pip install streamlit pandas numpy matplotlib plotly seaborn statsmodels scipy

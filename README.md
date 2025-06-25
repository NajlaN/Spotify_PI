# 🎧 Projet BI & IA – Analyse des tendances musicales Spotify

Ce projet de Business Intelligence, réalisé dans le cadre du Master 1 Business Analytics (2024-2025), vise à analyser les tendances musicales issues de données Spotify, puis à les valoriser à travers des visualisations interactives et une application web de recommandation personnalisée.

## 🚀 Objectifs du projet

- Identifier les tendances musicales (par genre, tempo, popularité…)
- Comprendre les corrélations entre caractéristiques audio et succès commercial
- Construire une base de données relationnelle optimisée pour l’analyse musicale
- Développer un tableau de bord Power BI dynamique
- Créer une application web de recommandation musicale

---

## 📚 Méthodologie : CRISP-DM

Le projet suit les étapes de la méthodologie CRISP-DM :

1. **Compréhension métier** : Identifier les besoins des utilisateurs (labels, artistes, plateformes)
2. **Compréhension des données** : Analyse exploratoire des données Spotify et Kaggle
3. **Préparation des données** : Nettoyage, normalisation, structuration PostgreSQL
4. **Modélisation** : Corrélations, KPIs, modèle KNN pour la recommandation
5. **Évaluation** : Interprétation des résultats métier
6. **Déploiement** : Tableau de bord Power BI et site web interactif

---

## 🧠 Données utilisées

- **API Spotify (Spotipy)** : Caractéristiques audio (tempo, loudness, energy, danceability, popularity…)
- **Kaggle** : Données historiques et genres complémentaires
- **Base PostgreSQL** : Modélisation en schéma en constellation

---

## 📈 Indicateurs clés (KPI)

- 📊 **Loudness** : Volume sonore moyen des chansons dans le temps
- 🎼 **Genres émergents** : Nouveaux styles gagnant en popularité
- 💃 **Danceability & Popularité** : Les morceaux dansants sont-ils les plus populaires ?
- ⏱ **Évolution du tempo** : Les rythmes accélèrent-ils pour séduire ?

---

## 🔍 Résultats analytiques

- **Corrélation forte** entre énergie et volume sonore
- **Popularité négative** des morceaux très acoustiques
- **Genres dominants** : pop, dance, hip hop
- **Tendance au raccourcissement** des chansons depuis 2015

---

## 📊 Dashboards Power BI

Trois tableaux de bord interactifs ont été développés pour visualiser les résultats :

> ![Dashboard Spotify](https://github.com/NajlaN/Spotify_PI/blob/main/dashboard.png?raw=true)

---

## 🌐 Application Web interactive

Développée avec **Flask**, **HTML/CSS/JS**, l'application propose :

- Recommandation de chansons similaires
- Génération de playlists selon l’humeur (party, chill…)
- Comparaison visuelle de morceaux (radar chart)
- Exploration par année ou artiste
- Expérience responsive, simple et moderne

### 🛠 Architecture technique

- **Backend** : Flask + PostgreSQL + modèle KNN
- **Frontend** : HTML/CSS + JS + Chart.js
- **API REST** : Communication fluide entre les couches

---

## 📁 Structure du dépôt

```bash
📦 Spotify_PI
 ┣ 📊 data/
 ┣ 📁 notebooks/
 ┣ 📁 dashboard.png
 ┣ 📄 app.py
 ┣ 📄 requirements.txt
 ┣ 📄 README.md
 ┗ 📁 templates/

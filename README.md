

# Impact des Investissements Sportifs et Culturels sur le Développement Socio-économique en Europe (2015–2021)

**Auteur** : Joel Mintchi  
**Technologies** : Python, Jupyter Notebook, Power BI, DAX  
**Période étudiée** : 2015–2021  
**Pays couverts** : 19 pays européens  
**Objectif** : Évaluer l’impact des dépenses publiques en culture et sport sur le bien-être socio-économique des jeunes

---

## 🧩 Contexte

Ce projet s’inscrit dans une démarche analytique complète en trois étapes :  
1. **Collecte & préparation des données**  
2. **Exploration & analyse statistique**  
3. **Visualisation & production d’insights décisionnels**

Il mobilise des sources internationales, des techniques de traitement de données avancées et une narration visuelle rigoureuse pour éclairer les politiques publiques européennes.

---

## 📁 Structure du dépôt

```
CultureSportImpactEU/
├── data/                      # Données brutes et nettoyées
│   ├── raw/                  # Sources originales
│   └── processed/            # Dataset consolidé
├── notebooks/                # Scripts Python
│   ├── 01_collecte.ipynb     # Tâche 1 : collecte & nettoyage
│   └── 02_analyse.ipynb      # Tâche 2 : exploration & indicateurs
├── dashboard/                # Fichier Power BI (.pbix)
├── docs/                     # Rapport, annexes, documentation
│   └── rapport_synthese.pdf
├── README.md
├── LICENSE
└── .gitignore
```

---

## 🧪 Tâche 1 : Collecte & Préparation des Données

### 🎯 Objectif
Consolider un dataset multi-sources prêt à l’analyse.

### 🔍 Méthodologie
- Identification de sources variées : bases internationales, open data, rapports publics
- Collecte via téléchargement, scraping, API
- Harmonisation des formats : unités, périodes, géographies
- Fusion des jeux de données dans un fichier unique

### 📚 Exemples de sources utilisées
- **Démographiques** : [WorldPop](https://hub.worldpop.org), [UN Population](https://population.un.org/wpp)
- **Économiques** : [IMF](https://data.imf.org), [OECD](https://www.oecd.org/en/data.html)
- **Sociales** : [WHO](https://www.who.int/data/gho), [UNDP](https://hdr.undp.org/data-center)
- **Culture/Sport** : Eurostat COFOG, FIFA Rankings

---

## 📊 Tâche 2 : Exploration & Analyse

### 🎯 Objectif
Transformer les données consolidées en support analytique riche et pertinent.

### 🔍 Méthodologie
- Analyse descriptive : tendances historiques et spatiales
- Création d’indicateurs dérivés :
  - Taux de croissance annuelle
  - Ratio population jeune
  - Indices composites : Wellbeing Index, Sport Culture Index
- Détection d’anomalies : pays sous-performants malgré investissements élevés
- Agrégations spatiales (Est/Ouest, régions) et normalisation par habitant

### 📁 Livrables
- Dataset enrichi (`processed/enriched_dataset.csv`)
- Notebook d’analyse (`notebooks/02_analyse.ipynb`)
- Documentation des choix méthodologiques (`docs/anomalies_methodo.md`)

---

## 📈 Tâche 3 : Visualisation & Insights avec Power BI

### 🎯 Objectif
Créer un tableau de bord interactif permettant aux décideurs d’identifier des leviers d’action.

### 🧠 Contenu du Dashboard
- **Page 1** : Vue d’ensemble (KPI, carte choroplèthe, top/bottom pays)
- **Page 2** : Évolution temporelle (aires empilées, cartes de croissance)
- **Page 3** : Analyse comparative (scatter animé, radar chart, barres normalisées)
- **Page 4** : Insights & Actions (table anomalies, cascade, corrélations)

### 🧪 Fonctionnalités interactives
- Filtres dynamiques : années, régions, secteurs
- Segments visuels : typologie des pays (leaders, efficients, critiques)
- Narration visuelle : chaque graphique répond à une question stratégique

### 📁 Livrables
- Fichier Power BI : `dashboard/CultureSportImpactEU.pbix`
- Rapport synthèse : `docs/rapport_synthese.pdf`

---

## 📬 Contact

**Joel Mintchi**  
📧 Mintchijo@email.com  
📍 Cotonou, Bénin


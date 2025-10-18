 **Impact des Investissements Sportifs et Culturels sur le Développement Socio-économique en Europe (2015–2021)**.

---

# 🇪🇺 Impact des Investissements Sportifs et Culturels sur le Développement Socio-économique en Europe (2015–2021)

**Auteur** : Joel Mintchi  
**Outils** : Python, Power BI, DAX, Jupyter Notebook  
**Périmètre** : 19 pays européens | 7 années | 20 indicateurs socio-économiques

---

## 🧩 Contexte du Projet

Ce projet vise à analyser l’impact des investissements publics en culture et sport sur le bien-être socio-économique des jeunes en Europe. Il s’inscrit dans une démarche complète en trois étapes : collecte des données, analyse exploratoire, et visualisation décisionnelle.

---

## 📌 Tâche 1 : Collecte & Préparation des Données

### 🎯 Objectif
Consolider un dataset multi-sources prêt à l’analyse, en combinant données démographiques, économiques, sociales et culturelles.

### 🔍 Méthodologie
- Identification de sources fiables : Eurostat, OCDE, PNUD, FIFA, WHO, World Bank
- Collecte via API, scraping et téléchargement manuel
- Nettoyage : harmonisation des unités, périodes, formats géographiques
- Fusion des jeux de données dans un dataset final structuré

### 📁 Livrables
- `notebooks/collecte_preparation.ipynb` : Notebook de collecte et nettoyage
- `data/raw/` : Données brutes
- `data/processed/final_dataset.csv` : Dataset consolidé prêt à l’analyse

---

## 📊 Tâche 2 : Exploration & Analyse

### 🎯 Objectif
Transformer le dataset en support analytique riche, révélant tendances, corrélations et anomalies.

### 🔍 Méthodologie
- Analyse descriptive : évolution du PIB, IDH, chômage, investissements
- Agrégations spatiales (Est/Ouest, pays) et temporelles (pré/post COVID)
- Création d’indicateurs dérivés :
  - Efficience culturelle = Wellbeing / (Investissement/100)
  - Indices composites : Sport Culture Index, Youth Wellbeing Index
- Détection d’anomalies : pays sous-performants malgré investissements élevés

### 📁 Livrables
- `notebooks/analyse_exploratoire.ipynb`
- `data/enriched/enriched_dataset.csv`
- `docs/anomalies_methodo.md` : Documentation des anomalies et choix méthodologiques

---

## 📈 Tâche 3 : Visualisation & Insights avec Power BI

### 🎯 Objectif
Créer un tableau de bord interactif permettant aux décideurs d’identifier des leviers d’action.

### 🧠 Structure du Dashboard
- **Page 1** : Vue d’ensemble (KPI, carte choroplèthe, top/bottom pays)
- **Page 2** : Évolution temporelle (aires empilées, cartes de croissance)
- **Page 3** : Analyse comparative (scatter animé, radar chart, barres normalisées)
- **Page 4** : Insights & Actions (table anomalies, cascade, corrélations)

### 🧪 Innovations
- Mesures DAX personnalisées (`[Statut_Anomalie]`)
- Zone d’insights automatiques selon filtres
- Narration visuelle cohérente (data storytelling)

### 📁 Livrables
- `dashboard/CultureSportImpactEU.pbix`
- `docs/rapport_synthese.pdf`

---

## 📚 Sources de Données

| Domaine       | Exemples de Sources |
|---------------|---------------------|
| Démographiques | [WorldPop](https://hub.worldpop.org), [UN Population](https://population.un.org/wpp) |
| Économiques    | [IMF](https://data.imf.org), [OECD](https://www.oecd.org/en/data.html) |
| Sociales       | [WHO](https://www.who.int/data/gho), [UNDP](https://hdr.undp.org/data-center) |
| Culture/Sport  | [Eurostat COFOG](https://ec.europa.eu/eurostat), [FIFA Rankings](https://www.fifa.com) |

---

## 🧠 Recommandations & Perspectives

- Création d’un **Fonds de Cohésion Culturelle** ciblé pour les pays critiques
- Développement d’une **plateforme de benchmark culturel** européenne
- Réorientation des budgets vers le **sport de masse**
- Documentation des modèles vertueux (Irlande, Pays-Bas)
- Intégration de variables médiatrices (éducation, capital social, urbanisation)

---

## 📬 Contact

**Joel Mintchi**  
📧 mintchijo@email.com  
📍 Cotonou, Bénin

---

Souhaites-tu que je t’aide à rédiger ton `.gitignore`, ton fichier `LICENSE`, ou à structurer les sous-dossiers de ton dépôt ? Je peux aussi t’aider à publier ton notebook ou ton fichier `.pbix` proprement.

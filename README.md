# hackathon-wdl-cote-divoire

# Vulnérabilité du marché du travail des jeunes en Côte d’Ivoire (2015–2025)

## Présentation du projet

Ce projet analyse la vulnérabilité des jeunes sur le marché du travail en Côte d’Ivoire, définie comme la combinaison du chômage et de l’inactivité chez les individus âgés de 15 à 35 ans.

L’objectif est de comprendre les facteurs structurels d’exclusion et de simuler des trajectoires futures selon différents scénarios de politiques publiques à l’horizon 2035.

---

## Question de recherche

Pourquoi la croissance économique en Côte d’Ivoire ne se traduit-elle pas par une inclusion effective des jeunes sur le marché du travail, et quelles réformes structurelles permettraient d’inverser cette tendance d’ici 2035 ?

---

## Description des données

- Source : OIT / BIT (2015–2025)
- Population : jeunes âgés de 15 à 35 ans
- Observations : indicateurs nationaux agrégés
- Variables principales :
  - taux de chômage
  - taux d’inactivité
  - niveau d’éducation
  - genre
  - secteur d’emploi

---

## Méthodologie

### 1. Analyse exploratoire des données (EDA)
- Distribution du chômage et de l’inactivité
- Disparités entre hommes et femmes
- Relation entre éducation et vulnérabilité
- Concentration sectorielle de l’emploi

### 2. Interprétation structurelle
- Identification des mécanismes systémiques :
  - dualité du marché du travail (formel vs informel)
  - mécanismes d’exclusion liés au genre
  - inadéquation entre formation et emploi

### 3. Modélisation de scénarios (2025–2035)

Trois trajectoires ont été simulées :

- Scénario 1 : inertie structurelle
- Scénario 2 : réformes partielles
- Scénario 3 : transformation structurelle

Chaque scénario repose sur des hypothèses différentes de réduction annuelle de la vulnérabilité des jeunes.

---

## Principaux insights

### Insight 1 — Paradoxe de l’éducation
Un niveau d’éducation élevé est associé à une vulnérabilité plus forte, en raison d’un décalage structurel entre les diplômés et la capacité de création d’emplois formels.

### Insight 2 — Écart de genre
Les femmes présentent systématiquement des taux d’inactivité plus élevés que les hommes à tous les niveaux d’éducation, en raison des contraintes liées à l’économie du care et des barrières sur le marché du travail.

### Insight 3 — Piège de l’informalité
Environ 68 % de l’emploi des jeunes est concentré dans l’agriculture et le commerce informel, ce qui limite la productivité et la mobilité sociale.

---

## Résultats des scénarios (projection 2035)

| Scénario | Vulnérabilité (2035) | Réduction |
|----------|---------------------|----------|
| Inertie | ~0,457 | ~4,9 % |
| Réformes partielles | ~0,413 | ~14,0 % |
| Transformation structurelle | ~0,354 | ~26,3 % |

---

## Message final

Sans transformation structurelle du marché du travail, la Côte d’Ivoire risque de transformer son dividende démographique en vulnérabilité structurelle de long terme.

---

## Implications politiques

### Court terme
- Programmes d’emploi des jeunes dans le secteur formel
- Subventions ciblées à l’embauche
- Politiques d’inclusion des femmes

### Moyen terme
- Diversification industrielle (agro-industrie, manufacturing)
- Réforme de l’adéquation formation-emploi
- Incitations à la formalisation des PME

### Long terme
- Transformation structurelle de l’économie
- Expansion de l’emploi formel productif
- Inclusion complète des femmes dans le marché du travail

---

## Outils et bibliothèques

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (régression linéaire)
- Jupyter Notebook

---

## Limites

- Données agrégées au niveau national
- Absence de microdonnées individuelles
- Corrélation ≠ causalité
- Les projections sont des simulations déterministes, et non des prévisions économétriques

---

## Auteur

Projet d’analyse en science des données et politiques publiques  
Spécialisation : économie du développement, marché du travail, emploi des jeunes

---

## Objectif

Transformer des données brutes du marché du travail en insights exploitables pour les décideurs publics en Côte d’Ivoire.

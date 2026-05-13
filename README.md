# asset-management-marketing-dashboard
# Dashboard Asset Management & Marketing Intelligence
## Présentation du projet

Ce projet est un dashboard interactif Power BI conçu pour analyser :

* La performance des fonds d’investissement
* L’efficacité commerciale
* La performance marketing et acquisition
* La segmentation du portefeuille
* Les tunnels de conversion marketing

Le dashboard combine des analyses financières et marketing dans une solution décisionnelle unique.

---

# Objectifs du projet

Les objectifs de ce projet étaient de :

* Concevoir un dashboard Power BI multi-pages professionnel
* Mettre en place un storytelling orienté métier
* Créer une expérience utilisateur claire et exécutive
* Travailler la modélisation de données et les mesures DAX
* Simuler un environnement réel de reporting Asset Management

---

# Structure du dashboard

## Page 1 — Vue Exécutive

Vue de pilotage globale contenant :

* Investissements totaux
* Taux de conversion
* Efficacité marketing
* Investissement par interaction
* Évolution mensuelle des investissements
* Investissements par région
* Investissements par type de fonds
* Insights métiers

---

## Page 2 — Analyse des Fonds

Analyse détaillée du portefeuille incluant :

* Efficacité commerciale
* Actifs sous gestion (AUM)
* Performance moyenne des fonds
* Répartition des fonds selon leur performance
* Analyse Performance vs Efficacité commerciale
* Tableau détaillé du portefeuille
* Comparaison investissements et performances

---

## Page 3 — Marketing & Acquisition

Analyse marketing comprenant :

* Dépenses marketing
* ROI marketing
* Coût par clic (CPC)
* Taux de clic (CTR)
* Tunnel de conversion marketing
* Nombre de clics par canal marketing
* Performance des contenus marketing
* Analyse CTR vs dépenses marketing

---

# Fonctionnalités principales

* Navigation interactive entre les pages
* Design Power BI multi-pages
* Slicers interactifs (Année / Mois / Région)
* KPI cards personnalisées
* Analyse de funnel marketing
* Scatter plots analytiques
* Mise en forme conditionnelle
* Mesures DAX avancées
* Storytelling orienté métier

---

# Modèle de données

Le projet utilise un modèle inspiré d’un schéma en étoile avec plusieurs tables de faits.

## Tables principales

### Funds

Contient :

* Fund_ID
* Fund_Name

### Fund_Details

Contient :

* Fund_ID
* Type
* Performance_%
* AUM_M€
* Year

### Sales

Contient :

* Investment
* Region
* Interactions
* Fund_ID
* Year

### Marketing

Contient :

* Channel
* Content_Type
* Views
* Clicks
* Marketing Spend
* Indicateurs de campagne
* Year

### Date Table

Table calendrier personnalisée pour l’analyse temporelle.

# Captures d’écran

Le repository contient des captures des différentes pages :

* Accueil
* Analyse des Fonds
* Marketing & Acquisition

# Licence

Projet réalisé dans un objectif pédagogique et portfolio.

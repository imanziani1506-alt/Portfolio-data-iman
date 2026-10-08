# 📊 Analyse de la satisfaction client avec SQL

## 🎯 Objectif

Analyser les retours clients de BestMarket afin de mesurer la satisfaction client, d’identifier les tendances et de dégager des axes d’amélioration.

## 🏢 Contexte

BestMarket souhaite exploiter les retours de ses clients afin d’améliorer leur expérience.

Les données proviennent de différents canaux de communication tels que les magasins, les réseaux sociaux et le service client.

La base de données relationnelle est composée de trois tables principales :

- `retour_client` : retours et évaluations des clients
- `produit` : informations sur les produits
- `ref_magasin` : informations sur les magasins

## 🛠️ Outil utilisé

- SQL
- MySQL

## 🔎 Méthodologie

- Compréhension du besoin métier et des objectifs d’analyse
- Exploration de la base de données
- Identification des différentes tables et relations
- Contrôle de la cohérence des données
- Vérification des valeurs manquantes et des anomalies
- Analyse des données à l’aide de requêtes SQL
- Création d’indicateurs pour mesurer la satisfaction client
- Interprétation des résultats
- Restitution des analyses

## 📋 Analyses réalisées

### 1. Analyse des retours clients

- Analyse du nombre de retours selon les catégories
- Analyse des sources des retours
- Analyse des retours par période
- Identification des magasins ayant le plus de retours

### 2. Analyse de la satisfaction client

- Calcul des notes moyennes
- Analyse de la satisfaction par typologie de produit
- Analyse de la satisfaction par magasin
- Classement des départements selon la note moyenne
- Analyse de la satisfaction selon les périodes

### 3. Analyse des produits et du service après-vente

- Identification des typologies de produits les mieux notées
- Analyse des produits associés aux retours SAV
- Comparaison des performances selon les périodes

### 4. Analyse des recommandations et du NPS

- Calcul du taux de recommandation
- Calcul du NPS
- Analyse du NPS selon la source des retours

### 5. Analyse des canaux de communication

- Comparaison de la satisfaction selon les canaux
- Analyse du comportement des clients
- Identification des profils de clients satisfaits et insatisfaits

## ✅ Contrôle de la cohérence des données

Plusieurs contrôles ont été réalisés :

- Vérification des valeurs NULL et vides
- Contrôle des valeurs des notes
- Vérification des clés et des relations entre les tables
- Contrôle des doublons éventuels
- Vérification des jointures
- Validation des résultats des requêtes SQL

Une attention particulière a été portée aux valeurs vides de la variable `recommandation`, afin de ne pas fausser les calculs.

## 📈 Résultats

Ce projet permet de :

- Mesurer la satisfaction des clients
- Identifier les catégories et produits les mieux notés
- Comparer les performances des magasins
- Identifier les canaux de communication les plus performants
- Calculer et analyser le NPS
- Identifier les profils de clients satisfaits et insatisfaits
- Produire des informations utiles à la prise de décision


## 📁 Fichiers du projet

- 📄 [Rapport du projet](./Bouskour_Iman_1_expression_besoin_052026.pdf)
- 📄 [Présentation du projet](./Bouskour_Iman_2_presentation_052026.pdf)

## 💡 Conclusion

Ce projet m’a permis de mettre en pratique SQL pour exploiter une base de données relationnelle, réaliser des analyses de satisfaction client et produire des indicateurs utiles à l’aide de requêtes SQL.

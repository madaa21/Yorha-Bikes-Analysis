# YoRHa Bike Sales Analysis - Power BI Portfolio

## Description
Analyse interactive de 1 000 prospects pour l'organisation fictive **YoRHa**, identifiant les leviers d'achat clés (âge, trajet, revenus) avec un taux de conversion de 48,1 %. Ce dashboard optimise le ciblage des 481 acheteurs convertis via une interface *Dark Mode* immersive.

## Présentation du Projet
Ce projet de Data Analyse a été réalisé pour l'organisation fictive **YoRHa**, spécialisée dans la vente de produits de mobilité urbaine. L'objectif est d'analyser les comportements d'achat et d'extraire des insights stratégiques à partir d'une base de données clients.

> **Note technique :** Ce projet utilise un jeu de données fictif provenant de **Kaggle**. Il s'agit d'une base de données volontairement simple, choisie pour m'entraîner à la structuration de rapports, à la modélisation DAX et au design d'interface (UI/UX) sous Power BI.

## Fonctionnalités du Dashboard
Le rapport se divise en deux vues principales (Overview et Map) reliées par un système de navigation dynamique :

* **Design Cockpit :** Thème "Dark Mode" avec un hub central de 4 segments (Slicers) pour une interactivité maximale.
* **KPIs Dynamiques :** Suivi du volume de ventes et du taux de conversion.
* **Analyse Géographique :** Carte mondiale interactive (Bing Maps) traitée en nuances sombres.
* **Segmentation Avancée :** Analyse croisée entre revenus, professions, et distances de trajet.

## Chiffres Clés (KPIs)
* **Total des Prospects :** 1 000 individus.
* **Total Vélos Vendus :** 481 unités.
* **Taux de Conversion (Purchase Rate) :** 48,1 %.
* **Segment Majoritaire :** Les clients "Middle Age" avec 701 individus.

## Analyses Approfondies & Corrélations
Pour ce projet, j'ai poussé l'analyse au-delà des simples totaux pour identifier des comportements d'achat complexes :

### 1. Le Paradoxe de la Distance de Trajet
L'analyse montre que le pic de conversion se situe à **0-1 Mile** avec 366 acheteurs potentiels. 
* **Analyse :** On observe une "chute de conversion" drastique au-delà de 10 miles. Cela suggère que le vélo chez YoRHa est un produit de **commodité et de fitness local** plutôt qu'un outil de transport longue distance. 
* **Corrélation :** Il existe une corrélation inverse entre la distance de trajet et l'intention d'achat.

### 2. Segmentation par CSP et Revenus
Le visuel "Impact of income and gender" révèle des disparités importantes :
* **Haut de gamme :** Les cadres (Management) et les professionnels affichent les revenus moyens les plus élevés (entre 50K et 100K). Cependant, le volume de vente le plus élevé provient des **Skilled Manual (25,5 %)**.
* **Insight :** Le produit YoRHa semble posséder un fort attrait "aspirationnel" pour la classe moyenne technique, qui investit une part plus importante de son revenu disponible dans ce type d'équipement par rapport aux cadres supérieurs.

### 3. Profil du "Client Idéal" (High-Value Persona)
En croisant les slicers, on identifie le profil présentant la plus forte probabilité de conversion :
* **Démographie :** Homme ou femme d'âge moyen (Middle Age).
* **Stabilité :** Propriétaire de son logement (Home Owner : Yes).
* **Localisation :** Amérique du Nord (189 ventes) ou Europe (148 ventes).

## Solutions Stratégiques Proposées
Sur la base de ces analyses profondes, voici trois axes de développement :

* **Axe "Micro-Mobilité" :** Puisque le marché sature après 5 miles, YoRHa devrait lancer une gamme d'accessoires de "Dernier Kilomètre" (trottinettes, vélos pliables) pour capturer le segment des 10+ miles qui utilise actuellement d'autres moyens de transport.
* **Optimisation du Panier Moyen :** Cibler les "Management" (revenus > 80K) avec des éditions limitées ou des vélos en carbone haute performance pour augmenter la marge unitaire sur un segment où le volume est plus faible.
* **Stratégie de Conquête Europe :** Avec 148 ventes contre 189 en Amérique du Nord, l'Europe représente le plus fort levier de croissance immédiat par une simple intensification des réseaux de distribution locaux.

## Stack Technique
* **Source :** Kaggle (Base de données simplifiée pour entraînement).
* **ETL :** Power Query (Nettoyage et typage des données).
* **Modélisation :** DAX (Calcul du taux de conversion et mesures de comptage).
* **Visualisation :** Power BI Desktop (Format 16:9, UI Custom Dark).

---
*Projet réalisé par CHAIB Madani - Aspirant Analyste de données.*

# Challenge National Dataviz : Scolarisation et Territoires
Ce projet a été réalisé dans le cadre du Challenge national de datavisualisation. Il explore l'impact du lieu de résidence sur la réussite scolaire et l'obtention du baccalauréat chez les jeunes de 15 à 29 ans en France.

À partir de données statistiques brutes de l'INSEE, nous avons construit un dashboard Power BI pour analyser et visualiser les inégalités territoriales.

## Objectifs du Projet
 • **Traiter** une masse de données statistiques complexes (INSEE) sur la scolarisation.

 • **Analyser** l'impact du territoire (département, zone urbaine/rurale) sur le niveau de diplôme.

 • **Communiquer** ces écarts via des visualisations claires et interactives.

## Méthodologie et Indicateur Clé
Le défi principal a été de nettoyer, filtrer et croiser les données pour en extraire des indicateurs pertinents.

Nous avons choisi de nous concentrer sur un indicateur principal : **la part de jeunes déscolarisés (15-29 ans) ayant obtenu au moins le baccalauréat**.

Cet indicateur a ensuite été comparé à la moyenne nationale pour identifier les départements en avance ou en retard.

## Visualisations (Power BI)
Le dashboard s'articule autour de deux axes :

  **1-Carte de France Interactive :**

    • Visualise la performance de chaque département par rapport à la moyenne nationale.

    • Un code couleur (🔴 Rouge = au-dessus de la moyenne, 🟠 Orange = proche, 🟢 Vert = en dessous) permet d'identifier instantanément les zones où les jeunes sortant du système scolaire sont les plus        diplômés.

  **2-Graphique Comparatif (Urbain vs. Rural) :**

    • Un barplot met en évidence les écarts de réussite entre les zones urbaines denses et les zones rurales, illustrant l'influence de l'accès aux ressources éducatives.

## Structure des Données
Ce dépôt contient deux fichiers de données clés :

  • **donnees_pour_eleves_v4.xlsx** : Le fichier original, contenant les données techniques et complexes issues de l'INSEE avant traitement.

  • **cleaned_donnees_pour_eleves_v4.xlsx** : Le fichier final, nettoyé, filtré et structuré, qui a servi de source directe pour le dashboard Power BI.

## Outils et Compétences
 • **Outils** : Power BI, Excel (pour le nettoyage et la préparation)

 • **Compétences** :

    • **Nettoyage de données (Data Cleaning)** : Traitement et structuration de fichiers statistiques complexes.

    • **Datavisualisation** : Création de dashboards interactifs et pertinents.

    • **Analyse de données** : Comparaison à la moyenne, identification de tendances.

    • **Data Storytelling** : Apprendre à "faire parler les chiffres" pour construire un message clair et humain sur un enjeu social.

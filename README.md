# OPC_DATA_SCIENTIST_PROJET2
Analysez des données de systèmes éducatifs


# Analyse des Données des Systèmes Éducatifs - Projet Academy

## Aperçu de l'entreprise

![Aperçu du site web](images/DS_projet2..PNG)

## Contexte

Je suis Data Scientist dans une startup EdTech, **academy**, qui propose des contenus de formation en ligne pour un public de niveau lycée et université. Dans le cadre du projet d'expansion internationale de l’entreprise, mon manager, **Mark**, m'a confié la mission d’analyser les données du système éducatif mondial fournies par la **Banque mondiale**. L'objectif est de déterminer si ces données peuvent informer les décisions stratégiques pour l'extension de nos services à l'international.

## Objectifs du Projet

1. **Validation de la Qualité des Données** : Vérifier la qualité du jeu de données en identifiant les valeurs manquantes et dupliquées, ainsi qu'en évaluant les types de données et la structure globale.
   
2. **Sélection des Indicateurs Pertinents** : Identifier les indicateurs clés dans le jeu de données qui pourront aider à répondre aux questions stratégiques de l’entreprise, notamment les indicateurs liés à l’accès à l’éducation, aux diplômes, et aux dépenses éducatives.

3. **Analyse Statistique des Indicateurs** : Réaliser des analyses statistiques descriptives (moyennes, médianes, écarts-types, etc.) par pays, continent, ou bloc géographique pour comprendre les tendances générales dans les différents systèmes éducatifs.

4. **Présenter les Résultats et les Recommandations** : Préparer une présentation claire et professionnelle pour partager les résultats de l’analyse avec les parties prenantes, en illustrant les insights par des graphiques et en formulant des recommandations concrètes pour les futures décisions stratégiques.

## Étapes du Projet

### Étape 1 : Validation de la Qualité des Données

- **Objectif** : Vérifier si les données de la Banque mondiale sont de qualité suffisante pour être utilisées dans une analyse stratégique.
- **Détails** :
  - Identifier les valeurs manquantes et dupliquées.
  - Décrire la structure des données : nombre de lignes, de colonnes, types de variables, etc.
  - Valider la cohérence des données en vérifiant l’exhaustivité des informations.
- **Livrable** : Un notebook Jupyter décrivant le processus de validation de la qualité des données.

### Étape 2 : Sélection des Indicateurs Pertinents

- **Objectif** : Identifier les colonnes et les années pertinentes dans le jeu de données pour répondre aux questions stratégiques liées à l'expansion internationale.
- **Détails** :
  - Sélectionner environ 15 indicateurs liés à l'accès à l’éducation, aux diplômes, aux enseignants et aux dépenses éducatives.
  - Filtrer les données pour ne conserver que les colonnes et années jugées pertinentes.
  - Évaluer la qualité des données associées à ces indicateurs pour s’assurer qu’elles sont exploitables.
- **Livrable** : Un notebook contenant le processus de filtrage et de sélection des données pertinentes.

### Étape 3 : Création d'un DataFrame Exploitable

- **Objectif** : Organiser les données de manière à ce qu’elles soient prêtes pour une analyse descriptive.
- **Détails** :
  - Structurer les données pour que chaque ligne représente un pays (ou un pays/année) et chaque colonne un indicateur.
  - Utiliser des méthodes comme le **pivot table** pour réorganiser les données de manière à ce qu’elles soient prêtes pour l’analyse.
  - Nettoyer et organiser les données pour faciliter l’analyse des tendances par pays et par région géographique.
- **Livrable** : Un ou plusieurs DataFrames prêts pour l’analyse, organisés par pays/année et indicateurs.

### Étape 4 : Analyse Statistique et Visualisation

- **Objectif** : Réaliser une analyse descriptive des données et visualiser les tendances par pays et région.
- **Détails** :
  - Calculer des statistiques descriptives (moyenne, médiane, écart-type, etc.) pour chaque indicateur à l’échelle des pays et des continents.
  - Créer des visualisations univariées (histogrammes, boîte à moustaches) et bivariées (nuages de points, barplots) pour illustrer les relations entre les différents indicateurs.
  - Analyser les corrélations entre les indicateurs et observer les tendances sur plusieurs années.
- **Livrable** : Un notebook contenant les analyses statistiques et les visualisations associées.

### Étape 5 : Présentation des Résultats

- **Objectif** : Présenter une synthèse des résultats de l’analyse sous forme d’une présentation claire et structurée.
- **Détails** :
  - Expliquer la méthodologie utilisée pour analyser les données, en vulgarisant les concepts techniques.
  - Partager les résultats obtenus, illustrés par des graphiques pertinents.
  - Fournir des recommandations sur la pertinence de ces données pour informer le projet d’expansion internationale de l’entreprise.
- **Livrable** : Une présentation PowerPoint ou un rapport détaillant les résultats et les recommandations.

## Détails Techniques

- **Fichiers** :
  - `Données de la Banque mondiale` : Données de l’éducation issues de l'organisme EdStats de la Banque mondiale, accessibles via le site de la Banque mondiale.
  - **Notebook de Préparation des Données** : Contient le processus de validation, de filtrage et d'organisation des données.
  - **Notebook d’Analyse Statistique** : Contient l’analyse descriptive et les visualisations.

- **Outils Utilisés** :
  - **Python** (Jupyter Notebook) pour la préparation des données, le nettoyage, et l’analyse statistique.
  - **Pandas**, **Matplotlib**, **Seaborn** pour la manipulation des DataFrames et la création de visualisations.

- **Compétences Utilisées** :
  - Nettoyage et validation des données.
  - Sélection des indicateurs pertinents.
  - Analyse descriptive et visualisation des données.
  - Communication des résultats et des recommandations.

## Résumé

Ce projet me permet de contribuer à l’expansion internationale d’academy en analysant les données du système éducatif mondial fournies par la Banque mondiale. En sélectionnant les indicateurs les plus pertinents et en réalisant une analyse descriptive détaillée, je fournis des insights qui aideront à orienter les décisions stratégiques pour l’ouverture de nouveaux marchés dans le secteur de l’éducation.

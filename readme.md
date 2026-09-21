# Montée en compétences

Ce dépôt contient tous les objectifs pédagogiques et les exercices pour monter en compétences sur les différents outils utilisés au sein de la DSCI.

## Table des matières

- [Méthode d'apprentissage](#méthode-dapprentissage)
- [Grist](#grist)
- [Python](#python)
- [Développement logiciel]()
- [SQL](#sql)
- [Git](#git)
- [Apache Superset](#apache-superset)
- [Apache Airflow](#apache-airflow)

## Méthode d'apprentissage

Un programme est réalisé pour prendre en main les différents outils.  
Chaque programme contient les informations suivantes :
- Liste des objectifs pédagogiques
- Liste de ressources disponibles
- Liste d'exercices (lorsqu'ils ne sont pas proposés dans les ressources)
- Quizz d'auto-évaluation

La vidéo suivante présente des méthodes d'apprentissage efficaces pour s'approprier de nouvelles connaissances : [https://www.youtube.com/watch?v=RVB3PBPxMWg](https://www.youtube.com/watch?v=RVB3PBPxMWg)


## Grist

1. Objectifs pédagogiques

| Objectif pédagogique | Description (verbe d'action + critère évaluable) |
|---------------------|-------------|
| Décrire l'écosystème Grist | Lister les fonctionnalités clés, expliquer son usage et identifier l'entité qui le maintient. |
| Créer et organiser des espaces et des documents | Créer un espace de travail, un document, le renommer et le déplacer vers un nouvel espace, puis le dupliquer sans erreur. |
| Construire un document | Créer des tables avec des colonnes typées, des pages et des vues, puis y saisir des données. |
| Écrire des formules | Rédiger une formule à partir d'une formule intégrée puis construire une formule Python qui renvoie le résultat attendu. |
| Partager son espace et ses documents | Configurer les droits de partage d'un document et collaborer en temps réel avec un autre utilisateur. |
| Adopter les bons réflexes | Diagnostiquer et corriger les erreurs courantes (types de données, formules, structure) en s'appuyant sur les messages de Grist. |

2. Ressources disponibles

  - [Documentation DINUM de Grist](https://docs.numerique.gouv.fr/docs/5da3aba2-9954-4ee0-9169-60083b59379b/)
  - [Découvrir Grist - Tutoriel vidéo](https://tube.numerique.gouv.fr/w/p/iff7qfK674FiEEw21dfgng?playlistPosition=5&resume=true)
  - [Grist - documentation officielle](https://grist.com/)


3. Exercices

La métropole du Grand Lyon met à disposition un document Grist pour s'exercer sur l'ensemble des fonctionnalités de l'outil.  
Le document contient les exercices, des tutoriels vidéos ainsi que le corrigé des exercices.  

Le document est accessible via le lien suivant : [Exercices Grist - Métropole du Grand Lyon](https://forum.grist.libre.sh/t/grist-mooc-formation-grist-en-autonomie/4005)

4. Quizz d'auto-évaluation

_a venir_

## Python

1. Objectifs pédagogiques

| Objectif pédagogique | Description (verbe d'action + critère évaluable) |
|---------------------|-------------|
| Déclarer des variables | Instancier des variables avec les types natifs (int, float, str, bool, list, dict, set, tuple), convertir entre types et vérifier le type obtenu avec `type()`. |
| Écrire des structures conditionnelles | Implémenter des conditions `if/elif/else` et vérifier le chemin d'exécution sur des cas limites. |
| Écrire des boucles | Itérer sur des séquences (listes, dictionnaires, plages) avec `for`/`while` pour réaliser des opérations répétitives. |
| Définir et appeler des fonctions | Définir des fonctions avec paramètres et valeur de retour, puis les réutiliser pour organiser le code. |
| Construire et instancier une classe | Modéliser une classe avec attributs et méthodes, l'instancier, et appliquer l'héritage et la composition. |
| Créer et utiliser les dunder méthodes | Identifier les principales dunder méthodes (ex. `__init__`, `__str__`, `__repr__`, `__eq__`, `__len__`) et les surcharger pour adapter le comportement des objets. |
| Utiliser les principales built-in méthodes des types | Appliquer les méthodes courantes de `str`, `dict`, `list`, `set` pour transformer et manipuler les données. |
| Configurer un environnement de développement | Créer un environnement virtuel, installer des packages via `pip` et gérer les dépendances (ex. `requirements.txt`). |


2. Ressources disponibles

  - [Documentation INSEE de Python](https://www.sspcloud.fr/catalog?path=Introduction%E2%90%A3to%E2%90%A3Python)
  - [Cours orienté objet en Python](https://courspython.com/classes-et-objets.html)
  - [Environnements python](https://docs.python.org/fr/3/tutorial/venv.html) (uniquement les sections 12.1 et 12.2)
  - [Les design patterns en Python](https://refactoring.guru/design-patterns/python) (Abstract Factory, Adapter, Composite, Strategy)

3. Exercices

Pour la maitrise de Python, il est conseillé de suivre le cours en ligne proposé par l'INSEE.  

4. Quizz d'auto-évaluation

_a venir_

## Développement logiciel

1. Objectifs pédagogiques

| Objectif pédagogique | Description |
|---------------------|-------------|

## SQL

1. Objectifs pédagogiques

| Objectif pédagogique | Description (verbe d'action + critère évaluable) |
|---------------------|-------------|
| Associer les types de données SQL | Classer les types de données disponibles (numériques, chaînes, dates/heures, booléens) et choisir le type adapté à une valeur donnée. |
| Écrire des requêtes de sélection | Rédiger des requêtes `SELECT` avec `WHERE`, `ORDER BY`, `GROUP BY`, `LIMIT` pour extraire les données attendues d'une table. |
| Écrire des jointures | Combiner des données de plusieurs tables avec `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN` et contrôler le nombre de lignes résultantes. |
| Écrire des sous-requêtes et des CTE | Construire des sous-requêtes et des `WITH` (CTE) pour effectuer des opérations complexes et les hiérarchiser lisiblement. |
| Utiliser les fonctions d'agrégation | Appliquer `COUNT`, `SUM`, `AVG`, `MIN`, `MAX` avec `GROUP BY`/`HAVING` pour calculer des statistiques sur des ensembles. |
| Créer des vues | Définir une vue à partir d'une requête, l'utiliser comme table et la maintenir (modifier/supprimer). |
| Créer et gérer des rôles et des utilisateurs | Créer des rôles/utilisateurs, leur attribuer des permissions (lecture, écriture) et les révoquer pour sécuriser les données. |
| Écrire des window functions | Calculer une information à partir d'un sous-ensemble des données qui est lié à la ligne actuel. |
| Optimiser des requêtes | Analyser un plan d'exécution, identifier les requêtes lentes et les améliorer (index, reformulation). |

2. Ressources disponibles

  - [Cours SQL de W3Schools](https://www.w3schools.com/sql/)
  - [Gestion des rôles dans PostgreSQL](https://www.postgresql.org/docs/current/database-roles.html)


## Git

1. Objectifs pédagogiques

| Objectif pédagogique | Description (verbe d'action + critère évaluable) |
|---------------------|-------------|
| Créer un dépôt | Initialiser un dépôt depuis le web (ex. GitHub) et depuis un dossier local avec `git init`, puis relier les deux. |
| Réaliser un commit | Ajouter une modification à l'index, créer un message de commit et pousser vers le dépôt distant. |
| Appliquer les conventions de commit | Rédiger des messages de commit conformes aux Conventional Commits (type, scope, description). |
| Créer et gérer une branche | Créer une branche, y réaliser des modifications, la pousser en remote et la fusionner. |
| Créer une Pull Request | Ouvrir une Pull Request pour fusionner sa branche vers une autre branche et la valider. |
| Résoudre un conflit de branche | Identifier un conflit de fusion, choisir la partie du code à conserver et finaliser la fusion. |

2. Ressources disponibles

_a venir_


3. Exercices

_a venir_


4. Quizz d'auto-évaluation

_a venir_

## Apache Superset

1. Objectifs pédagogiques

| Objectif pédagogique | Description (verbe d'action + critère évaluable) |
|---------------------|-------------|
| Créer, modifier et supprimer un dataset | Créer un dataset depuis une source, y créer une nouvelle colonne et une nouvelle mesure, puis le supprimer. |
| Créer, modifier et supprimer un graphique | Construire un graphique à partir d'un dataset, en changer le type, les dimensions/mesures puis le supprimer. |
| Créer, modifier et supprimer un tableau de bord | Assembler des graphiques dans un tableau de bord, réorganiser/éditer les onglets puis le supprimer. |
| Créer un dataset personnalisé depuis le SQL Lab | Rédiger une requête SQL dans le SQL Lab, exécuter la requête et sauvegarder le résultat en dataset. |
| Créer, modifier et supprimer un utilisateur | Créer un compte utilisateur, lui attribuer un rôle/permissions, les modifier puis le supprimer. |
| Personnaliser le visuel d'un tableau de bord | Sélectionner une palette de couleurs et appliquer des couleurs à des valeurs spécifiques. |
| Créer, modifier et supprimer une connexion aux sources de données | Configurer une connexion à une base de données, la modifier puis la supprimer. |
| Créer un graphique carte | Construire un graphique cartographique en liant une dimension géographique aux mesures. |


2. Ressources disponibles

_a venir_


3. Exercices

_a venir_


4. Quizz d'auto-évaluation

_a venir_

## Apache Airflow

1. Objectifs pédagogiques

| Objectif pédagogique | Description (verbe d'action + critère évaluable) |
|---------------------|-------------|
| Décrire les notions clés d'Airflow | Définir les concepts DAG, Task, Scheduler, XCom et Trigger et expliquer leurs interactions. |
| Créer une task simple | Définir une tâche (opérateur) dans un DAG avec ses paramètres (task_id, op_args, retries, etc.). |
| Créer une mapped task | Paramétrer une tâche pour qu'elle s'exécute sur plusieurs entrées via le mapping (`.expand()` ou `partial`). Évaluable : la tâche s'exécute pour chaque entrée fournie et les résultats sont tous présents. |
| Créer un DAG | Définir un DAG avec ses paramètres (schedule, owner, start_date) et relier les tâches par dépendances. |
| Partager des données entre tâches | Échanger des données entre tâches via XCom (`xcom_push`/`xcom_pull` ou `return`). |
| Analyser les logs d'un DAG et d'une tâche | Consulter les logs d'exécution, localiser les erreurs et en identifier la cause. |
| Créer une variable | Définir, modifier et utiliser une variable Airflow dans les DAGs. |
| Créer une connexion | Créer et configurer une connexion Airflow (ex. base de données, API) et l'utiliser dans une tâche. |

2. Ressources disponibles

_a venir_


3. Exercices

_a venir_


4. Quizz d'auto-évaluation

_a venir_

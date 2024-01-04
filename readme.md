L'objectif de ce document est de vous donner les bases pour gérer un projet de développement de logiciel. Il ne s'agit pas d'un document exhaustif, mais d'un ensemble de notions et de bonnes pratiques basiques qui vous permettront de gérer un projet de manière efficace.

## Sommaire

- [1. Introduction générale et notion de base](#1-introduction-générale-et-notion-de-base)
  - [1.1. Qu'est-ce qu'un projet ?](#11-quest-ce-quun-projet-)
- [2. Le Cahier des Charges](#2-le-cahier-des-charges)
- [3. La méthode Agile](#3-la-méthode-agile)
  - [3.1. Les principes de la méthode Agile](#31-les-principes-de-la-méthode-agile)
  - [3.2. Les rôles de la méthode Agile](#32-les-rôles-de-la-méthode-agile)
  - [3.3. Les artefacts de la méthode Agile](#33-les-artefacts-de-la-méthode-agile)
  - [3.4. Les événements de la méthode Agile](#34-les-événements-de-la-méthode-agile)
- [4. Le cycle de vie d'un projet](#4-le-cycle-de-vie-dun-projet)
- [5. Les outils de gestion de projet Agile](#5-les-outils-de-gestion-de-projet-agile)
  - [5.1. Les Kanban Boards](#51-les-kanban-boards)
  - [5.2. Les User Stories](#52-les-user-stories)
- [Notes](#notes)

## 1. Introduction générale et notion de base

### 1.1. Qu'est-ce qu'un projet ?

En gestion de projet, un projet se définit par un ensemble d'activités **coordonées** et **temporaires**, son objectif est de créer un **produit**, un **service** ou un **résultat** **_unique_**.

- Temporaire : un projet a un début et une fin définis.
- Unique : Le résultat d'un projet est unique. Bien que le projet puisse impliquer des éléments répétitifs ou courants, son ensemble d'objectifs et de livrables est distinct et crée quelque chose de nouveau ou de différent.
- Objectif : Un projet est mené pour répondre à des exigences spécifiques et produire des livrables spécifiques.
- Ressources : Un projet est mené en mobilisant des ressources.
- Planification, Exécution et Contrôle : Un projet est mené en planifiant détaillé, en exécutant et en contrôlant les activités.
- Gestion des risques : Les projets comportent des risques, et la gestion des risques fait partie intégrante de la gestion de projet.
- Adaptation : Un projet est mené dans un environnement incertain et est adapté à cet environnement changeant.
- Stakeholders : Un projet a des parties prenantes (stakeholders) qui ont un intérêt dans le projet.

Le projet est une entreprise complexe et structurée.

### 1.2 Clarifier les besoins et les attentes du client

Avant de commencer un projet, il est important de clarifier les besoins et les attentes du client. Cela permet de s'assurer que le projet répondra aux besoins du client et que le client sera satisfait du résultat. Pour ça, il existe des outils comme les User Stories, les outils de gestion de projet Agile, etc.
Il est important d'éclaircir même les choses les plus basiques comme le titre du produit ou du service, les fonctionnalités, les technologies, etc.

## 2. Le Cahier des Charges

Le cahier des charges est un document qui décrit les besoins et les attentes du client. Il est rédigé par le client et doit être validé par le client et le prestataire. Il doit être le plus précis possible et doit être rédigé en collaboration avec le prestataire.

- Présentation du projet : contexte, objectifs, enjeux, etc.
- Définition de la portée du projet : périmètre, limites, etc.
- Besoins et exigences : fonctionnels, techniques, etc.
- Spécifications techniques : technologies, langages, etc.
- Planifications et échéances : dates de livraison, etc.
- Critères de validation : tests, recettes, etc.
- Budget.
- Gestion des risques.
- Procédures de gestion de projet : réunions, reporting, etc.
- Annexes.

## 3. La méthode Agile

En développement logiciel, la méthode Agile est une approche itérative et incrémentale de la gestion de projet. Elle permet de réduire les risques en divisant le projet en plusieurs itérations appelées "**Sprints**".

Chaque **sprint** est une phase de développement qui dure entre 1 et 4 semaines. A la fin de chaque sprint, une version du logiciel est livrée au client. Le client peut alors tester le logiciel et faire des retours au prestataire. Ces retours sont pris en compte dans le sprint suivant.

La méthode Agile permet de réduire les risques et de s'adapter aux changements. Elle permet également de livrer des versions du logiciel plus rapidement. Elle est particulièrement adaptée aux projets de développement logiciel.

### 3.1. Les principes de la méthode Agile

- **L'implication du client** : Le client est impliqué dans le projet et participe à la rédaction du cahier des charges. Il est également impliqué dans le développement du logiciel et peut faire des retours au prestataire à la fin de chaque sprint.

- **L'adaptation au changement** : La méthode Agile permet de s'adapter aux changements. Le client peut faire des retours au prestataire à la fin de chaque sprint. Ces retours sont pris en compte dans le sprint suivant.

- **La collaboration** : La méthode Agile favorise la collaboration entre les membres de l'équipe de développement. Elle favorise également la collaboration entre le client et le prestataire.

- **La livraison rapide** : La méthode Agile permet de livrer des versions du logiciel plus rapidement. A la fin de chaque sprint, une version du logiciel est livrée au client.

- **L'auto-organisation** : La méthode Agile favorise l'auto-organisation des équipes de développement. Elle permet aux équipes de s'organiser elles-mêmes et de s'adapter aux changements.

- **L'amélioration continue** : La méthode Agile permet d'améliorer continuellement le logiciel. Le client peut faire des retours au prestataire à la fin de chaque sprint. Ces retours sont pris en compte dans le sprint suivant.

### 3.2. Les rôles de la méthode Agile

- **Le Product Owner (PO) :**

  Représente les intérêts du client et les utilisateurs finaux.
  Responsable de la définition des priorités du produit et de la création du backlog du produit.

  Assure que les livrables répondent aux attentes et aux besoins des utilisateurs.
  Ne gère pas directement le projet ou la planification des sprints, mais contribue à la définition des objectifs de chaque sprint.

- **Le Scrum Master** :

  Sert de facilitateur pour l'équipe Scrum, en soutenant et en promouvant les pratiques Scrum.
  Responsable de l'élimination des obstacles qui pourraient empêcher l'équipe de développement de réaliser ses objectifs.

  Aide l'équipe et l'organisation à améliorer leurs processus et pratiques de travail.
  N'est pas le représentant du prestataire mais plutôt un coach et un facilitateur pour l'équipe Scrum.

- **L'équipe de développement** :

  Composée de professionnels qui réalisent le travail de création du produit (développeurs, testeurs, designers, etc.).

  Autogérée et multidisciplinaire, l'équipe collabore étroitement pour atteindre les objectifs définis pour chaque sprint.
  Responsable de la qualité technique du produit et de la réalisation des tâches définies dans le backlog du sprint.

### 3.3. Les artefacts de la méthode Agile

Dans la méthodologie Agile, et en particulier dans le cadre de Scrum, les artefacts sont des outils ou des documents qui fournissent des informations cruciales pour le développement et la gestion du projet.

Ils aident à organiser le travail, à suivre les progrès et à faciliter la communication au sein de l'équipe et avec les parties prenantes.

| Artefact                   | Description                                                                                                                                                       |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Product Backlog            | Liste ordonnée de tout ce qui pourrait être nécessaire dans le produit. Gérée par le Product Owner.                                                               |
| Sprint Backlog             | Sélection d'éléments du Product Backlog que l'équipe s'engage à livrer à la fin d'un sprint.                                                                      |
| Increment (PSPI)           | Ensemble des éléments du Product Backlog complétés pendant un sprint, additionnés aux incrémentations des sprints précédents. Doit être potentiellement livrable. |
| Burndown Charts            | Graphiques montrant le travail restant dans un sprint ou un release.                                                                                              |
| Définition de "Fait" (DoD) | Ensemble clair de critères que chaque produit ou fonctionnalité doit satisfaire pour être considéré comme terminé.                                                |
| Définition de "Prêt" (DoR) | Ensemble clair de critères que chaque élément du Product Backlog doit satisfaire pour être considéré comme prêt à être développé.                                 |

### 3.4. Les événements de la méthode Agile

Dans la méthodologie Agile, les événements sont des réunions qui permettent de synchroniser l'équipe et de planifier le travail.

| Événement                   | Description                                                                                                                                                  |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Sprint                      | Période fixe (généralement de 2 à 4 semaines) pendant laquelle l'équipe travaille pour livrer un ensemble spécifique d'éléments du Product Backlog.          |
| Planification de Sprint     | Réunion où l'équipe choisit quels éléments du Product Backlog seront réalisés pendant le prochain sprint. Planifie également comment atteindre cet objectif. |
| Scrum quotidien             | Brève réunion quotidienne (15 minutes) où l'équipe discute de ce qui a été fait la veille, ce qui sera fait aujourd'hui et identifie les obstacles.          |
| Revue de Sprint             | Rencontre à la fin du sprint où l'équipe présente les éléments du Product Backlog qu'elle a terminés pendant le sprint aux parties prenantes.                |
| Rétrospective de Sprint     | Réunion après la Revue de Sprint où l'équipe réfléchit sur le sprint passé pour s'améliorer continuellement.                                                 |
| Affinage du Product Backlog | Processus continu d'examen et de révision des éléments du Product Backlog pour assurer leur clarté et leur précision, ainsi que pour prioriser les tâches.   |

## 4. Le cycle de vie d'un projet

Le cycle de vie d'un projet est l'ensemble des phases qui composent un projet. Il est composé de 5 phases :

- **La phase d'initialisation** : Définit les objectifs, les ressources nécessaires et les contraintes du projet (budget, délais, etc.).

- **La phase de planification** : Concerne la définition des tâches, la planification du projet, et l'établissement des rôles et responsabilités de l'équipe.

- **La phase de réalisation** : Implique la mise en œuvre des tâches planifiées, le suivi de l'avancement du projet, et la gestion des risques.

- **La phase de clôture** : Consiste à livrer le projet au client, clôturer le projet formellement, et préparer un rapport initial sur les performances et les résultats du projet.

- **La phase de post-projet** : Se concentre sur l'analyse approfondie du projet terminé, le tirage des leçons apprises, et la capitalisation sur les acquis et l'expérience pour des projets futurs.

## 5. Les outils de gestion de projet Agile

### 5.1. Les Kanban Boards

Le Kanban est une méthode de gestion de projet qui permet de visualiser le travail, de limiter le travail en cours et de maximiser l'efficacité.

Il s'agit d'un tableau qui permet de visualiser les tâches à réaliser, les tâches en cours et les tâches terminées.
Il permet également de suivre l'avancement du projet et de s'adapter aux changements.

GitHub propose un outil de gestion de projet basé sur le Kanban Board. Il permet de créer des projets, des colonnes et des cartes. Il permet également de définir des étiquettes et des filtres.

Il est important de considérer que les tâches dans le kanban board doivent être suffisamment petites pour être réalisées en une journée. Si une tâche est trop grande, elle doit être découpée en plusieurs tâches plus petites. Cela permet de suivre l'avancement du projet et de s'adapter aux changements. C'est l'un des principes de la méthode Agile.

### 5.2. Les User Stories Expliquées Simplement

Une User Story est un moyen simple et clair de décrire une fonctionnalité d'un logiciel du point de vue de l'utilisateur. C'est une courte histoire qui explique ce que l'utilisateur souhaite accomplir en utilisant le logiciel. Elle est créée en collaboration entre le client (qui a besoin du logiciel) et le prestataire (qui développe le logiciel). Ces histoires aident à imaginer comment le logiciel sera utilisé dans la pratique.

Il est important de définir les rôles des utilisateurs. Cela permet de définir les fonctionnalités du logiciel et de s'assurer que le logiciel répondra aux besoins des utilisateurs.

**Chaque User Story comprend trois parties principales :**

**La Description** : C'est le cœur de la User Story. Elle explique en quelques mots ce que l'utilisateur veut faire avec le logiciel. Par exemple, "Je veux pouvoir me connecter à mon compte".

**Les Critères d'Acceptation** : Ce sont les conditions qui doivent être remplies pour que la User Story soit considérée comme complète. Ils définissent ce qui est nécessaire pour que la fonctionnalité soit opérationnelle. Par exemple, "Je dois pouvoir saisir mon adresse email et mon mot de passe".

**La Valeur Métier** : Elle montre l'utilité ou l'avantage que cette fonctionnalité apporte à l'utilisateur. Par exemple, "Cela me permet d'accéder à mon profil".

Pour rendre cela plus concret, voici un exemple :

    En tant qu'utilisateur, je veux pouvoir me connecter à mon compte afin d'accéder à mon profil.

    Critères d'acceptation :

    - Je peux entrer mon adresse email et mon mot de passe pour me connecter.

    Valeur métier :

    - J'accède facilement à mon profil et à mes informations personnelles.

Cela se traduit en un tableau simple :

| En tant que | Je veux pouvoir... | Afin de...           |
| ----------- | ------------------ | -------------------- |
| Utilisateur | me connecter       | accéder à mon profil |

Et en anglais :

| As a | I want to... | So that...             |
| ---- | ------------ | ---------------------- |
| User | log in       | access my profile page |

La formule générale est : "En tant que [type d'utilisateur], je veils pouvoir [action] afin de [bénéfice]".

L'objectif est de présenter clairement ces concepts pour les débutants en développement logiciel.

### 5.3. Poker Planning

### 5.4. Wireframes et Mockups

Le Wireframe est un schéma qui permet de visualiser l'interface du logiciel, il est fonctionnel. Ce n'est pas le design final, on parlera plutot de maquette ou de mockup dans ce cadre là.
Les wireframes sont souvent très rudimentaires, ils permettent de visualiser l'interface du logiciel et de s'assurer que le logiciel répondra aux besoins des utilisateurs avant de commencer le développement.

Il est envisageable de faire plusieurs Wireframes, par exemple un pour la version mobile et un pour la version desktop.

### Notes

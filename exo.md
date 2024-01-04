Besoin d'une structure de base de données.

J'ai besoin d'une plateforme de quizz où chaque élève pourrait se connecter à une interface pour répondre à des quizz.

Chaque quizz aurait un titre, une thématique (ex: cosmologie, informatique...) ainsi que des sujets relatifs au quiz (ex: pour la cosmologie, on aurait l'espace, la relativité, la gravitation...).

Chaque quizz aurait un auteur et serait signé (ex: Gerôme Durand).

Chaque quizz aurait des questions avec un type de question et des réponses possibles (voir schéma).

Chaque question aurait éventuellement un petit contexte ainsi qu'un niveau de difficulé : débutant, confirmé, expert mais potentiellement plus.

En terme d'interface, on aurait

- une zone de correction
- les "coulisses"
- en allant dans un quizz
  - on pourrait répondre aux question
  - voir les niveaux
  - voir la thématique
  - et valider
- puis on aurait les résultats:
  - avec un petit score
  - pour voir si les réponses sont bonnes ou mauvaises
  - j'ai pas besoin dans la plateforme de stocker ça en revanche, c'est seulement pour de la consommation immédiate.

Définitions des roles :

- un visiteur : c'est un utilisateur qui navigue sans être connecté
- un membres : c'est un utilisateur qui s'est connecté
- un administrateur : c'est un utilisateur qui a les droits d'administration

| En tant que    | Je veux pouvoir...         | Afin de...                                    |
| -------------- | -------------------------- | --------------------------------------------- |
| Visiteur       | voir la homepage           | visualiser les quizzs de l'application        |
| Visiteur       | voir la page de connexion  | me connecter                                  |
| Visiteur       | voir la page d'inscription | m'inscrire                                    |
| Membre         | Aller dans les quizz       | Participer aux quizz                          |
| Membre         | Voir mes résultats         | Visualiser mon score                          |
| Membre         | Voir mes résultats         | Voir si mes réponses sont bonnes ou mauvaises |
| Membre         | Se déconnecter             | Me déconnecter                                |
| Administrateur | Crééer un quizz            | Créer un quizz                                |
| Administrateur | Modifier un quizz          | Modifier les réponses/questions du quizz      |
| Administrateur | Supprimer un quizz         | Supprimer un quizz                            |

MCD :

### 1. Les entités et leurs attributs :

- Utilisateur: nom, prénom, email, mot de passe
- Quizz: titre, description
- Questions: description, wiki, anecdote
- Niveau: nom
- Thème: nom
- Propositions de réponse: description

### 2. Schématisation du MCD en drawio

### 3. Souligner le discriminant

Le discriminant est un attribut qui permet de différencier les entités de manière unique.

exemple :

- on ne peut pas avoir 2 utilisateurs avec le même email
  => email est un discriminant

### 4. Les associations

Les associations sont des liens entre les entités.
Note : Les associations seront stockées en base, soit par une clé étrangère, soit par une table de jointure.

Pour les niveaux, les cardinalités pourraient être :

- `0, N` : un niveau peut caractériser 0 questions. Exemple : un Administrateur crééer un niveau mais ne l'a pas encore assigné à une question.
- `1, N` : un niveau caractérise au moins une question. Exemple : un Administrateur crééer un niveau et l'assigne à une question. L'implication est que l'interface nous oblige à assigner un niveau à une question.

# Plan de cours

Programmation Web dynamique \
582-21B-MA \
75 heures (2-3-3)

Préalables: 582-11B

Enseignant: Maxime Pigeon (mpigeon@cmaisonneuve.qc.ca)

## Description

Dans ce second cours de programmation côté serveur, l'étudiant·e
apprendra à utiliser une base de données. Plus précisément, il ou elle
apprendra à créer des structures de données, ainsi que les principales
opérations liés à la manipulation de ces données. Il ou elle apprendra
aussi à se connecter à une base de données par programmation, et à y
effectuer des opérations. Il ou elle apprendra à traiter les données
afin de produire une réponse à une requête HTTP.

## Compétences à développer

### EHPA : Effectuer la programmation d'un site Web

1.  Analyser la demande
2.  Programmer les éléments du site Web
3.  Résoudre les erreurs de programmation
4.  Vérifier la qualité de la programmation
5.  Documenter la programmation
6.  Gérer les versions de code source

### EHP2 : Effectuer le développement de la partie serveur d'un site Web

1.  Traiter les requêtes d'un navigateur Web
2.  Interagir avec une base de données en-ligne
3.  Répondre aux requêtes d'un navigateur Web

### EHP3 : Exploiter des bases de données pour le Web


1.  Créer une base de données pour le Web
2.  Effectuer des opérations standards sur la base de données pour le Web
3.  Exploiter une base de données à l'aide d'une application en
    ligne de gestion de base de données pour le Web
4.  Sauvegarder et restaurer une base de données pour le Web

## Calendrier

### Étape 1 : Concevoir une base de données

À la première étape, l'étudiant·e apprend à reconnaître un problème qui
nécessite une source de données persistante. Il ou elle apprend les
étapes du processus de conception d'une base de données, et comment
concevoir une base de données à l'aide du modèle entité-relation.

|     | Contenu                                | Remises         |
| --: | -------------------------------------- | --------------- |
|   1 | Présentation du cours                  |                 |
|   2 | Modélisation d'une base de données I   |                 |
|   3 | Modélisation d'une base de données II  |                 |
|   4 | Modélisation d'une base de données III |                 |
|   5 | Atelier                                |                 |

### Étape 2 : Produire une base de données

À la deuxième étape, l'étudiant·e apprend à produire le schéma d'une
base de données relationnelle à partir du modèle entité-relation. Il ou
elle apprend les opérations de création, lecture, mise à jour et
suppression qui permettent de produire et de gérer le contenu d'une base
de données relationnelle.

|     | Contenu                                | Remises         |
| --: | -------------------------------------- | --------------- |
|   6 | Modèle relationnel I                   |                 |
|   7 | Modèle relationnel II                  |                 |
|   8 | Du modèle au schéma                    |                 |
|   9 | SQL I                                  |                 |
|  10 | SQL II                                 | TP1             |
|  11 | Atelier                                |                 |

### Étape 3 : Produire une serveur HTTP

À la troisième étape, l'étudiant·e est introduit·e au logiciel de
gestion de versions Git, ainsi qu'au langage de programmation Python.
Il ou elle est aussi introduit·e à la programmation orientée objet.
À l'aide de ces outils, l'étudiant·e apprend à mettre sur pied un
serveur capable de traiter des requêtes HTTP.

|     | Contenu                                | Remises         |
| --: | -------------------------------------- | --------------- |
|  12 | Introduction à Git                     |                 |
|  13 | Introduction à Python                  |                 |
|  14 | Programmation orientée objet           |                 |
|  15 | Architecture REST                      |                 |
|  16 | Requêtes et réponses HTTP              | TP2             |
|  17 | Atelier                                |                 |

### Étape 4 : Produire un site Web dynamique

À la dernière étape, l'étudiant·e apprend à créer un site Web dynamique
qui intègre une base de données. Il ou elle est introduit à la gestion
d'état et à l'authentification côté serveur. Enfin, l'étudiant·e est
amené·e à mettre en place des tests unitaires afin d'assurer la
robustesse d'un programme.

|     | Contenu                                | Remises         |
| --: | -------------------------------------- | --------------- |
|  18 | Interface de base de données           |                 |
|  19 | Gestion de contenu                     |                 |
|  20 | Tests unitaires                        |                 |
|  21 | État et authentification               |                 |
|  22 | Atelier                                | Projet final I  |
|  23 | Pot-pourri                             |                 |
|  24 | Atelier                                |                 |
|  25 | Atelier                                | Projet final II |

## Évaluations

### Devoirs (20%)

Plusieurs devoirs seront donnés au fil de la session. Le but des devoirs
est d'encourager la pratique, sans pénaliser l'erreur. À cette fin, le
contenu des devoirs ne sera pas évalué. Un devoir remis à temps, fait honnêtement par l'étudiant·e, recevra une note parfaite.

### Travaux pratiques (20% × 2)

Ce cours compte deux travaux pratiques durant lesquels les étudiant·es
auront l'opportunité de mettre en œuvre la matière vue en classe. Les
travaux pratiques auront la forme de projet à faire individuellement à
l'extérieur de la classe.

### Projet final (40% / 2)

Le projet final du cours s'effectuera en deux phases, chacune corrigée
indépendamment. En premier lieu, l'étudiant·e sera amené·e à implémenter
un serveur capable de traiter des requêtes HTTP. Ensuite, il ou elle
devra connecter le serveur à une base de données. Le travail se fera
seul·e, et du temps en classe y sera alloué.

#### Critères d'évaluation

-   Analyse adéquate du devis de production
-   Modélisation adéquate d'une base de données
-   Exploitation précise d'un système de gestion de base de données
-   Utilisation adéquate des requêtes SQL
-   Utilisation adéquate des éléments du langage de programmation
    pour traiter et afficher des données dynamiques
-   Traitement correct de la requête et production d'une réponse HTTP
    appropriée

## Approche pédagogique

L'approche pédagogique pour ce cours consiste en un mélange d'exposés
magistraux et d'exercices pratiques dirigés. L'approche privilégiée pour
les évaluations est centrée sur le development de projets, au terme
desquels les étudiant·es recevront des remarques sur la qualité du
travail effectué. Quoique l'objectif du cours ne soit pas la
mémorisation du matériel vu en classe, il est attendu des étudiant·es
qu'ils ou elles puissent expliquer leurs choix. Des exercices à cet
effet prendront place au fil de la session.

## Plagiat et fraude

> À l'instar des autres maisons d'enseignement supérieur, le Collège de
> Maisonneuve considère l'honnêteté intellectuelle comme une valeur
> fondamentale dans le monde académique. Il condamne donc toute forme de
> tromperie et s'attend à ce que ses étudiant·es et son personnel
> adoptent une conduite irréprochable dans leur production
> intellectuelle.
>
> Tout espoir d'un progrès du savoir requiert que les idées puissent
> circuler le plus librement possible, que les connaissances soient
> partagées et échangées de façon respectueuse et constructive. Pour
> cela, la confiance est indispensable. Chacun·e est en droit d'espérer
> et même de présumer que sa contribution personnelle aux connaissances
> sera reconnue et que personne d'autre ne la fera passer pour sienne.
> Piller la pensée d'un·e autre, c'est décourager l'effort intellectuel
> et miner l'entreprise du savoir dont nous bénéficions tous.
>
> Au cégep, il n'y a plus vraiment d'excuses qui tiennent : vous devez
> parfaire le réflexe de l'honnêteté intellectuelle. L'un des socles de
> la formation collégiale consiste à développer une aptitude à rendre
> compte ou à expliquer des faits ou des idées sur la base d'une
> réflexion personnelle, puis à communiquer celle-ci. La maîtrise de
> cette compétence ne peut souffrir d'aucun raccourci. Si vous utilisez
> les idées ou les écrits d'un autre en les prétendant vôtres, non
> seulement vous êtes malhonnête, mais vous passez complètement à côté
> de cet objectif.

Plus d'informations à ce sujet sont disponibles ici : [https://www.cmaisonneuve.qc.ca/plagiat-et-fraude/](https://www.cmaisonneuve.qc.ca/plagiat-et-fraude/).

## Pénalité de retard

À moins d'un accord préalable avec l'enseignant, tout travail pratique
remis en retard sera pénalisé de 5% de la note maximale pour chaque jour
de retard, incluant la fin de semaine et les jours fériés. Les retards
ne seront pas acceptés pour les devoirs.

## Politiques d'évaluation des apprentissages

Conformément aux politiques institutionnelles et départementales
d'évaluation des apprentissages, les modalités d'application
spécifiques dans le contexte de la formation continue sont disponibles
ici : [http://fc.cmaisonneuve.;.ca/sites/default/files/FC_Modalite_PIEA_582.pdf](http://fc.cmaisonneuve.qc.ca/sites/default/files/FC_Modalite_PIEA_582.pdf).
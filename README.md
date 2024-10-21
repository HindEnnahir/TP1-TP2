# TP1 : Programmation Dynamique et Réflexion en Java

## Description

L'objectif de ce projet est de comprendre et mettre en œuvre l'utilisation de la *programmation dynamique* en Java pour gérer l'instanciation des classes, l'injection des dépendances et l'invocation des méthodes via la *réflexion*. Cette approche permet de charger dynamiquement les classes et de configurer une application sans dépendre d'une configuration statique.

## Contexte

Dans ce projet, nous allons développer une application Java qui utilise des interfaces et des classes pour effectuer le calcul d'une valeur. L'application devra exploiter la réflexion pour :

- Charger dynamiquement les implémentations des interfaces.
- Gérer l'injection des dépendances.
- Configurer l'application à partir d'un fichier de configuration externe, offrant ainsi une flexibilité dans la gestion des dépendances.

Cette approche améliore la modularité de l'application et facilite son évolution future sans nécessiter de modifications majeures dans le code source.

## Fonctionnalités

- Chargement dynamique des classes à l'exécution via la réflexion.
- Injection de dépendances entre les composants de l'application.
- Utilisation d'un fichier de configuration externe pour définir les implémentations des interfaces.
- Flexibilité accrue dans la gestion des dépendances grâce à la programmation dynamique.

# TP2 : Application Java avec Spring - Inversion de Contrôle et Injection de Dépendances

## Description

Ce projet a pour objectif de créer une application Java en utilisant *Spring Framework* pour mettre en œuvre les concepts d'*Inversion de Contrôle (IoC)* et d'*Injection de Dépendances (DI)* via des annotations. L'application consistera à développer des interfaces DAO et métier, tout en gérant l'injection des dépendances entre elles de manière automatisée grâce à Spring.

## Contexte

Dans ce projet, nous développons une application modulaire basée sur deux types d'interfaces principales :
- Une *interface DAO* (Data Access Object) pour la gestion des données.
- Une *interface métier* pour les règles de gestion.

Le framework Spring sera utilisé pour l'*injection automatique des dépendances* entre ces composants, éliminant ainsi la nécessité de configurer manuellement les dépendances dans le code. Cette approche permet de simplifier l'architecture de l'application, en la rendant plus flexible et maintenable grâce à l'utilisation des annotations.

## Fonctionnalités

- Implémentation de l'Inversion de Contrôle (IoC) à travers le container Spring.
- Gestion de l'injection des dépendances (DI) à l'aide des annotations Spring (@Autowired, @Component, @Repository, etc.).
- Modularisation de l'application via des interfaces pour le DAO et la couche métier.
- Gestion facile des dépendances et de la configuration à l'exécution via Spring.

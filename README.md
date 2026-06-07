# SAÉ 1.04 – Introduction aux bases de données

## Réalisé par : LANOIZELET Colin & LANGE Lorenzo
## Date : Janvier 2026 | IUT Université de Lille – Département Informatique

## Présentation du projet
Ce dépôt contient l'ensemble des fichiers réalisés dans le cadre de la SAÉ 1.04 portant sur l'introduction aux bases de données. L'objectif était de modéliser et d'implémenter le système d'information d'une entreprise de transport de marchandises, depuis la commande client jusqu'à la réalisation du trajet.

## Contenu du dépôt

- transport_de_marchandise.mcd : Modèle Conceptuel de Données (MCD)
- transport_de_marchandises.bcd : Fichier source du MCD 
- transport_de_marchandises.mld : Modèle Logique de Données (MLD)
- Espace_de_travail.sws : Espace de travail du logiciel de modélisation
- RapportBDD.pdf : Rapport complet du projet

## Structure de la base de données
La base modélise 7 tables interconnectées :

- Client – informations sur les clients de l'entreprise
- Commande – demandes de transport passées par les clients
- Trajet – déplacements planifiés avec dates, véhicule et chauffeur associés
- Chauffeur – conducteurs affectés aux trajets
- Véhicule – flotte de transport (marque, type, poids max)
- Ville – villes de départ et d'arrivée
- Distance – distances en km entre paires de villes


## Outils utilisés

Looping – modélisation MCD/MLD
Microsoft Access – implémentation de la base, requêtes SQL, formulaires et états


## Lancer / consulter le projet

Ouvrir Espace de travail.sws dans Looping pour visualiser les modèles MCD et MLD
Consulter Rapport BDD.pdf pour le détail des choix de conception, des requêtes SQL et des captures d'écran

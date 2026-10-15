# Projet d'Ingénierie des données sur Azure 

## Contexte du projet 

Réalisation d'un projet de data engineering pour concevoir un pipeline de données complet sur le cloud Microsoft Azure, simulant le besoin réel des entreprises de migrer et centraliser leurs données. 

## Sources de données 

Le projet intègre et centralise des données de sources variées : 

- Données On-Premise : Fichiers d'entreprise (factures, données financières/sensibles) et bases de données SQL locales. 

- APIs Externes : Récupération de données dynamiques via des API REST (ex : API GitHub)

## Ce que j'ai réalisé 

- Ingestion et Pipelines dynamiques : Création de pipelines de données automatisés pour charger les fichiers et bases SQL vers le Data Lake Azure.

- Architecture Médaillon (Bronze, Silver, Gold) : Organisation des données par niveaux de transformation en utilisant Azure Data Factory (ADF).

- Automatisation : Utilisation conjointe d'Azure Data Factory et Azure Logic Apps pour orchestrer les flux.

- Monitoring : Mise en place d'un suivi et d'une surveillance des pipelines pour s'assurer du bon déroulement des traitements.

- Gestion de version (Git) : Connexion d'Azure Data Factory à GitHub avec l'utilisation de branches et de Pull Requests pour appliquer les bonnes pratiques de développement.


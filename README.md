# Projet Big Data : Pipeline de traitement de logs

## Objectif
Ce projet implémente un pipeline de traitement de logs machine à l'aide de technologies Big Data open source :
- Kafka pour la gestion des flux
- Hadoop HDFS pour le stockage
- Zeppelin pour l'analyse des données

## Structure
- `data/` : Contient des fichiers de données d'exemple
- `scripts/` : Scripts Python et Bash pour le traitement des données
- `config/` : Fichiers de configuration pour Kafka et Hadoop
- `notebooks/` : Notebooks Zeppelin pour l'analyse

## Installation
1. Configurez le cluster Adaltas avec Hadoop et Kafka.
2. Installez les dépendances Python :
   ```bash
   pip install -r requirements.txt

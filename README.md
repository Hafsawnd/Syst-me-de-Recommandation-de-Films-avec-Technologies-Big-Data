**Système de Recommandation de Films avec Technologies Big Data**

Ce projet consiste en la conception et l'implémentation d'un système de recommandation de films utilisant des technologies Big Data dans l'environnement Hortonworks Data Platform (HDP). L'objectif principal était de développer une solution évolutive capable de fournir des recommandations personnalisées aux utilisateurs.

**Architecture Technique**
Le système repose sur une pile technologique complète :
- **Kafka** pour l'ingestion en temps réel des données films
- **HDFS** pour le stockage distribué des données
- **Apache Pig** pour le nettoyage et la transformation des données
- **PySpark** pour l'implémentation de l'algorithme de filtrage collaboratif
- **Hive** pour l'analyse et le stockage des résultats
- **Power BI** pour la visualisation des données

**Méthodologie**
Le processus suit un pipeline de données structuré :
1. Collecte des données via des scripts Kafka personnalisés
2. Nettoyage et prétraitement avec Apache Pig
3. Implémentation d'un algorithme de similarité cosinus avec PySpark
4. Génération de recommandations basées sur les préférences utilisateur
5. Évaluation des performances via précision, rappel et RMSE

**Résultats**
Le système démontre des performances solides :
- Précision moyenne : 50-70% selon les utilisateurs
- Rappel moyen : 30-60%
- RMSE : 0.845, indiquant une bonne précision prédictive

Cette solution offre une base robuste pour des systèmes de recommandation évolutifs, combinant traitement distribué et algorithmes de machine learning pour une expérience utilisateur personnalisée.

# Résumé du Projet

## Mission

La mission consiste à compléter et améliorer la chaîne de traitement initiée par l'alternant. L'accent est mis sur la mise en place des premières briques de traitement pour gérer efficacement un volume croissant de données. Le développement se fait en Pyspark dans un environnement Big Data, notamment sur le cloud AWS (EMR, S3, IAM), avec une démonstration de l'instance EMR opérationnelle et une explication détaillée du script PySpark.

## Contraintes

1. **Évolution Volumique :** Anticipation d'une augmentation rapide du volume de données après la livraison du projet.
2. **Démonstration EMR :** Mise en place d'une instance EMR opérationnelle, avec explication détaillée du script PySpark comprenant la diffusion des poids du modèle TensorFlow sur les clusters et une étape de réduction de dimension de type PCA.
3. **RGPD :** Respect des contraintes du RGPD, en paramétrant l'installation pour utiliser des serveurs situés sur le territoire européen.
4. **Coûts :** Minimisation des coûts liés à l'instance EMR, maintenue opérationnelle uniquement pour les tests et démos.

## Livrables

1. **Notebook sur le Cloud :** Contenant les scripts Pyspark exécutables, couvrant le preprocessing et une étape de réduction de dimension de type PCA.
2. **Stockage Cloud :** Images du jeu de données initial, sortie de la réduction de dimension (matrice CSV ou autre) disponibles dans un espace de stockage sur le cloud.
3. **Support de Présentation :** Présentant les choix d'architecture sur le cloud, leur rôle dans l'architecture Big Data, la mise en œuvre de l'environnement Big Data (EMR ou Databricks), et les étapes de la chaîne de traitement PySpark.

## Référentiel d'Évaluation

1. **Identification d'Outils Cloud pour le Big Data :** Identification des briques d'architecture nécessaires et des outils du cloud pour mettre en place un environnement Big Data.
2. **Manipulation de Données dans un Environnement Big Data :** Chargement de fichiers dans un espace de stockage cloud conforme au RGPD, exécution de scripts avec des machines cloud, écriture des sorties directement dans l'espace de stockage cloud.
3. **Parallélisation des Opérations avec Pyspark :** Identification des traitements critiques à l'échelle, respect du RGPD, développement de scripts basés sur Spark, et exécution complète de la chaîne dans le cloud.

## Compétences Évaluées

- Utilisation des outils du cloud pour manipuler des données dans un environnement Big Data.
- Identification des outils du cloud pour mettre en place un environnement Big Data.
- Parallélisation des opérations de calcul avec Pyspark.

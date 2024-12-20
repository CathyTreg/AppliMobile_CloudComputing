# AppliMobile_CloudComputing
Construction d’une architecture Big Data (Cloud Computing) dans le cadre de la création d'une application mobile - Projet réalisé en septembre 2024 dans le cadre du parcours de formation DataScientist.

Contexte : « Fruits! » est une start-up AgriTech qui développe une application mobile permettant aux utilisateurs de prendre en photo des fruits et d’obtenir instantanément des informations sur ces derniers. Ce projet repose sur la mise en place d'une infrastructure Big Data et de traitements distribués pour gérer une grande quantité d'images.

Objectif : Créer une solution de traitement de données d’images à grande échelle, capable de fonctionner dans le cloud avec des performances optimales.

Tâches :
-	Conception de l'architecture Big Data : 
o	Développer une architecture Big Data intégrée à l'application mobile pour le traitement et la classification des images ;
o	Utiliser les services AWS EMR (Elastic MapReduce) pour gérer le calcul distribué et l'exécution des tâches à grande échelle ;
o	Instancier des serveurs EC2 pour le traitement distribué et la gestion de l'infrastructure ;
-	Traitement des données à grande échelle avec PySpark :
o	Développer des scripts en PySpark pour effectuer des calculs distribués sur les données ;
o	Implémenter des Spark sessions permettant de charger et traiter efficacement les images en parallèle sur plusieurs nœuds, avec une gestion optimale de la mémoire et des ressources.

Résultats : 
-	Le traitement des données via les Spark session (code pySpark) permettra un passage à l’échelle simple et rapide en faisant appel à des exécuteurs ;
-	Ce processus fonctionne de manière optimale avec l'infrastructure distribuée mise en place, avec un temps de traitement de moins de 10 minutes pour 100 000 images.

Environnement de travail : Service EMR (Service cloud pour exécuter des calculs distribués) d’AWS avec EC2 (location de serveurs virtuels), Jupyter Hub avec PySpark
Librairies : NumPy – Pandas – Matplotlib – TensorFlow/Keras – PySpark


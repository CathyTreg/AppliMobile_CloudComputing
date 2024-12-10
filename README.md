# AppliMobile_CloudComputing
Construction d’une architecture Big Data (Cloud Computing) dans le cadre de la création d'une application mobile - Projet réalisé en septembre 2024 dans le cadre du parcours de formation DataScientist.

Contexte : 
-	L’entreprise « Fruits! », une très jeune start-up de l'AgriTech, cherche à proposer des solutions innovantes pour la récolte des fruits.
-	La start-up souhaite dans un premier temps se faire connaître en mettant à disposition du grand public une application mobile qui permettrait aux utilisateurs de prendre en photo un fruit et d'obtenir des informations sur ce fruit.
-	Il faut donc intégrer dans l’application un moteur de classification des images de fruits.

Tâches :
-	Construire une architecture Big Data qui sera intégrée à l’application mobile.
-	Développer une première chaîne de traitement des données qui comprendra le preprocessing et une étape de réduction de dimension (sur la base d’un notebook développé par un alternant).
-	Etablir une chaine de traitement des données qui pourra facilement passer à l’échelle : développer les scripts en pyspark pour effectuer du calcul distribué.

Actions : 
-	Créer l’environnement BigData avec AWS.
-	Configurer le service EMR avec EC2 pour permettre le calcul distribué (Hadoop et Spark).
-	Stocker les données images sur Amazon S3.
-	Traiter les données et préparer le modèle avec PySpark.

Résultats : 
-	Le traitement des données via les Spark session (code pySpark) permettra un passage à l’échelle de manière simple et rapide en faisant appel à des exécuteurs.
-	Ce process fonctionne très bien avec l'infrastructure distribuée mise en place (temps de traitement de moins de 10 minutes sur les 100 000 images). 

Environnement de travail : Service EMR (Service cloud pour exécuter des calculs distribués) d’AWS avec EC2 (location de serveurs virtuels), Jupyter Hub avec PySpark
Librairies : Numpy – Pandas – Matplotlib – TensorFlow/Keras – PySpark

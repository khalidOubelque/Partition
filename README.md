# Partition
fonction « partition » qui prend un paramètre « liste » et un paramètre « taille » et retourne une liste de sous liste, où chaque sous liste a au maximum « taille » éléments.


-------------Project Title---------------

Le livrable dispose d'une fonction partitionList() qui retourne une liste de sous liste, où chaque sous liste a au maximum


-------------Prerequisites----------------

You will need to run this jar file :
	. jdk 8
	. Projet Maven(J'ai deja partager le jar dans le repository Maven), si non j'ai mis le jar en jointure il faut juste l'ajouter dans le classpath du projet.
	. Ajouter la dependence maven dans le fichier pom :
			 <dependency>
			  <groupId>com.oubelque.Partition</groupId>
			  <artifactId>Partition-0.0.1-SNAPSHOT</artifactId>  
			  <version>0.0.1-SNAPSHOT</version>
			</dependency>
	. JUNIT 4.12 	


-----------Running ------------------- 
		. Il suffit d'instancier la classe Partition et mettre en parametre la taille et la list a partitionner, et apres appeller la methode comme mentionne dessous :
				ListPartition p = new ListPartition(subset,paramList);
				p.partitionList();
				
		. Le test unitaire(JUNIT) s'executera automatiquement, au cas d'echeance une exception et afficher.

---------------Authors------------------
OUBELQUE KHALID

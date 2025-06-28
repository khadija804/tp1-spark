# TP: Traitement parallèle et distribué avec Spark

Exercice 1 :
1. On souhaite développer une application Spark permettant, à partir d’un
   fichier texte (ventes.txt) en entré, contenant les ventes d’une entreprise dans
   les différentes villes, de déterminer le total des ventes par ville. La structure
   du fichier ventes.txt est de la forme suivante :
   date ville produit prix

   - Compte du nombre total de ventes
   ![1](captures/totalVente.png)

   - Calcul du total des ventes par ville
   ![2](captures/totalVenteParVille.png)

   - Calcul du total des ventes par ville et année
   ![3](captures/totalVenteParVilleEtAnnee.png)

Exécution sur un cluster Spark (via Docker)

    - Lancer le cluster
![4](captures/spark_up.png)
   - Executer le script
![4](captures/execute.png)


Projet 4 : Gestion Sécurisée de Bases de Données de Mots de Passe

# Sommaire : 

1.  [Description du Projet](#Description-du-Projet)
2.  [Membre du groupe](#Membre-du-groupe)
3.  [Rôle des Membres](#Rôle-des-membres)
4.  [Architecture technique](#Architecture-technique)



  
  # **Description du Projet**
  
Ce projet consiste en la mise en place d'une infrastructure de gestion centralisée et sécurisée de mots de passe, basée sur le logiciel KeePass.
Le déploiement s'articule autour de deux bases de données chiffrées, accessibles dans un environnement hybride (Windows et Linux), garantissant ainsi une haute disponibilité pour vous (le Client).

------------------------------------------------------------------------------------------------------------
  # **Membre du groupe**
 
  * PO_Product Owner : Minjha
  * SM_Scrum Master : Cédric
  * Tech : Anass
  * Tech : Zinedine

  # **Rôle des Membres**  

  Minjha : "Création du Backlog et participation à la documentation du projet."
  
  Cédric : "Gestion et encadrement du projet. Installation de KeePass sur les clients (Windows 11/Ubuntu) et la rédaction de la documentation."
  
  Anass : "Effectué une connexion sécurisée en SSH qui permet aux 4 machines de communiquer entre-elles et la synchronisation des terminaux."
   
  Zinedine : "Installation de la clef de chiffrement sur chaque serveur, création des accès aux 2 BDD via le protocole SMB."

  #  **Architecture technique**
  
La Base de données "DSI_T0" est hébergée sur un serveur Windows Server 2025.

La Base de données "DSI_T1" est hébergée sur un serveur Linux Debian 13.

Vous (le Client) avez l'accès aux bases de données de manière sécurisée via le logiciel KeePass pour vous connectez aux bases de données via le réseau.

En terme de sécurité : Chaque base de données utilise une signature de chiffrement unique et les clées de chiffrement sont conservées localement sur leurs serveurs hôtes respectifs.

# **Démonstration**

Je donne la parole à mon Scrum Master pour vous expliquez, tout ce que nous avons élaboré durant cette 1ere semaine de projet : 




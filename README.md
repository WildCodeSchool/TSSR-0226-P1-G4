Projet 4 : Gestion Sécurisée de Bases de Données de Mots de Passe

# Sommaire : 

1.  [Description du Projet](#Description-du-Projet)
2.  [Membre du groupe](#Membre-du-groupe)
3.  [Rôle des Membres](#Rôle-des-membres)
4.  [Architecture technique](#Architecture-technique)



  
  # **Description du Projet**
  
Ce projet consiste en la mise en place d'une infrastructure de gestion centralisée et sécurisée de mots de passe, basée sur le logiciel KeePass.
Le déploiement s'articule autour de deux bases de données chiffrées, accessibles dans un environnement hybride (Windows et Linux), garantissant ainsi une haute disponibilité pour les clients.

------------------------------------------------------------------------------------------------------------
  # **Membre du groupe**
 
  * PO_Product Owner : Minjha
  * SM_Scrum Master : Cédric
  * Tech : Anass
  * Tech : Zinedine

  # **Rôle des Membres**  

  Minjha : "Encadré le projet. Création du Backlog, aide à la documentation du projet."
  
  Cédric : "Gestion du projet. Installation de KeePass sur les clients (Windows 11/Ubuntu), rédigé la documentation."
  
  Anass : "Effectué une connexion sécurisée en SSH qui permet aux 4 machines de communiquer entre-elles et la synchronisation des terminaux."
   
  Zinedine : "Installation de la clef de chiffrement sur chaque serveur, création des accès aux 2 BDD via le protocole SMB."

  #  **Architecture technique**
  
Base de données DSI_T0 : Hébergée sur un serveur Windows Server 2025.

Base de données DSI_T1 : Hébergée sur un serveur Linux Debian 13.

Accès : Les clients disposent du logiciel KeePass pour se connecter aux bases de données respectives via le réseau.

Sécurité : Chaque base de données utilise une signature de chiffrement unique. Les clées de chiffrement sont conservées localement sur leurs serveurs hôtes respectifs.




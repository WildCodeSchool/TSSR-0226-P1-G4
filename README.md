Projet : Gestion Sécurisée de Bases de Données de Mots de Passe

# Sommaire : 

1.  [Description du Projet](#Description-du-Projet)
2.  [Membre du groupe](#Menbre-du-groupe)
3.  [Rôle des Membres](#Rôle-des-membres)
4.  [Architecture technique](#Architecture-technique)



  
  # **Description du Projet**
  
Ce projet consiste en la mise en place d'une infrastructure de gestion centralisée et sécurisée de mots de passe, basée sur le logiciel KeePass.
Le déploiement s'articule autour de deux bases de données chiffrées, accessibles dans un environnement hybride (Windows et Linux), garantissant ainsi une haute disponibilité et une interopérabilité pour les clients.

------------------------------------------------------------------------------------------------------------
# **Membre du groupe **
  * Minjha
  * Zinedine
  * Anass
  * Cédric

# **Rôle des Membres **  

  Minjha : Product Owner,"Création du Backlog, aide à la documentation du projet."
  
  Zinedine : Tech,"Installation de KeePass sur serveurs (Windows/Debian), création des accès BDD."
  
  Anass : Tech,"Création des accès SSH, configuration des BDD, documentation."
  
  Cédric : Scrum Master,"Gestion du framework, installation de KeePass sur clients (Windows 11/Ubuntu), documentation."

  #  **Architecture technique**
Base de données DSI_T0 : Hébergée sur un serveur Windows.

Base de données DSI_T1 : Hébergée sur un serveur Linux.

Accès : Les clients disposent du logiciel KeePass pour se connecter aux bases de données respectives via le réseau.

Sécurité : Chaque base de données utilise une signature de chiffrement unique. Les clés de chiffrement sont conservées localement sur leurs serveurs hôtes respectifs.




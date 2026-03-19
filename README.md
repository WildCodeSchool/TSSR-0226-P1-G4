Projet 4 : Gestion Sécurisée de Bases de Données de Mots de Passe

# Sommaire : 

1.  [Description du Projet](#Description-du-Projet)
2.  [Membre du groupe et Rôle des Membres](#Membre-du-groupe-et-Rôle-des-Membres)
3.  [Architecture technique](#Architecture-technique)
4.  [Technologies Utilisées](#Technologies-Utilisées)


 ##  Description du projet 
Ce projet consiste en la mise en place d'une infrastructure de gestion centralisée et sécurisée de mots de passe, basée sur le logiciel KeePass.

Le déploiement s'articule autour de deux bases de données chiffrées, accessibles dans un environnement hybride (Windows et Linux), garantissant ainsi une haute disponibilité pour vous (le Client).

> **Analogie du Major :** On ne laisse pas les clés du serveur sous le paillasson. On construit une salle des coffres avec une porte blindée (chiffrement) et on s'assure qu'on peut y accéder même si un ascenseur tombe en panne (haute disponibilité).

![LAB](https://github.com/WildCodeSchool/TSSR-0226-P1-G4/blob/main/ressource/Sch%C3%A9ma-Projet.png)

------------------------------------------------------------------------------------------------------------
  # **Membre du groupe et Rôle des Membres**
 

  |             |                                                                        **Sprint 1**                                                                        |                                 **Sprint 2**                                 |
| :---------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------: |
| **Anass**  |                                 Effectué une connexion sécurisée en SSH qui permet aux 4 machines de communiquer entre-elles et la synchronisation des terminaux.                                   |   _Product owner_: Maintenir la direction du projet. Livraison de l'audit.Backlog    |
| **Zinedine**  | Installation de la clef de chiffrement sur chaque serveur, création des accès aux 2 BDD via le protocole SMB. |                  Rédaction de la présentation.                   |
|  **Minjha**  |   _Product owner_: Création du Backlog et participation à la documentation du projet.Backlog   |                          Rédaction de INSTALL.md. Documentation de la réalisation                           |
| **Cédric** |                                 _Scrum Master_: Gestion et encadrement du projet. Installation de KeePass sur les clients (Windows 11/Ubuntu) et la rédaction de la documentation.                                    |  Mise en place de la Démonstration, Rédaction du README.md |
| **Commun**  |                                     Installation de toutes les VM et des logiciels pour pouvoir tester en même temps.                                      |                       Test du cassage de mot de passe. Travail sur la présentation                        |

 
  #  **Architecture technique**
  
La Base de données "DSI_T0" est hébergée sur un serveur Windows Server 2025.

La Base de données "DSI_T1" est hébergée sur un serveur Linux Debian 13.

L'accès aux bases de données de manière sécurisée via le logiciel KeePass pour se connecter aux bases de données via le réseau.

Sécurité : Chaque base de données utilise une signature de chiffrement unique et les clées de chiffrement sont conservées localement sur leurs serveurs hôtes respectifs.

 #  Projet Infrastructure de Gestion Sécurisée des Accès Privilégiés

##  Description du projet

Ce projet consiste en la mise en place d'une infrastructure de gestion centralisée et sécurisée de mots de passe, basée sur le logiciel KeePass. 

Le déploiement s'articule autour de deux bases de données chiffrées, accessibles dans un environnement hybride (Windows et Linux), garantissant ainsi une haute disponibilité pour vous (le Client).


#  Technologies Utilisées

- VM 1 : WIN01 - CLIENT WINDOWS 11
- OS : Windows 11
- Compte & Mot de passe : Wilder, Azerty1*
- Adresse Ip : 172.16.10.10
- Masque : 255.255.255.0

------------------------------------

- VM 2 : UBU01 - CLIENT UBUNTU
- OS : Ubuntu 24.04
- Compte & Mot de passe : wilder, Azerty1*
- Adresse Ip : 172.16.10.20
- Masque : 255.255.255.0

------------------------------------

- VM 3 : SRVWIN01 - WindowsServer
- OS : Windows Server 2025 GUI
- Compte & Mot de passe : Administrator, Azerty1*
- Adresse Ip : 172.16.10.5
- Masque : 255.255.255.0

------------------------------------

- VM 4 : SRVLX01 - DebianServer
- OS : Debian 13 CLI
- Compte & Mot de passe : Root, Azerty1*
- Adresse Ip : 172.16.10.6
- Masque : 255.255.255.0






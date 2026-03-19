# Projet : Gestion Sécurisée de Bases de Données de Mots de Passe

# **_Sommaire_** : 

1.  [Description du Projet](#Description-du-Projet)
2.  [Membre du groupe et Rôle des Membres](#Membre-du-groupe-et-Rôle-des-Membres)
3.  [Architecture technique](#Architecture-technique)
4.  [Technologies Utilisées](#Technologies-Utilisées)
5.  [Logiciel](#Logiciel)
6.  [Difficultés et solutions rencontrées](#Difficultés-et-solutions-rencontrées)
7.  [Améliorations possibles](#Améliorations-possibles)

   #  **_Description du projet_** 
Ce projet consiste en la mise en place d'une infrastructure de gestion centralisée et sécurisée de mots de passe, basée sur le logiciel [KeePass](https://keepass.info/index.html).

Le déploiement s'articule autour de deux bases de données chiffrées, accessibles dans un environnement hybride (Windows et Linux), garantissant ainsi une haute disponibilité pour vous (le Client).

> **Analogie du Major :** On ne laisse pas les clés du serveur sous le paillasson. On construit une salle des coffres avec une porte blindée (chiffrement) et on s'assure qu'on peut y accéder même si un ascenseur tombe en panne (haute disponibilité).

![LAB](https://github.com/WildCodeSchool/TSSR-0226-P1-G4/blob/main/ressource/Projet1-G4-Page-1.drawio%20(1).png)

------------------------------------------------------------------------------------------------------------
   # **_Membre du groupe et Rôle des Membres_**
 

|      Noms       |      Rôles  S-01                  |                                              Sprint 1                                                                        |      Rôles S-02       |                   Sprint 2                                 |
| :---------: | :-----------------------: | :---------------------------------------------------------------------------------------------------------------------------------: | :----------------: | :----------------------------------------------------------: |
| Anass  |              Tech expert              |     Effectué une connexion sécurisée en SSH qui permet aux 4 machines de communiquer entre-elles et la synchronisation des terminaux.                                   | POProduct Owner            |Product owner: Maintenir la direction du projet. Livraison de l'audit.Backlog    |
| Zinedine  |         Tech expert   |Installation de la clef de chiffrement sur chaque serveur, création des accès aux 2 BDD via le protocole SMB. |               Tech expert                         |    Rédaction de la présentation.           |
|  Minjha  |            Product Owner | Création du Backlog et participation à la documentation du projet.Backlog   |                      Scrum Master                      |     Rédaction de INSTALL.md. Documentation de la réalisation       |
| Cédric |                Scrum Master |                 Gestion et encadrement du projet. Installation de KeePass sur les clients (Windows 11/Ubuntu) et la rédaction de la documentation.                             |    Tech expert         |  Mise en place de la Démonstration, Rédaction du README.md |
| Commun  |                |                     Installation de toutes les VM et des logiciels pour pouvoir tester en même temps.                                      |                                             | Test du cassage de mot de passe. Travail sur la présentation 

 
   #  **_Architecture technique_**
  
La Base de données "DSI_T0" est hébergée sur un serveur Windows Server 2025.

La Base de données "DSI_T1" est hébergée sur un serveur Linux Debian 13.

L'accès aux bases de données de manière sécurisée via le logiciel KeePass pour se connecter aux bases de données via le réseau.

Sécurité : Chaque base de données utilise une signature de chiffrement unique et les clées de chiffrement sont conservées localement sur leurs serveurs hôtes respectifs.


   #  **_Technologies Utilisées_**

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

  # **_Logiciel_**

- Keepass 2.61 : [Lien de Téléchargement](https://keepass.info/download.html) , [Lien de Documentation](https://keepass.info/index.html)
- WinCSP : [Lien de Téléchargement](https://winscp.net/eng/download.php) , [Lien de Documentation](https://winscp.net/eng/docs/start)

## **_Difficultés et solutions rencontrées_**

| **Difficultées**                                           |                                                       **Solutions** |
| :--------------------------------------------------------- | ------------------------------------------------------------------: |
| Logiciel Putty                 |                                    Installation de Winscp |
| Connection au serveur la plus securisé                 |           Connection via le Protocol SMB (windows) |
| Connection au serveur la plus sécurisé   |    Connection vie la Protocol Samba (unix) |


# **_Améliorations possibles_**

**Il est recommandé de ne jamais stocker la clé de chiffrement au même endroit que la base de données afin de renforcer la sécurité !** 


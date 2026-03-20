# Logiciel KeePass

&nbsp;

## Étape 1 — Lancement du logiciel KeePass
Ouvrir le logiciel KeePass depuis votre dossier : Mes Documents en double cliquant sur l'application

&nbsp;

<img width="870" height="634" alt="Screenshot 2026-03-18 153521" src="https://github.com/user-attachments/assets/eba9739e-4e50-4935-bdf8-4734a77e5e8e" />

&nbsp;

## Étape 2 — Créer une nouvelle clef chiffrée KeePass

&nbsp;

Cliquer sur le menu fichier en haut à gauche et sélectionner "Nouveau".
<img width="870" height="635" alt="Screenshot 2026-03-18 153552" src="https://github.com/user-attachments/assets/5ec51715-03a2-49ba-b43f-28a760250d76" />

&nbsp;

## Étape 3 — Tapez votre mot de passe "Azerty1* dans la section Master password
Cochez la case "Key file/provider et appuyez sur le bouton "créer"

&nbsp;


<img width="692" height="737" alt="Screenshot 2026-03-18 153957" src="https://github.com/user-attachments/assets/33bee563-c023-45da-a75f-59c6689f4bc4" />

&nbsp;

Cliquez sur "Create a new key file (randowm key) puis cliquez sur OK.

&nbsp;

<img width="609" height="531" alt="Screenshot 2026-03-18 154035" src="https://github.com/user-attachments/assets/e0baade0-e674-4833-86de-83f8fd5d68ef" />

&nbsp;

## Étape 3 — Créer votre base de donnée DSI_T0 et enregistrez la dans vos Documents
Dans la section "File name" supprimez "DataBase" et écrivez "DSI_T0" puis cliquez sur "Save".

&nbsp;

<img width="1485" height="591" alt="Screenshot 2026-03-18 175622" src="https://github.com/user-attachments/assets/4566b074-314b-429e-a505-86786bcb3412" />

&nbsp;

Dans la section "DataBase name :" écvrivez "DSI_T0" puis cliquez sur OK.

&nbsp;

<img width="647" height="595" alt="Screenshot 2026-03-18 175755" src="https://github.com/user-attachments/assets/5b546ab2-d484-48f4-a220-7c2c00078be8" />

&nbsp;

## Étape 3 — Sauvegardez la base de donnée dans vos Documents

&nbsp;

<img width="872" height="633" alt="Screenshot 2026-03-18 175930" src="https://github.com/user-attachments/assets/26e90a14-f307-4471-9382-f9171caebf74" />

&nbsp;


<img width="966" height="447" alt="Screenshot 2026-03-18 180023" src="https://github.com/user-attachments/assets/a3e1c2bf-9d3f-4993-a621-ec794b4cb871" />

&nbsp;

# Étape 4 — Générez un mot de passe niveau ultra sécurisé 256 bits

&nbsp;

Cliquez sur "Tools" et sélectionnez "Generate Password".

&nbsp;

<img width="870" height="633" alt="Screenshot 2026-03-18 180143" src="https://github.com/user-attachments/assets/94e8eb1e-cf06-417e-806d-f616f941ba81" />

&nbsp;

<img width="650" height="706" alt="Screenshot 2026-03-18 180804" src="https://github.com/user-attachments/assets/87e45d8d-b9e8-4c56-8251-07430138d1ef" />


<img width="652" height="630" alt="Screenshot 2026-03-18 180710" src="https://github.com/user-attachments/assets/81216660-58a9-4e4b-a179-c210fe8dae84" />

# Comparaison avec un mot de passe 10 fois plus faible (Azerty1*) 28 bits
<img width="650" height="627" alt="Screenshot 2026-03-18 180730" src="https://github.com/user-attachments/assets/89d49c01-25f0-42e4-a73e-44269968b3ad" />

# Configuration d'accès au server via SSH

## Faire un ping avec l'ip du serveur : 172.16.10.5 pour s'assurer que la connexion entre WIN01 et SRVWIN01 est bien établie :
<img width="519" height="258" alt="Screenshot 2026-03-18 155339" src="https://github.com/user-attachments/assets/0954e468-8bb2-4caf-b81c-2271da10a812" />

## Vérifier que le protocole SSH est activé sur votre poste de travail via la commande suivante :
<img width="745" height="174" alt="Screenshot 2026-03-18 152638" src="https://github.com/user-attachments/assets/95bfe217-c5ed-4c3e-a0af-93754854bdaf" />

## Se connecter au serveur via le protocole SSH via la commande suivante :
<img width="1017" height="118" alt="Capture d&#39;écran 2026-03-19 130602" src="https://github.com/user-attachments/assets/9b61314d-aa4b-45f6-934d-b793e0d9bc2d" />

# Bravo vous avez maintenant accès au server !

## administrator@SRVWIN01 nous confirme que vous êtes connecté au serveur depuis WIN01.
<img width="1023" height="170" alt="Capture d&#39;écran 2026-03-19 121241" src="https://github.com/user-attachments/assets/d2f94200-964a-4b6e-86b9-e30eb54aba23" />

# Configuration de la synchronisation entre WIN01 et le serveur SRVWIN01 via protocol SMB :
<img width="1351" height="112" alt="Capture d&#39;écran 2026-03-19 121920" src="https://github.com/user-attachments/assets/a82f677c-e0d2-44ec-8225-3fd5b4305269" />

# Création du pont réseau entre client WIN01 et notre serveur SRVWIN01 pour y déposer la bdd DSI_T0 et la clef chiffrée
<img width="519" height="765" alt="Screenshot 2026-03-18 180939" src="https://github.com/user-attachments/assets/9e64344a-b8e7-4e8d-bb6d-d2b22d75a047" />
<img width="480" height="277" alt="Screenshot 2026-03-18 180956" src="https://github.com/user-attachments/assets/f97e4d7c-a803-4c76-add7-fa1c5efb4104" />
<img width="486" height="258" alt="Screenshot 2026-03-18 181026" src="https://github.com/user-attachments/assets/bc3b18f7-2d7c-4bbf-84aa-3ce48d0288c6" />
<img width="564" height="552" alt="Screenshot 2026-03-18 181057" src="https://github.com/user-attachments/assets/c0565e7d-e020-4f80-83ba-d650ef5e7f81" />
<img width="555" height="552" alt="Screenshot 2026-03-18 181223" src="https://github.com/user-attachments/assets/a90af3eb-051c-432f-a053-0fdcf98dc94e" />
<img width="606" height="252" alt="Screenshot 2026-03-18 181238" src="https://github.com/user-attachments/assets/1034aede-49fb-418d-9846-2f19352922e3" />
<img width="691" height="248" alt="Screenshot 2026-03-18 181302" src="https://github.com/user-attachments/assets/0b3aefbe-3106-492e-a120-9ca8645b5826" />
<img width="977" height="761" alt="Screenshot 2026-03-18 181354" src="https://github.com/user-attachments/assets/bba9c69c-3420-48a5-b8b7-eea1e28646c5" />
<img width="664" height="766" alt="Screenshot 2026-03-18 181505" src="https://github.com/user-attachments/assets/9fb841df-7487-4c2f-b754-655f5a36cd27" />
<img width="1002" height="298" alt="Screenshot 2026-03-18 181536" src="https://github.com/user-attachments/assets/7733d518-76b2-4d82-ab8f-916dbf4bab63" />

# Bravo vous avez accès au serveur depuis votre poste de travail
<img width="1110" height="406" alt="Capture d&#39;écran 2026-03-18 182008" src="https://github.com/user-attachments/assets/b729cb2b-811c-4948-96cb-79d4ab0a8748" />





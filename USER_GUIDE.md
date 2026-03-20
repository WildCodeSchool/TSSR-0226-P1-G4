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

## Étape 4 — Générez un mot de passe niveau ultra sécurisé 256 bits

&nbsp;

Cliquez sur "Tools" et sélectionnez "Generate Password".

&nbsp;

<img width="870" height="633" alt="Screenshot 2026-03-18 180143" src="https://github.com/user-attachments/assets/94e8eb1e-cf06-417e-806d-f616f941ba81" />

&nbsp;

Dans le menu déroulant : "Profile" sélectinnez "Hex-Key -256-Bit (built-in).

&nbsp;

<img width="650" height="706" alt="Screenshot 2026-03-18 180804" src="https://github.com/user-attachments/assets/87e45d8d-b9e8-4c56-8251-07430138d1ef" />

&nbsp;

## Étape 5 — Sélectionnez une clef puis faites un clic droit puis cliquez sur "Edit" pour personnaliser le nom de votre clef.

&nbsp;

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


&nbsp;


<img width="1185" height="635" alt="Screenshot 2026-03-19 101113" src="https://github.com/user-attachments/assets/04f047ed-451c-412f-8a88-d26e78791db0" />

&nbsp;


<img width="822" height="605" alt="Screenshot 2026-03-19 101202" src="https://github.com/user-attachments/assets/4d550865-2991-4c7b-af07-7ac6f9919184" />

&nbsp;

<img width="548" height="415" alt="Screenshot 2026-03-19 101244" src="https://github.com/user-attachments/assets/bf7b8f42-8c91-4454-84cc-39d0c2a5e06e" />


&nbsp;


<img width="2082" height="256" alt="Screenshot 2026-03-19 101358" src="https://github.com/user-attachments/assets/8e7a9454-7f45-410c-805c-933d557bd004" />

&nbsp;

<img width="706" height="399" alt="Screenshot 2026-03-19 101724" src="https://github.com/user-attachments/assets/700fcbe2-c41c-4134-a5b4-2ec005a491f9" />


&nbsp;

<img width="1022" height="402" alt="Screenshot 2026-03-19 101745" src="https://github.com/user-attachments/assets/9aaa332a-aada-498b-b46f-4ef13e5cd7fa" />


&nbsp;

<img width="780" height="528" alt="Screenshot 2026-03-19 101946" src="https://github.com/user-attachments/assets/7d944f9f-cbd7-49f5-977a-463138fc6764" />

&nbsp;


<img width="402" height="255" alt="Screenshot 2026-03-19 102233" src="https://github.com/user-attachments/assets/4220b308-1353-4a1a-a1ce-4ddeb5977812" />

&nbsp;


<img width="783" height="527" alt="Screenshot 2026-03-19 102459" src="https://github.com/user-attachments/assets/d3cd0594-7206-4da6-b675-461ac9a564e6" />

&nbsp;


<img width="1342" height="753" alt="Screenshot 2026-03-19 102757" src="https://github.com/user-attachments/assets/99e76f36-a38b-4d11-be03-bb24ddeab87a" />

&nbsp;

<img width="1346" height="754" alt="Screenshot 2026-03-19 102826" src="https://github.com/user-attachments/assets/fdb9a5c1-18b5-49af-a936-d7e7aac79e96" />

&nbsp;

<img width="1339" height="753" alt="Screenshot 2026-03-19 103039" src="https://github.com/user-attachments/assets/18fc204c-220f-4295-bc1f-08feb8069d51" />

&nbsp;

# Bravo vous avez accès au serveur depuis votre poste de travail

&nbsp;
<img width="1110" height="406" alt="Capture d&#39;écran 2026-03-18 182008" src="https://github.com/user-attachments/assets/b729cb2b-811c-4948-96cb-79d4ab0a8748" />





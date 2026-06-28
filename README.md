# Projet Relais FPV Video-Radio  <img width="100" height="100" alt="image" src="https://github.com/user-attachments/assets/776024e2-1432-40de-8bd1-c0caff72386b" /> <img width="100" height="100" alt="image" src="https://github.com/user-attachments/assets/103ca738-9ef7-4062-9f4e-e25c367a501c" />



Ici vous trouve manuel d'utilisation et montage de composants puis le model **.stl**, le relais etait fabrique par **CPL Grib du 2REP**



### C'est qua au interieur projet:
* **Manuel de montage Relais fpv.pdf** - Instruction complete comment faire Montage/Parametrage/Composants
* **BOITE RELAIS.stl** - Le boite principal de relais
* **COUVERCLE RELAIS.stl** - Fermeture pour boite
* **vrx adapt 1 antenne.stl** - Adaptation/fixation du VRX au Boite relais (evite que VRX tombe)
* **vrx adapt 2 antenne.stl** - Adaptation/fixation du VRX au Boite relais (evite que VRX tombe)



### Comment telecharger📥:
*  **Telecharger direct au github⚡**:Appuie sur link pour telecharger tout le fichier [https://github.com/ivanopolon/Relais-FPV-Video-et-Radio/archive/refs/heads/main.zip]
*  **Deuxieme link Google Drive** : [https://drive.google.com/drive/folders/1ycLJLeQRHloeQPtYHDW72jciS7_rBkLo?usp=sharing]


### 💡Ce projet est ouvert a toutes les proposition d'amelioration! Si vous avez de idees pour optimiser les modeles, ajouter des fonctionnalites ou adapter les pieces pour autre configuration, votre aide est la bienvenue

**Comment participer🤝:**
  * **Proposer une idee:** Ouvrez un **"Issue"** pour discuter d'une modification ou d'une amelioration (dimensions, design, placement des composants).
  * **Partager vos modifications:** Si vous avez deja modifier un fichier STL de votre cote, n'hesitez pas a soumettre une **"Pull Request"**.
  * **Signaler un probleme:** Si vous remarquez un defaut d'impression ou un problemme d'ajustement sur le pieces, merci de le signaler dans l'onglet **Issues**
  


### Contacts 📬 
* **Email:** ivan.grib.2003@gmail.com
* **Telegram:** [👉 (https://t.me/Manuel_Gorbatiuc) 👈]
* **Disscusions:** Cree un theme dans onglets **"Disscusions"** pour communique de futurs et votre proposition soit problemme

### Conseils du impression 3D
* **Boite relais et couvercle:**
     *  **Material:** PETG soit PLA
     *  **Remplisage:** 20 a 30% gyroid
     *  **Supports:** Arbreuse (fait tourner model boite relais a 180 en **Y** pour que partie haut du relais etre en bas pendant impression)

 * **Vrx adapteur:**
     *  **Material:** TPU
     *  **Remplisage:** 15% Standart
     *  **Supports:** NON


### Principe de fonctionnement relais Video + Radio

Dans le contexte actuel de l'utilisation des drones (notamment les drones FPV kamikaze), la portée du signal se deminuer à une limite physique majeure : 
* **Zone montagneuses⛰️**
* **Zone forestieres et boisees dense🌳**
* **Environnement urbains**
* **Et tout le obstacle naturel**

Les signaux radio (comme l'ExpressLRS, Crossfire) et les Flux vidéo de differents frequances se coupent dès que le drone passe derrière l'obstacle (perte de la ligne de visée directe ou Line of Sight). 
Quelle que soit la puissance d'émission utilisée (même avec plusieurs Watts), la présence d'une masse physique bloque la reseau, entraînant une perte de contrôle et flux video immédiate.

### 💡 La Solution : Le Relais Embarqué sur Drone Porteur/(Observateur meme temps)
Pour surmonter tout le obstacle, ce projet propose une architecture de retransmission mobile. L'idée est de déployer un module de relais radio et vidéo fixé et allimenter sur un **Drone porteur** (drone mère). 

* **Rôle du drone porteur:** Placé en altitude stratégique, il sert de station relais volante et maintient une liaison parfaite entre l'opérateur au sol et le drone d'action. En meme temps faire observation
* **Fonctionnement Relais:** Le boîtier reçoit en temps réel les commandes de l'opérateur et le flux vidéo du drone d'attaque, puis les retransmet instantanément d'un point à un autre en contournant le relief.
* **Drone kamikaze:** Franchir le mouvement de terain et obstacle puis arrive a son point distribuie son perte signal

Grâce à cette liaison aérienne déportée, le drone peut accomplir sa mission avec succès derrière des obstacles topographiques complexes, garantissant la continuité du signal vidéo et radio jusqu'à l'objectif, peu importent les difficultés du terrain.














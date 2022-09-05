# HA_RFPlayer

Composant/intégration personnalisé RFPlayer pour Home assistant

## Installation

Copiez le dossier `custom_component/rfplayer` dans votre répertoire de configuration..

Accédez à l'interface utilisateur Home-Assistant, Intégrations de configuration, bouton (+ Ajouter une intégration) et recherchez GCE RFPlayer

Il est possible de faire l'intégration par HACS, avec un ajout de dêpot personnalisé 

[Dépôt]()

https://github.com/Doubledom45/HA-Rfplayer-Beta

[Catégorie]()

Intégration

![image](https://user-images.githubusercontent.com/97252459/188435563-2153b448-7938-4092-a3b6-7ab35179827d.png)

Puis [Ajouter]()

Si ok, repasser sur intégration , le nouveau dépôt devrait être présent !
![image](https://user-images.githubusercontent.com/97252459/188435950-d9fb45a9-3370-43c5-9a19-13ef8f51b0f3.png)
Cliquer sur cette intégration
![image](https://user-images.githubusercontent.com/97252459/188436224-ab860744-a7fa-4a4a-8468-91de45c76ab9.png)
Puis sur [Téléchargé]()

![image](https://user-images.githubusercontent.com/97252459/188436474-e8deb12e-3760-4bf1-8c23-63ddcb65fcb4.png)

Confirmer le téléchargement

Il faut redémarrer HA !

![image](https://user-images.githubusercontent.com/97252459/188436987-437042ac-1a0b-49ad-961e-29ffee15c601.png)

![image](https://user-images.githubusercontent.com/97252459/188436881-a33c2a2c-b461-4c27-8219-9cbcc506c980.png)




Sélectionnez le périphérique USB dans la liste et validez.

## Usage

Les capteurs sont créés automatiquement si vous l'activez lors de l'installation ou sur le bouton d'option (menu Intégration)

Vous pouvez utiliser le service `rfplayer.send_command` pour envoyer des commandes à vos appareils et ajouter l'appareil en tant que nouvelle entité de commutateur.

## Credits
Version Béta, pour remonter entité correctement !
Voir https://github.com/gce-electronics/HA_RFPlayer/issues/10#issuecomment-1126559421

Pour la partie Jamming Alerte voir https://github.com/gce-electronics/HA_RFPlayer/issues/3#issuecomment-1126729241

En attente de test pour version GCE

forked from gce-electronics/HA_RFPlayer

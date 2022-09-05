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

![image](https://user-images.githubusercontent.com/97252459/188452103-0324079f-eb49-4c52-bbda-b3310e009611.png)

Puis [Ajouter]()

Si ok, repasser sur intégration , le nouveau dépôt devrait être présent !

![image](https://user-images.githubusercontent.com/97252459/188453031-852a7f38-d30e-4d92-a6ee-c481b96b5ecf.png)

Cliquer sur cette intégration

Puis sur [Téléchargé]()

![image](https://user-images.githubusercontent.com/97252459/188436474-e8deb12e-3760-4bf1-8c23-63ddcb65fcb4.png)

Confirmer le téléchargement

Il faut redémarrer HA !

![image](https://user-images.githubusercontent.com/97252459/188436987-437042ac-1a0b-49ad-961e-29ffee15c601.png)

![image](https://user-images.githubusercontent.com/97252459/188436881-a33c2a2c-b461-4c27-8219-9cbcc506c980.png)

Aprés redémarrage

Passer sur Paramètres

Appareils et services

Cliquer sur
![image](https://user-images.githubusercontent.com/97252459/188457665-35314cf4-fb1a-4e07-ae04-70a864da2a6c.png)

Rechercher intégration [rfplayer]()

![image](https://user-images.githubusercontent.com/97252459/188458256-7a6cd0a1-25c0-489e-88a2-79d4824efac0.png)

Sélectionnez le périphérique USB dans la liste et validez.

![image](https://user-images.githubusercontent.com/97252459/188458404-cbe00813-e6b5-4903-bc55-b4ede158fe4a.png)


## Usage

Les capteurs sont créés automatiquement si vous l'activez lors de l'installation ou sur le bouton d'option (menu Intégration)

Vous pouvez utiliser le service `rfplayer.send_command` pour envoyer des commandes à vos appareils et ajouter l'appareil en tant que nouvelle entité de commutateur.

## Credits
Version Béta, pour remonter entité correctement !
Voir https://github.com/gce-electronics/HA_RFPlayer/issues/10#issuecomment-1126559421

Pour la partie Jamming Alerte voir https://github.com/gce-electronics/HA_RFPlayer/issues/3#issuecomment-1126729241

En attente de test pour version GCE

forked from gce-electronics/HA_RFPlayer

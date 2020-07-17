# Communication

Tous les appareils dinotec basés sur dinotecNET+, équipés d'un écran tactile, peuvent être raccordés à **dinoRemote**.
La communication avec le serveur dinoRemote a lieu au moyen d'un tunnel VPN crypté, via le protocole **OpenVPN**.
Le **boîtier dinoRemote** est requis pour la création du tunnel VPN. Ce dernier utilise l'accès Internet local pour transmettre l'ensemble des paquets de données de l'appareil dinotecNET+, de manière cryptée, au serveur dinoRemote.

Le raccordement du boîtier dinoRemote (ci-après **dRB**) est simple :
Raccordez le câble réseau du routeur DSL au port **WAN** du dRB. Le panneau de commande (OP57, etc.) de l'installation dinotecNET+ est raccordé au port **LAN**.

![image alt text](../assets/cable.png)
  
***

Dès que le dRB est alimenté en courant et connecté à Internet, le voyant VPN sur le boîtier s'allume brièvement. Cela indique que la connexion à notre serveur dinoRemore a été effectuée avec succès.
Dans le cas contraire, vous pouvez chercher la solution dans le paragraphe Élimination des défauts. 
![image alt text](../assets/vpn.jpg)  
***

# Connexion UMTS

Le dRB peut également être raccordé à l'appareil dinoRemote via le réseau mobile. Toutefois, nous recommandons de toujours utiliser la variante stable via DSL. 
Pour une connexion par UMTS, le modem UMTS disponible en option ainsi qu'une carte SIM avec forfait de données (min. 1 Go/mois) est requise. La carte SIM doit être mise à disposition par l'exploitant. 
dinotec peut se charger de la configuration du modem avant la livraison. Il suffit pour cela de nous communiquer l'APN et le fournisseur. Vous avez également la possibilité de nous envoyer la carte déjà activée et vous recevrez votre boîtier entièrement configuré. 
**Important :** le PIN de la carte SIM doit impérativement être désactivé !


***

# Élimination de défauts

** Le voyant VPN est éteint **

+ Le routeur DSL doit povoir attribuer une adresse IP par DHCP (si cela s'avère impossible pour des raisons techniques, veuillez vous adresser à notre assistance).
+ Le tunnel VPN est établi via le port standard OpenVPN 1194. Veuillez vous assurer qu'il n'est pas bloqué par un pare-feu.
+ N'utilisez pas de câble réseau non blindé très long
+ N'utilisez pas d'adaptateur Wi-Fi ou d'adaptateur Powerline
+ Vérifiez que le câblage est correct
+ La transmission de données est trop lente (principalement avec UMTS)

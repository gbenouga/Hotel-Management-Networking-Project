Conception et Mise en œuvre d'un Réseau pour un Système Hôtelier (Projet #3)
Étude de cas et exigences du Projet #3

Dans le cadre de votre projet de fin d'année en réseautique, vous êtes chargé de concevoir et de mettre en œuvre le réseau du Vic Modern Hotel. L'hôtel comprend trois étages : au premier étage se trouvent trois départements (Réception, Magasin et Logistique), au deuxième étage trois départements (Finance, RH et Ventes/Marketing), tandis que le troisième étage abrite l'IT et l'Administration. Voici les considérations pour la conception et la mise en œuvre :

    Trois routeurs doivent connecter chaque étage (tous placés dans la salle des serveurs du département IT).

    Tous les routeurs doivent être connectés entre eux à l'aide de câbles série DCE.   

    Le réseau entre les routeurs doit utiliser les plages d'adresses 10.10.10.0/30, 10.10.10.4/30 et 10.10.10.8/30.

    Chaque étage doit avoir un commutateur (placé dans l'étage correspondant).

    Chaque étage doit avoir des réseaux Wi-Fi connectés aux ordinateurs portables et aux téléphones.

    Chaque département doit disposer d'une imprimante.

    Chaque département doit être dans un VLAN différent avec les détails suivants :

    1er étage :
        Réception - VLAN 80, Réseau 192.168.8.0/24
        Magasin - VLAN 70, Réseau 192.168.7.0/24
        Logistique - VLAN 60, Réseau 192.168.6.0/24

    2ème étage :
        Finance - VLAN 50, Réseau 192.168.5.0/24
        RH - VLAN 40, Réseau 192.168.4.0/24
        Ventes - VLAN 30, Réseau 192.168.3.0/24

    3ème étage :
        Administration - VLAN 20, Réseau 192.168.2.0/24
        IT - VLAN 10, Réseau 192.168.1.0/24

    Utilisez OSPF comme protocole de routage pour annoncer les routes.

    Tous les dispositifs du réseau doivent obtenir une adresse IP dynamiquement avec le routeur configuré en tant que serveur DHCP.

    Tous les dispositifs du réseau doivent pouvoir communiquer entre eux.

    Configurez SSH sur tous les routeurs pour l'accès à distance sécurisé.

    Dans le département IT, ajoutez un PC appelé Test-PC au port fa0/1 et utilisez-le pour tester l'accès à distance.

    Configurez la sécurité des ports sur le commutateur du département IT pour permettre uniquement à Test-PC d'accéder au port fa0/1 (utilisez la méthode sticky pour obtenir l'adresse MAC avec un mode de violation de fermeture).

Technologies mises en œuvre

    Création d'une topologie réseau en utilisant Cisco Packet Tracer.
    Conception hiérarchique du réseau.
    Connexion des dispositifs réseau avec le câblage approprié.
    Création de VLANs et attribution des numéros de ports VLAN.
    Subnetting et adressage IP.
    Configuration du routage inter-VLAN (Router on a stick).
    Configuration du serveur DHCP (routeur en tant que serveur DHCP).
    Configuration de SSH pour un accès à distance sécurisé.
    Configuration de la sécurité des ports ou Port-Security sur les commutateurs.
    Configuration du réseau WLAN ou sans fil (point d'accès Cisco).
    Configurations des dispositifs hôtes.
    Test et vérification de la communication réseau.

Topologie du réseau créée
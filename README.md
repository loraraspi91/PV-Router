# Smart PV-Router (Zero Injection)
> Format compact DIN (5 in 1) + RTC/Gradation

Routeur Photovoltaïque, Delesteur de Puissance, Fonction Jour/Nuit, Thermostat/Temperature et Suivi de la production (options)
> _Si vous voulez le votre, contactez moi:_ pvrouter@gmail.com


01/2025 *** NOUVEAU: Module EVSE-Pilot: Router sur voiture Electrique
- Nouveau module permettant au Smart PV-Router de piloter <b>VOTRE</b> wallbox
- Charge manuelle, Charge automatique (routage avec complément la nuit), Priorité au Ballon.
- Fonction delestage pour éviter de dépasser votre abonnement EDF.
- Compatible avec toutes les wallbox
- Plus d'information, page github <b>Smart EV-Pilot</b> : https://github.com/loraraspi91/EV-Pilot/tree/main
<img src="https://github.com/loraraspi91/PV-Router/blob/main/routeur.jpg" alt="Smart PV-Router" width="360" height="360">
<img src="https://github.com/loraraspi91/PV-Router/blob/main/coffret_ferme_web.jpg" alt="Smart PV-Router" width="220" height="360">

11/2024 *** Version Coffret CE, facile à installer:
- Simple et pré-configuré, branchez 5 fils, connectez le à votre WiFi (ou pas) et optimisez votre production.
- Si connecté au WiFi: suivez la performance de votre installation via internet en temps-réel.
- Existe en version 12 modules
<img src="https://github.com/loraraspi91/PV-Router/blob/main/Coffret8_2.jpg" alt="Smart PV-Router" width="361" height="360">

07/2024 *** Version Commerciale certifié CE, made in France :
> infos & Commandes : contact@smartelectromation.com
<img src="https://github.com/loraraspi91/PV-Router/blob/main/Smart_PVRouter.jpg" alt="Smart PV-Router" width="322" height="450">

06/2024 *** Module distant de mesure (linky) WiFi monophasé
- Permet de prendre les mesures sur un linky (ou tableau principal) loin de votre chauffe-eau
- Evite de passer des cables longs et disgracieux dans la maison pour relier le Router au linky.
- Mettez le module dans le tableau principal et le routeur au plus près ude votre chauffe-eau
<img src="https://github.com/loraraspi91/PV-Router/blob/main/Distant_Wifi-300x300.jpg" alt="Mesure WiFi Monophasé" width="322" height="450">


05/2024 *** 2 nouvelles fonctionnalités pour le PV-Router:
- Fonction "Boost": Relancer la chauffe de votre chauffe-eau en appuyant sur le bouton "boost". Ce bouton remplace l'interrupteur On/Off.
- Fonction "Mémorisation": Partez en vacances tranquille en coupant box & WiFi; le PV-Router mémorise ses données jusqu'à 90 jours et les restitura au serveur à votre retour.

04/2024 *** Le PV-Router devient compatible réseau Tri-Phasé en s'interconnectant avec le Shelly 3EM

<img src="https://github.com/loraraspi91/PV-Router/blob/main/Shelly3EM-2.jpg" alt="Shelly3EM" width="450" height="300">

03/2024 *** Nouveau compagnon: Node Battery permet de monitorer la charge/décharge de la batterie de l'onduleur. 
<img src="https://github.com/loraraspi91/PV-Router/blob/main/Battery.jpg" alt="Module PV Battery" width="220" height="300">

Permet de rendre compatible le PV-Router avec les onduleurs hybrides en priorisant le routage dans le cumulus et évitant de décharger les batteries dans le cumulus (à cause de la rapidité de routage par rapport à l'onduleur).

11/2023 *** Monitoring dynamique du PV-Router à distance (PC/Tablette/smartphone): Permet de suivre votre PV-Router, votre installation et votre production

05/2023 *** Nouveau compagnon: Node WiFi "Monitoring Solaire" pour suivre votre production si votre onduleur est loin de votre PV-Router

02/2023 *** Nouveau Design (cf photo ci-dessous) avec les mêmes fonctionalités.

11/2022 *** NOUVELLE Fonctionalité: Gestion automatique de la destruction des Légionnelles en mode nuit.

10/2022 *** NOUVEAUTE: Petit compagnon: le Node WiFi Temperature, Utile lorsque votre ballon est trop loin du PV-Router
> Remplace la sonde de température filaire si votre ballon est trop éloigné

05/2022*** Désormais le PV-Router dispose de 2 sorties en mode gradation (une via un SSR et l'autre interne). 
Sa sortie interne peut piloter une charge selfique (typiquement un moteur, un contacteur etc...) ou être remplacer (option) par un 2ème SSR.

> **_Video_** Présentation et revue du PV-Router (en mode gradateur) par Jean-Lou: https://youtu.be/uTjck2MogZk 

> **_Video_** PV-Router en action avec gradateur : https://youtu.be/Zar5hZ-N06U 
* PV-Router: Système de suivi et de monitoring à distance:
<img src="https://github.com/loraraspi91/PV-Router/blob/main/Monitoring.png" alt="PV-Router - Monoriting/suivi" width="756" height="472">

* PV-Router: Nouveau Design (avec fonction température & gestion des légionnelles):
<img src="https://github.com/loraraspi91/PV-Router/blob/main/PV-Router-NewDesign.jpg" alt="PV-Router - Nouveau Design" width="367" height="393">
* Petit compagnon (si besoin): Le PV-Node Monitoring (WiFi)
<img src="https://github.com/loraraspi91/PV-Router/blob/main/NodeMonitor.jpg" alt="PV-Router - Nouvelle Version 2" width="400" height="300">
* PV-Router: Ancien Design:
<img src="https://github.com/loraraspi91/PV-Router/blob/main/version21.jpg" alt="PV-Router - Ancien Design" width="550" height="393">
* Son petit compagnon (si besoin): Le PV-Node Temperature (WiFi)
<img src="https://github.com/loraraspi91/PV-Router/blob/main/PV_Node_Temp2.jpg" alt="PV-Router - Nouvelle Version 2" width="300" height="300">
Routeur connecté (WiFi)/(MQTT) et API REST. 
--Ce module PV-Router vous permet de router (Fonction routeur solaire) directement votre production électrique solaire sur 2 équipements distincts, vous permettant ainsi d’éviter d’injecter cette production dans le réseau de votre fournisseur d’électricité. Il vous permet aussi d’économiser l’électricité que vous auriez utilisée la nuit pour alimenter ces équipements. 
  * Note: uniquement la sortie 1 gère le mode gradation, la sortie 2 interne est en mode "tout ou rien". Possibilité de remplacer la 2ème sortie interne par un SSR externe en gradation.

--Fonction Jour/Nuit* : La 2ème fonction du PV-Router permet d’activer la sortie 1 aux heures de nuit et de la désactivée pendant la journée, où la fonction routeur reprend le relais. Cette fonction vous permet de compléter par exemple la montée en temperature de votre chauffe-eau si le soleil n'était pas au rendez-vous dans la journée. 
* L'option RTC est nécessaire lorsque le PV-Router ne peut être connecté au WiFi, en effet, celui-ci prend son heure sur internet par défaut. 

--Fonction Délesteur : La 3ème fonction du PV-Router, c’est une fonction de délestage. En effet, le PV-Router mesure en permanence la puissance à l’entrée de l’installation, lorsque cette puissance dépasse un seuil fixé par l’utilisateur, le PV-Router désactive ses entrées pour ne pas dépasser ce seuil fixé. Cette fonction est utile, si vous souhaitez souscrire une puissance limitée auprès de votre fournisseur tout en évitant des dépassements. Cette fonction vous permet ainsi de diminuer vos frais d’abonnement et le prix du KwH facturés par votre fournisseur d’électricité.

--Fonction Thermostat : Permet de limiter la remontée en température du chauffe-eau limitant d'autant la consomation d'électricité. Arrivée à température, le PV-Router ne maintient pas la température, toujours pour économiser de l'électricité et espérer que le soleil complétera à partir du réveil.

-- Fonction de suivi de production: Permet de suivre votre production solaire. Pour ce faire, le PV-Router est équipé d'un pince amperemetrique supplémentaire ce qui lui permet de suivre et transmettre le suivi de la production au travers du protocole MQTT, de son API REST et son interface web.

Plus d'information sur l'ensemble des fonctionalités dans le guide d'installation (<a href="https://github.com/loraraspi91/PV-Router/blob/main/PV_Installation_configuration_V2.02.pdf">PV_Installation_configuration_V2.02.pdf</a>)

Routeur connecté (WiFi)/(MQTT), facilement connectable avec Home Assistant

Video Boot & Auto-Calibrations des sorties: https://youtu.be/g_4Lvs88GUc

Video PV-Router en action: https://youtu.be/Mwd3u_4tKyo

Contact: pvrouter@gmail.com

* Malgré ce qui est indiqué ci-dessous, un service après-vente est assuré (mise à jour logiciel, réparations, upgrade....). 

Copyright 2021-2023 Tous droits réservés

CE PRODUIT EST FOURNI PAR LES AUTEURS ET CONTRIBUTEURS « EN L’ETAT » SANS AUCUNE GARANTIE D’AUCUNE SORTE, EXPLICITE OU IMPLICITE, N’Y SOIT ATTACHEE, Y COMPRIS LES GARANTIES IMPLICITES DE CARACTERE COMMERCIAL OU D'ADAPTATION DANS UN BUT PARTICULIER. LES AUTEURS ET CONTRIBUTEURS NE PEUVENT EN AUCUN CAS ETRE TENUS POUR RESPONSABLES D’UN QUELCONQUE DOMMAGE DIRECT, INDIRECT, ACCESSOIRE, PARTICULIER, EXEMPLAIRE OU IMMATERIEL (Y COMPRIS, MAIS SANS S’Y LIMITER, L'ACQUISITION DE PRODUITS OU SERVICES DE SUBSTITUTION ; LA PERTE DE JOUISSANCE, DE DONNEES OU DE BENEFICES ; OU LES PERTES D'EXPLOITATION) QUELLES QU'EN SOIENT LES CAUSES ET QUEL QUE SOIT LE TYPE DE RESPONSABILITE, CONTRACTUELLE, SANS FAUTE OU FONDEE SUR UN DELIT CIVIL (Y COMPRIS PAR NEGLIGENCE OU POUR UNE AUTRE CAUSE) RESULTANT D'UNE MANIERE OU D'UNE AUTRE DE L'UTILISATION DE CE PRODUIT, MEME SI MENTION A ETE FAITE DE LA POSSIBILITE DE TELS DOMMAGES.


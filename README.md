# PV-Router Compact DIN (5 in 1) + RTC/Gradation
Routeur Photovoltaïque, Delesteur de Puissance, Fonction Jour/Nuit, Thermostat et Suivi de la production (options)

*** NOUVEAUTE: Désormais le PV-Router dispose de 2 sorties en mode gradation (une via un SSR et l'autre interne). 
Sa sortie interne peut piloter une charge selfique (typiquement un moteur, un contacteur etc...) ou être remplacer (option) par un 2ème SSR.

> **_Video_** Présentation et revue du PV-Router (en mode gradateur) par Jean-Lou: https://youtu.be/uTjck2MogZk 

> **_Video_** PV-Router en action avec gradateur : https://youtu.be/Zar5hZ-N06U 

* PV-Router: Nouvelle Version 2:
<img src="https://github.com/loraraspi91/PV-Router/blob/main/version21.jpg" alt="PV-Router - Nouvelle Version 2" width="579" height="393">
Routeur connecté (WiFi) et (MQTT). 
--Ce module PV-Router vous permet de router (Fonction routeur solaire) directement votre production électrique solaire sur 2 équipements distincts, vous permettant ainsi d’éviter d’injecter cette production dans le réseau de votre fournisseur d’électricité. Il vous permet aussi d’économiser l’électricité que vous auriez utilisée la nuit pour alimenter ces équipements. 
  * Note: uniquement la sortie 1 gère le mode gradation, la sortie 2 est en mode "tout ou rien".

--Fonction Jour/Nuit* : La 2ème fonction du PV-Router permet d’activer la sortie 1 aux heures de nuit et de la désactivée pendant la journée, où la fonction routeur reprend le relais. Cette fonction vous permet de compléter par exemple la montée en temperature de votre chauffe-eau si le soleil n'était pas au rendez-vous dans la journée. 
* L'option RTC est nécessaire lorsque le PV-Router ne peut être connecté au WiFi, en effet, celui-ci prend son heure sur internet par défaut. 

--Fonction Délesteur : La 3ème fonction du PV-Router, c’est une fonction de délestage. En effet, le PV-Router mesure en permanence la puissance à l’entrée de l’installation, lorsque cette puissance dépasse un seuil fixé par l’utilisateur, le PV-Router désactive ses entrées pour ne pas dépasser ce seuil fixé. Cette fonction est utile, si vous souhaitez souscrire une puissance limitée auprès de votre fournisseur tout en évitant des dépassements. Cette fonction vous permet ainsi de diminuer vos frais d’abonnement et le prix du KwH facturés par votre fournisseur d’électricité.

--Fonction Thermostat : Permet de limiter la remontée en température du chauffe-eau limitant d'autant la consomation d'électricité. Arrivée à température, le PV-Router ne maintient pas la température, toujours pour économiser de l'électricité et espérer que le soleil complétera à partir du réveil.

-- Fonction de suivi de production: Permet de suivre votre production solaire. Pour ce faire, le PV-Router est équipé d'un pince amperemetrique supplémentaire ce qui lui permet de suivre et transmettre le suivi de la production au travers du protocole MQTT, de son API REST et son interface web.

Plus d'information sur l'ensemble des fonctionalités dans le guide d'installation (<a href="https://github.com/loraraspi91/PV-Router/blob/main/PV_Installation_configuration_V2.02.pdf">PV_Installation_configuration_V2.02.pdf</a>)

Routeur connecté (WiFi) et (MQTT), facilement connectable avec Home Assistant

Video Boot & Auto-Calibrations des sorties: https://youtu.be/g_4Lvs88GUc

Video PV-Router en action: https://youtu.be/Mwd3u_4tKyo

Contact: pvrouter@gmail.com

* Malgré ce qui est indiqué ci-dessous, un service après-vente est assuré (mise à jour logiciel, réparations, upgrade....). 

Copyright 2021, Tous droits réservés

CE PRODUIT EST FOURNI PAR LES AUTEURS ET CONTRIBUTEURS « EN L’ETAT » SANS AUCUNE GARANTIE D’AUCUNE SORTE, EXPLICITE OU IMPLICITE, N’Y SOIT ATTACHEE, Y COMPRIS LES GARANTIES IMPLICITES DE CARACTERE COMMERCIAL OU D'ADAPTATION DANS UN BUT PARTICULIER. LES AUTEURS ET CONTRIBUTEURS NE PEUVENT EN AUCUN CAS ETRE TENUS POUR RESPONSABLES D’UN QUELCONQUE DOMMAGE DIRECT, INDIRECT, ACCESSOIRE, PARTICULIER, EXEMPLAIRE OU IMMATERIEL (Y COMPRIS, MAIS SANS S’Y LIMITER, L'ACQUISITION DE PRODUITS OU SERVICES DE SUBSTITUTION ; LA PERTE DE JOUISSANCE, DE DONNEES OU DE BENEFICES ; OU LES PERTES D'EXPLOITATION) QUELLES QU'EN SOIENT LES CAUSES ET QUEL QUE SOIT LE TYPE DE RESPONSABILITE, CONTRACTUELLE, SANS FAUTE OU FONDEE SUR UN DELIT CIVIL (Y COMPRIS PAR NEGLIGENCE OU POUR UNE AUTRE CAUSE) RESULTANT D'UNE MANIERE OU D'UNE AUTRE DE L'UTILISATION DE CE PRODUIT, MEME SI MENTION A ETE FAITE DE LA POSSIBILITE DE TELS DOMMAGES.


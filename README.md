# PV-Router Compact DIN (3 in 1) + RTC/Gradation
Routeur Photovoltaïque, Delesteur de Puissance et fonction Jour/Nuit

*** NOUVEAUTE: Le PV-Router peut disposer d'une horloge temps-réel (RTC) et sa sortie 1 peut piloter un SSR en mode gradateur (Dimmer). *** 


> **_Video_** Présentation et revue du PV-Router (en mode gradateur) par Jean-Lou: https://youtu.be/uTjck2MogZk 

> **_Video_** PV-Router en action avec gradateur : https://youtu.be/Zar5hZ-N06U 

<img src="https://github.com/loraraspi91/PV-Router/blob/main/version21.jpg" alt="PV-Router - Nouvelle Version 2" width="579" height="393">

Routeur connecté (WiFi) et (MQTT). 
--Ce module PV-Router vous permet de router (Fonction routeur solaire) directement votre production électrique solaire sur 2 équipements distincts, vous permettant ainsi d’éviter d’injecter cette production dans le réseau de votre fournisseur d’électricité. Il vous permet aussi d’économiser l’électricité que vous auriez utilisée la nuit pour alimenter ces équipements. 
  * Note: uniquement la sortie 1 gère le mode gradation, la sortie 2 est en mode "tout ou rien".

--Fonction Jour/Nuit* : La 2ème fonction du PV-Router permet d’activer la sortie 1 aux heures de nuit et de la désactivée pendant la journée, où la fonction routeur reprend le relais. Cette fonction vous permet de compléter par exemple la montée en temperature de votre chauffe-eau si le soleil n'était pas au rendez-vous dans la journée.
* L'option RTC est nécessaire lorsque le PV-Router ne peut être connecté au WiFi, en effet, celui-ci prend son heure sur internet par défaut. 

--Fonction Délesteur : La 3ème fonction du PV-Router, c’est une fonction de délestage. En effet, le PV-Router mesure en permanence la puissance à l’entrée de l’installation, lorsque cette puissance dépasse un seuil fixé par l’utilisateur, le PV-Router désactive ses entrées pour ne pas dépasser ce seuil fixé. Cette fonction est utile, si vous souhaitez souscrire une puissance limitée auprès de votre fournisseur tout en évitant des dépassements. Cette fonction vous permet ainsi de diminuer vos frais d’abonnement et le prix du KwH facturés par votre fournisseur d’électricité.

Plus d'information sur l'ensemble des fonctionalités dans le guide d'installation (PV_Installation_configuration_V1.1.pdf)

Routeur connecté (WiFi) et (MQTT), facilement connectable avec Home Assistant

Video Boot & Auto-Calibrations des sorties: https://youtu.be/g_4Lvs88GUc

Video PV-Router en action: https://youtu.be/Mwd3u_4tKyo

Contact: pvrouter@gmail.com


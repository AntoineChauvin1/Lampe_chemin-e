# Lampe_cheminee
Lampe de cheminée

Plafonnier constitué de 3 planches de bois.
Les planchers de bois seront espacées par des cubes de bois pour pouvoir constituer 3 etages

Chaque planche de bois sera fraisé pour accueillir des bandes de led.
L'eclairage sera indirect dirigé vers le haut.
2 types de bande de led vont cohabiter: 
Des leds blanches en 12V
Des led adressables en 5v

Le systeme comportera une batterie lithium 12v.

Fonctionnement

Le but est de garder fonctionnel l'interrupteur principal.

Quand l'interrupteur 220v est pressé, les led blanches doivent s'allumer progressivement, idéalement étage par étage.
Dans le meme temps, l'alimentation 220v/12v doit charger la batterie 12V à 80% de sa capacité.

Pour la partie led adressables
Elles doivent pouvoir etre gérées a partir de la batterie 12V.
La luminositée doit varier en fonction de la luminosité ambiante
Elle peut aussi etre déterminée dans home assistant (HA), ainsi que la couleur
Un micro detecte le bruit et active la lampe pour x minutes (paramétrable dans HA)
Des sequences de led doivent pouvoir etre choisie

Une sonde de température est intégrée pour remonter l'information dans HA
Une sortie permanante et une sortie commandée par relai est aussi paramétrable.

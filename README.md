# MultiOuvrants

Widget pour Jeedom permettant d'afficher une icône en fonction du pourcentage d'ouverture d'équipements tels que volets battants ou roulants, veluxs, rideaux, stores, portails, portes de garage, etc... (Info Numérique)

Le widget inclus d'office 17 types d'ouvrants différents dont 9 séries de volets, 3 séries de veluxs, 2 séries de rideaux et 1 série de garage, de portail et de store. Il est possible d'ajouter ses propres icônes.

<img src="/doc/visuels.jpg" alt="visuels"/>

Pour choisir le type de visuel à afficher, il faut ajouter un paramètre optionnel '<i><b>type</b></i>' avec pour valeur le nom de la série à afficher (par exemple: '<i>velux2</i>'). Par défaut c'est le visuel '<i>volet1</i>' qui s'affiche. 
La liste des différents ouvrants disponibles est inscrite au début du code:
<blockquote> <!-- volet1 // volet2 // volet3 // volet4 // volet5 // volet6// volet7 // volet 8 // volet9 // velux1 // velux2 // velux3 // rideau1 // rideau2 // store1 // portail1 // garage1 --> </blockquote>

Pour afficher le pourcentage d'ouverture sous l'icône de l'ouvrant, il faut ajouter un paramètre ayant pour nom: '<i><b>position</b></i>' <b>sans valeur</b> (champ vide).

Il est également possible de spécifier la hauteur et la largeur des icônes par l'ajout de paramètres optionnels "<i><b>hauteur</b></i>" & "<i><b>largeur</b></i>" ayant pour valeur la dimension souhaitée (par exemple: hauteur=120/largeur=90 -> icône de 120px*90px).
Par défaut les icônes font 95px*95px.

<img src="/doc/params.jpg" alt="parametres"/>

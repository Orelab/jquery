# Pour s'échauffer

Créer une page HTML contenant un champ INPUT, ainsi qu'une DIV nommée #cadre (dimension minimale 800x600)
et les boutons suivants : Créer, Supprimer, Détruire, Ecrire, Vider, Shake

Intégrez les scripts jquery.min.js et jquery-ui.min.js avec nodejs

- Le bouton *Créer* ajoute une DIV de taille 50x50 dans le #cadre.
  La couleur de cette nouvelle DIV est celle notée dans le champ INPUT
  (rouge, vert bleu, jaune, etc... si la couleur n'est pas reconnue, la DIV est jaune)
- Le bouton *Supprimer* détruit toutes les DIV de la couleur mentionnée dans le champ INPUT
- Le bouton *Détruire* supprime toutes les DIV contenues dans le #cadre..
- Le bouton *Ecrire* ajoute dans toutes les DIV contenues dans le #cadre le texte présent dans le INPUT.
- Le bouton *Vider* vide simplement l'ensemble des balises INPUT et DIV de leur contenu.
- Le bouton *Shake* secoue toutes les DIV 2 secondes

- Lorsqu'on clique sur une DIV rouge, elle... explose ! (mais quel effet !)
- Les DIV vertes deviennent bleues au survol de la souris.
- Les DIV jaunes deviennent rouge 3 secondes après avoir cliqué dessus
- Le double-clic sur un DIV affiche le nombre de DIV de la même couleur dans une popup modale
  (voir Dialog dans JqueryUI)


# Challenge à réaliser en jQuery

Dans la culture web, deux des pires choses à faire sont l'ajout d'éléments clignotants, et les sites
qui font tomber de la neige. Comme votre formateur ne souhaite pas faire de crise d'épilepsie,
faites tomber de la neige !

Petits rappels des règles élémentaires de physique de base :
- Les flocons viennent du ciel, et ont tendance à tomber au sol (!!)
- Ils peuvent louvoyer de gauche à droite en tombant
- Ils disparaissent quand on clique dessus, ou lorsqu'ils arrivent en bas de page


# Mode "difficile"

Quand on décrit un cercle autour d'un flocon avec la souris, celui-ci double de volume !


# Hint


https://github.com/Promo-Java-Montpellier/Programme/wiki/Js-&-jQuery#user-content-pourquoi-jquery

RTFM :
- https://api.jquery.com/
- https://jqueryui.com/

Pour modifier le DOM :
- .append()
- .remove()
- .empty()

Pour gérer les événements :
- .on()
- .delegate() : ne pas hésiter à solliciter le formateur pour un petit brief sur delegate()

Pour gérer les animations :
- .animate()
- .delay() 
- https://jqueryui.com/effect/

Boite de dialogue modale :
- https://jqueryui.com/dialog/#modal-confirmation



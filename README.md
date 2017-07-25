# FileShaker
a File + a shake = something

L'idée est d'automatiser au maximum la pratique de databending. L'inspiration du projet est venue de cet article : ["Voici ce qu'il se passe lorsque vous éditez vos photos comme de la musique"](https://creators.vice.com/fr/article/mgpv3a/heres-what-happens-when-you-edit-photos-like-music)

Cependant, nous somme vraiment intéressés par l'application de filtre destinés à un type de média sur un autre plutôt que le "glitching" où l'on retire ou ajoute au hasard des bytes dans un fichier.

Si on le peut il serait intéressant de pouvoir à terme chaîner ces traitements, on peut imaginer la chaîne suivante :

`film --> musique --> echo --> image --> sepia --> film`

Plus en détails:
`film --> musique --> echo (-->musique) --> image --> sepia (--> image) --> film`

What?
=====
Le but de jeu est de:
- charger un fichier, image, musique, film
- appliquer un filtre(shake)
- visualiser le resultat

Progress
========
- Step zero
 * definir une architecture
 * Recherches sur les méthodes manuelles de databending (principalement comment "tranformer" un média en un autre type de média et inversement). Voir ce [tutoriel](http://www.hellocatfood.com/databending-using-audacity/) et les résultats que l'on peut attendre [ici](https://questionsomething.wordpress.com/2012/07/26/databending-using-audacity-effects/)

- Step one
  * Charger et afficher/visualiser/diffuser un fichier
    * [ ] Image
    * [ ] Musique
    * [ ] Film

- Step two
  * Choisir des Shakes et trouver un moyen de les appliquer

- Step three
  * Rendre le tout user-fucking-friendly

Languages/libs
==============
- C++, Poo
- Libs
  * Image: none
  * Video: none
  * Musique: none
  * Fenetre: none

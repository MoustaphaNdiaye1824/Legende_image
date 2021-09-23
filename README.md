# Légender des images à partir de mots clés

Le but de ce projet est de construire un modèle qui légende des images données en entrée. On nous a donné une centaine d’images et leurs descriptions.

Dans un premier temps on a découpé le problème en trois parties. On a tout d’abord extrait quelques mots-clés de chaque légendes. On a ensuite utilisé un modèle qui associe à chaque image un ou plusieurs mots-clés.
A partir de ces mots clés on a généré du texte, qu’on a évalué avec le score BLEU.Le score BLEU permet de mesurer la ressemblance entre les légendes réelles et les légendes générées. Dans un second temps on a directement utilisé un modèle qui décrit les images.

### Auteur : Moustapha Ndiaye, Mohamed Dhmine & Kenza SKALLI FETTACHI

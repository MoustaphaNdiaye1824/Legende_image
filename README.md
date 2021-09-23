# Légender des images à partir de mots clés

Le but de ce projet est de construire un modèle qui légende des images données en entrée que l'on a fourni avec leurs descriptions.

Dans un premier temps nous avons découpé le problème en trois parties. Nous avons tout d’abord extrait quelques mots-clés de chaque légendes. Ensuite nous avons utilisé un modèle qui associe à chaque image un ou plusieurs mots-clés.
A partir de ces mots clés on a généré du texte, que nous avons évalué avec le score BLEU. Le score BLEU permet de mesurer la ressemblance entre les légendes réelles et les légendes générées. Dans un second temps, nous avons directement utilisé un modèle qui décrit les images.

##### Auteur : Moustapha Ndiaye, Mohamed Dhmine & Kenza SKALLI FETTACHI

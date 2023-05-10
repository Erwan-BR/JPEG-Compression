# Compression JPEG
## Objectif du TP
Afin d’étudier les différents modes de compression d’images, nous avons étudié la compression JPEG et j’ai codé les différentes étapes qui permettent de réaliser l’encodage et le décodage d’images.

## Mise en œuvre
Afin de réaliser ce TP, j’ai commencé par coder les fonctions permettant de réaliser les différentes étapes de la compression JPEG. Puis, j’ai commencé par encoder des images en noir et blanc : cela permettait de travailler sur une seule dimension et de vérifier que tout fonctionnait correctement.

Une fois ceci réalisé, j’ai codé l’encodage pour des images en couleurs et en chrominance.

## Résultats
Après avoir vérifié que la compression et la décompression étaient tout deux fonctionnels, j’ai fait des tracés de courbes afin de mettre en avant le taux de compression en fonction du facteur de qualité, et prouver ainsi qu’une image en chrominance était bien plus pratique pour obtenir un plus grand taux de compression - d’autant plus que la relation entre une image RGB et une image en chrominance est bijective.

Utilisation du code n2n du dépot https://github.com/NVlabs/noise2noise pour un projet étudiant

Par Valentin Andral et Valentin Sicard

Seul les résultats du eval ont été ajoutés.

Si vous voulez lancez l'entraîenement avec le modèle sur un dataset réduit, entrez la commande:
python config.py train --train-tfrecords=datasets/images.tfrecords --long-train=true --noise=(gaussian|poisson)
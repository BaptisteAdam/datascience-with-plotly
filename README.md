
Lorsque tous les fichiers sont dans le meme dossier, commencez par exécuter la commande 'python complete_csv.py' pour completer une fois pour toutes les données qui seront utilisées dans le dashboard. Ensuite, exécutez la commande 'python projet.py'pour afficher le dashboard.

Il n'est nécessaire d'exécuter complete_csv.py qu'une seule fois contrairement à projet.py qui devra etre éxécuté à chaque visualisation du dashboard.

A noter, dans le CSV d'origine, les lieux n'ont pas de coordonnées geographique, je suis donc allé les chercher avec l'API Nominatim. Par soucis de temps d'execution et de potentiel probleme de ban temporaire de l'API pour sur-utilisation de celle-ci, le programme utilise par defaut le fichier plan_b.py qui contiens les dites coordonnées pré-répupérées avec l'exact meme fonction présente dans le fichier complete_csv.py. Si vous voulez utiliser ce code pour vérifier son fonctionnement, décommentez la ligne 117 et commentez la ligne 118 de complete_csv.py puis recommencez les instructions ci-dessus.
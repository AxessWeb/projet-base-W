## Projet base W

Ce projet est la structure de base d'un projet W. Il permet d'utiliser le framework en tant que package et donc de le maintenir à jour plus facilement.

Pour l'utiliser, il suffit de le cloner et de le renommer. N'oubliez pas de mettre le fichier composer.json en remplacant les différentes données (name, description, authors).

####Spécifications
Ce projet nécessite :
* PHP: >= 5.5.9
* PHP extensions: mbstring, mysqli, intl, fileinfo
* MariaDB ou MySQL: >=5.x
* Server modules : composer
* Apache modules: rewrite, expires, header

####Installation
Utilisez `composer install -o` pour installer les dépendances nécessaires

Accédez ensuite à http://localhost/nom_de_mon_projet/public/check.php afin de vérifier que tout est fonctionnel.
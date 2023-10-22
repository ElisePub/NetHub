# NetHub

Développement d'un Site Web Forum.  
NetHub est une plateforme de discussion en ligne pour permettre à une communauté de partager des informations, échanger des idées et interagir autour de l'informatique.

### Pré-requis

Application testée sur un environnement Ubuntu 22.04.  
Symfony nécéssite l'utilisation d'une version PHP 8.1 ou superieur.

### Installation

Retrouvez la [documentation officielle](https://symfony.com/doc/current/setup.html)

**étape 1 - Installer Composer**  
Composer est un gestionnaire de dépendances pour PHP. Vous pouvez le télécharger et l'installer à partir de [getcomposer.org](https://getcomposer.org/download/).


_exemple_:  

_Depuis le dossier NetHub, executez la commande suivante :  
 ``php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"``_  
_puis pour vérifiez le programme d'installation_  
``php -r "if (hash_file('sha384', 'composer-setup.php') === 'e21205b207c3ff031906575712edab6f13eb0b361f2085f1f1237b7126d785e826a450292b6cfd1d64d92e6563bbde02') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"``.    

_Ensuite `php composer-setup.php` pour executer l'installeur_  
_et enfin `php -r "unlink('composer-setup.php');"` pour le supprimer._

**étape 2 - Installer les dépendances du projet**  
Executez ``composer install`` depuis le repertoire du projet. Cela installera toutes les dépendances listées dans le fichier composer.json.

## Démarrage

Executez la commande ``symfony serve`` pour démarrer le serveur ensuite rendez-vous à https://localhost:8000. Cliquer sur "accepter les risques et continuer" si le navigateur bloque la connexion.
Pour arrêter le serveur executez ``symfony server:stop``.

## Logiciel

* [Symfony 6.3.5](https://symfony.com/doc/current/index.html) - Framework PHP
* [PHP 8.1.2](https://www.php.net/) - Backend
* [Twig](https://twig.symfony.com/) - Frontend
* [SQLite 3](https://www.sqlite.org/index.html) - Database
* [Visual Studio Code](https://code.visualstudio.com/) - Editeur de textes


## Auteurs
* **Elise Pubert** _alias_ [@ElisePub](https://github.com/ElisePub)

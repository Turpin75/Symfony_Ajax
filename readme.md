# Codebase pour l'initiation à AJAX avec Symfony

# Installation
```
# On clone le dépot les bros !
git clone https://github.com/Turpin75/Symfony_Ajax.git

# On se déplace dans le dossier
cd symfony_ajax

# On installe les dépendances !
composer install

# On créé la base de données
php bin/console doctrine:database:create

# On exécute les migrations
php bin/console doctrine:migrations:migrate

# On exécute la fixture
php bin/console doctrine:fixtures:load --no-interaction

# On lance le serveur
php bin/console server:run
```

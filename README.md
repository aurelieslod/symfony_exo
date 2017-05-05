symfony_exo
===========

A Symfony project created on May 5, 2017, 12:28 pm.

First Test project Symfony

******************
ENTITY
Create entity :
php bin/console generate:doctrine:entity
  ->name entity : AppBundle:Your_entity_name
  ->name fields (type ex : string / integer / float)



*****************
DATABASE
Sync database with current mapping :
php bin/console doctrine:schema:create

Database validate :
php bin/console doctrine:schema:validate  

Database update :
php bin/console doctrine:schema:update --force

****************
BOWER + BOOTSTRAP

npm install -g bower
->Create file .bowerrc
-> File .bowerrc :
  {
    "directory": "web/assets/vendor/"
  }
-> bower install --save bootstrap
-> add this line in gitignore :
  /web/assets/vendor/

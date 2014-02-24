symfony-sonata
==============

Instalation
-----------

Lancer depuis le terminal les commandes suivantes :

    git clone https://github.com/DILL44/symfony-sonata
    php -r "readfile('https://getcomposer.org/installer');" | php`
pour charger le depot et composer 

    cd symfony-sonata/
    sudo php ../composer.phar update
pour charger les modules avec composer, al la fin il vous demandera les configuration de symfony
    
    sudo chown -R koalas:koalas *
    app/console cache:clear`
    chmod g+w app/logs/dev.log
pour générer les caches

    app/console doctrine:database:create
    app/console doctrine:schema:update
pour générer la base de données

# Sf-UnitTests
# commande pour tester
bin/phpunit --filter InvitationCodeTest
# commande pour charger les fixtures depuis l'env. de test
php bin/console doctrine:fixtures:load --env=test

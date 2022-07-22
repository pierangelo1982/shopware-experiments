one development:

(https://github.com/shopware/development)[https://github.com/shopware/development]


install

`./bin/setup`


start:

daemon
symfony server:start -d

symfony server:stop
 
symfony server:start


### create theme

NomeCreatoreNomeTemplate

`bin/console theme:create PierangeloBasicExampleTheme`

`bin/console plugin:refresh`

`bin/console plugin:install --activate PierangeloBasicExampleTheme`

`bin/console theme:change`

dopo eventuali modifiche al theme:

`bin/console theme:compile`

docker run --name docker-mysql -e MYSQL_ROOT_PASSWORD=password1234 -d mysql:5.7


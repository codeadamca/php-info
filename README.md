# php-info

When you're coding PHP, debugging can be difficult. By default when a PHP error occues your browser will display a `This pags isn't working` message. This message is not too helpful. 

<img src="https://github.com/codeadamca/php-info/blob/master/php-default-error.png?raw=true " width="300">

There are a handful of methods to have PHP display a much more descriptive error. Once we have adjusted the PHP `display_errors` server setting, error messages wil lbe much more helpful.

## MAMP/WAMP

If you are using a local server you will need to chagne your `php.ini` file. First you need to locate this file. Place the `phpinfo.php` file in your server root and test. It will list all of your PHP settings. 

Locate the `Loaded Configuration File` setting and not where the `php.ini` files is located. Mine is located in the `/Applications/MAMP/bin/php/php7.3.9/conf/php.ini` folder. Open this file, find the line that says `display_errors = Off` and change it to `display_errors = On`.

## PHP Hosting

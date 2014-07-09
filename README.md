Php Binary CQL (Composer Compatible)
============

Php implementation of the CQL binary protocol.  This project is a client that will allow queries to be sent using the binary protocol.

Required PHP Modules (not installed by default)
--------------------
iconv
mbstring
bcmath

Installing Via Composer
--------------------------------------
This package is not submitted to packagist but you can add it to your composer.json file using the following require and repository entries.

Add custom package to repositories section in composer.json
```javascript
"repositories": [
        {
            "type": "package",
            "package": {
                "name": "aloha/phpbinarycql",
                "version": "0.0.2",
                "source": {
                    "url": "https://github.com/aloha/phpbinarycql",
                    "type": "git",
                    "reference": "0.0.2"
                }
            }
        }
    ],
```
Add desired release to require block in composer.json
```javascript
"require": {
        "aloha/phpbinarycql" : "0.0.2"
	},
```

Update Composer or composer install if running for first time
```bash
composer update
```


Forked From
--------------------------------------
https://github.com/rmcfrazier/phpbinarycql


Additional Information
----------------------
- Walk through of simple_query.php - http://blog.robert.mcfrazier.com/getting-started-php-binary-cql-client/

Link: https://viblo.asia/p/build-a-simple-rest-api-in-php-924lJqrbZPM

INSTALL PHP AND COMPOSER
1. Install PHP
    https://windows.php.net/download
    Extract the downloaded file
    Copy the folder to C:\

2. Install Composer
    https://getcomposer.org/doc/00-intro.md#installation-windows
    Run Composer-Setup

3. Restart VScode

CREATE INI OF PROJECT
1. Create folder and file
    * name-project
        * src
        - composer.json
        - .env

2. Add to composer.json:
    {
        "require": {
            "vlucas/phpdotenv": "^2.4"
        },
        "autoload": {
            "psr-4": {
                "Src\\": "src/"
            }
        }
    }

3. Run composer install

4. 
 
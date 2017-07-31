# phpcamp
Creating to share the important stuff from a training camp

## Goals
 * HTTP Request / Response
 * Composer
 * SOLID Principles
 * OOP / MVC
 * Reusable Components / Framework

## Topics that were covered through the bootcamp
   
 ### Day 16
  * Installed phpunit/phpunit https://jtreminio.com/2013/03/unit-testing-tutorial-introduction-to-phpunit/
  * Installed twig/twig https://twig.symfony.com/doc/2.x/
  
  Still configuring... :(
  
 ### Day 15
  * Git
  * FQN
  * Reformat Code in phpStorm
  * PSR-2 Coding Style Guide http://www.php-fig.org/psr/psr-2/
  * PSR-4 Autoloading http://www.php-fig.org/psr/psr-4/
  * // TODO phpStorm recognizeable comment
  * Persistent layer -> Database
  * Design Patern - Adaptor
     * https://github.com/domnikl/DesignPatternsPHP
     * https://en.wikipedia.org/wiki/Design_Patterns
  
  ### Day 14
  * Classes
  * Static
  * Construct
  * call_user_func http://php.net/manual/en/function.call-user-func.php
  * SOLID https://en.wikipedia.org/wiki/SOLID_(object-oriented_design)
  * Dependency Container Injection
  * SemVer
  
  ### Day 13
  * Functions, Parameter types
  * assert http://php.net/manual/en/function.assert.php
  * shuffle http://php.net/manual/en/function.shuffle.php
  * array_slice http://php.net/manual/en/function.array-slice.php
  * Cyclomatic Complexity https://en.wikipedia.org/wiki/Cyclomatic_complexity
  * http_response_code http://php.net/manual/en/function.http-response-code.php
  * header http://php.net/manual/en/function.header.php
  
  ### Day 12
  * Started the common project. Link to git repository : https://github.com/alexniedreacn/bootcamp
  * Loops - for, do while, while, foreach
  * include, include_once, require, require_once
  * Null coalescing operator http://php.net/manual/en/migration70.new-features.php 
  * MVC - Model View Controller
  * Super Global Variables http://php.net/language.variables.superglobals
  
  ### Day 11
  * Intro to PHP (all the topics in the presentation slide https://www.slideshare.net/bradley.holt/introduction-to-php-5176251?qid=fc6cbf13-f883-470d-ad4a-f968b4194e52&v=&b=&from_search=1 )
  * Classes, Abstract classes & Interface

## Terminal Commands
  * `which php` - Shows the root directory of your system installed php
  * `brew tap homebrew/homebrew-php` - Updates all the package list for php available in brew
  * `brew search php7` - List down the package list for php7 in brew
  * `brew install php71` - installs php 7.1 using brew
  * `brew install php71-xdebug` - installs xdebug extention for php using brew
  * `cd ~` - Go to home directory
  * `nano .bash_profile` - Opens the file in nano
  * Copy **export PATH="$(brew --prefix homebrew/php/php71)/bin:$PATH"** to the file and save it. (Ctrl+X, Yes, Enter)
  * Open a new terminal and type `which php` - Should give the new directory path
  * `php -v` - Check the php version. Should be php 7.1
  * `brew install php71-intl` - Installs intl package
  * `brew install curl` - Installs curl
  
## PhpStrome Terminal Commands (Actually any terminal)
  * `php -S localhost:8080` - Starts the server at given url on given port
  * **Ctrl + C** - Stops the server
  * **Ctrl + D** - Exit from Terminal
  
## Composer Commands
  * Installing
    * Go inside your project directory
    * `php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"`
    * `php -r "if (hash_file('SHA384', 'composer-setup.php') === '669656bab3166a7aff8a7506b8cb2d1c292f042046c5a994c43155c0be6190fa0355160742ab2e1c88d40d5be660b410') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"`
    * `php composer-setup.php`
    * `php -r "unlink('composer-setup.php');"`
  * Setting up project
    * `php composer.phar init`
    * `php composer.phar install` - Need *composer.lock* to do this. It was created when initializing.
  * Adding up packages
    * `php composer.phar require packageName`
       * eg:
          * `php composer.phar require symfony/var-dumper --dev`
          * `php composer.phar require symfony/routing`
          * `php composer.phar require symfony/dependency-injection`
          * `php composer.phar require nikic/fast-route`
          * `php composer.phar require phpunit/phpunit`
          * `php composer.phar require twig/twig`
  
## Useful links
  * https://3v4l.org/
  * https://packagist.org/
  * http://phpfig.org/
  * http://www.phptherightway.com/
  * https://github.com/marcelgsantos/learning-oop-in-php
  * https://www.udemy.com/learn-php-5-and-7-this-way-to-rise-above-and-beyond-competition/ (Suggested by Arturs)
  * http://overapi.com/php (Suggested by Alvis)
  
## Tools
  * https://pastebin.com/
  * https://paste.ee/
  * https://paste.ofcode.org

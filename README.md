## PHP corpus

A collection of various PHP code.

Useful for PHP tools writers to get some insights on how "real-world" PHP code looks like.

## Installation

To clone this repository with all contents at once:

```bash
# This will take a while...
git clone --recurse-submodules  https://github.com/quasilyte/phpcorpus.git
```

If you already cloned phpcorpus without fetching submodules:

```bash
$ git submodule init

# This will take a while...
$ git submodule update
```

After this, you'll have all repositories cloned into [submodules/](submodules/), but that doesn't mean that all of them are ready to be executed or analyzer. Depending on your goals, you may need to run `composer install` for the project of interest so it downloads all its dependencies.

If you only care about the lightweight syntax analysis, downloading dependencies may not be required as it would only make your results worse due to the code duplication in `vendor/` directory (different corpus entries may depend on the same library, so you'll get multiple hits from the same library).

## Corpus contents

Only git repositories with open sources are included. We don't copy any code, but add repositories
to the git submodules of this repository.

> All lists are sorted alphabetically.

* Web frameworks:
  * [github.com/laravel/laravel](https://github.com/laravel/laravel)
  * [github.com/symfony/symfony](https://github.com/symfony/symfony)
  * [github.com/yiisoft/yii2](https://github.com/yiisoft/yii2)

* ORM:
  * [github.com/doctrine/orm](https://github.com/doctrine/orm)
  * [github.com/propelorm/Propel2](https://github.com/propelorm/Propel2)

* Templating systems:
  * [github.com/bobthecow/mustache.php](https://github.com/bobthecow/mustache.php)
  * [github.com/twigphp/Twig](https://github.com/twigphp/Twig)

* Libraries:
  * [github.com/VKCOM/vk-php-sdk](https://github.com/VKCOM/vk-php-sdk)
  * [github.com/brick/math](https://github.com/brick/math)
  * [github.com/guzzle/guzzle](https://github.com/guzzle/guzzle)
  * [github.com/markrogoyski/math-php](https://github.com/markrogoyski/math-php)
  * [github.com/nikic/PHP-Parser](https://github.com/nikic/PHP-Parser)
  * [github.com/ramsey/uuid](https://github.com/ramsey/uuid)

* Utilities:
  * [github.com/composer/composer](https://github.com/composer/composer)
  * [github.com/sebastianbergmann/phpunit](https://github.com/sebastianbergmann/phpunit)
  * [github.com/vimeo/psalm](https://github.com/vimeo/psalm)

* Platforms/CMS:
  * [github.com/WordPress/WordPress](https://github.com/WordPress/WordPress)
  * [github.com/drupal/drupal](https://github.com/drupal/drupal)
  * [github.com/joomla/joomla-cms](https://github.com/joomla/joomla-cms)
  * [github.com/moodle/moodle](https://github.com/moodle/moodle)
  * [github.com/phacility/phabricator](https://github.com/phacility/phabricator)

This list is not guaranteed to be append-only; some entries may be removed.

## License

This repository **does not** override the license of the code it can fetch via git submodules.

The MIT license applies for the actual repository contents.

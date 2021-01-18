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

## Corpus contents

Only git repositories with open sources are included. We don't copy any code, but add repositories
to the git submodules of this repository.

> All lists are sorted alphabetically.

* Web frameworks:
  * [github.com/laravel/laravel](https://github.com/laravel/laravel)
  * [github.com/symfony/symfony](https://github.com/symfony/symfony)
  * [github.com/yiisoft/yii2](https://github.com/yiisoft/yii2)

* Templating systems:
  * [github.com/bobthecow/mustache.php](https://github.com/bobthecow/mustache.php)
  * [github.com/twigphp/Twig](https://github.com/twigphp/Twig)

* Libraries:
  * [github.com/VKCOM/vk-php-sdk](https://github.com/VKCOM/vk-php-sdk.git)
  * [github.com/guzzle/guzzle](https://github.com/guzzle/guzzle)
  * [github.com/nikic/PHP-Parser](https://github.com/nikic/PHP-Parser.git)

* Utilities:
  * [github.com/composer/composer](https://github.com/composer/composer)
  * [github.com/sebastianbergmann/phpunit](https://github.com/sebastianbergmann/phpunit)
  * [github.com/vimeo/psalm](https://github.com/vimeo/psalm)

* Platforms/CMS:
  * [github.com/WordPress/WordPress](https://github.com/WordPress/WordPress)
  * [github.com/drupal/drupal](https://github.com/drupal/drupal.git)
  * [github.com/joomla/joomla-cms](https://github.com/joomla/joomla-cms.git)
  * [github.com/moodle/moodle](https://github.com/moodle/moodle)
  * [github.com/phacility/phabricator](https://github.com/phacility/phabricator.git)

This list is not guaranteed to be append-only; some entries may be removed.

## License

This repository **does not** override the license of the code it can fetch via git submodules.

The MIT license applies for the actual repository contents.

# TYPO3 CMS legacy package as Composer installation source

This repository shows how to use a TYPO3 CMS legacy package as Composer
installation source.

## Prerequisites

* [DDEV](https://github.com/drud/ddev/releases/latest)

or

* PHP 7.2
* [Composer](https://getcomposer.org/download/)

## Quick start

* `ddev start`
* `ddev exec prepare-source.sh`
* `ddev composer install`

or

* `bin/prepare-source.sh`
* `composer install`

The TYPO3 instance is now installed and ready to set up. Please see the core
repository in the `composer.json` and also `bin/prepare-source.sh`.

## License

This project is released under the terms of the [GNU GENERAL PUBLIC LICENSE](LICENSE)

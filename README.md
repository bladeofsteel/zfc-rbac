# ZfcRbac

[![Master Branch Build Status](https://secure.travis-ci.org/ZF-Commons/ZfcRbac.png?branch=master)](http://travis-ci.org/ZF-Commons/ZfcRbac)
[![Coverage Status](https://coveralls.io/repos/ZF-Commons/ZfcRbac/badge.png)](https://coveralls.io/r/ZF-Commons/ZfcRbac)
[![Latest Stable Version](https://poser.pugx.org/zf-commons/ZfcRbac/v/stable.png)](https://packagist.org/packages/zf-commons/ZfcRbac)
[![Latest Unstable Version](https://poser.pugx.org/zf-commons/ZfcRbac/v/unstable.png)](https://packagist.org/packages/zf-commons/ZfcRbac)
[![Scrutinizer Quality Score](https://scrutinizer-ci.com/g/ZF-Commons/ZfcRbac/badges/quality-score.png?s=0bf2b72bb233e93ba766cac36cc6dcb99b33acb5)](https://scrutinizer-ci.com/g/ZF-Commons/ZfcRbac/)
[![Total Downloads](https://poser.pugx.org/zf-commons/ZfcRbac/downloads.png)](https://packagist.org/packages/zf-commons/ZfcRbac)

ZfcRbac is an access control module for Zend Framework 2, based on the RBAC permission model.

## Requirements

- PHP 5.4 or higher
- [Rbac component](https://github.com/zf-fr/rbac): this is actually a prototype for the ZF3 Rbac component.
- [Zend Framework 2.2 or higher](http://www.github.com/zendframework/zf2)

> If you are looking for older version of ZfcRbac, please refer to the 0.2.x branch.
> If you are using ZfcRbac 1.0, please upgrade to 2.0.

## Optional

- [DoctrineModule](https://github.com/doctrine/DoctrineModule): if you want to use some built-in role and permission providers.
- [ZendDeveloperTools](https://github.com/zendframework/ZendDeveloperTools): if you want to have useful stats added to
the Zend Developer toolbar.

## Installation

ZfcRbac only officially supports installation through Composer. For Composer documentation, please refer to
[getcomposer.org](http://getcomposer.org/).

Install the module:

```sh
$ php composer.phar require zf-commons/zfc-rbac:~2.0
```

IMPORTANT: there is currently a problem with Packagist because I mess with the names. As a result, you couldn't download ZfcRbac this way. Until it's fixed (hopefully today or tomorrow), please specify "dev-develop" instead of 2.0 to fetch the branch 2.0. Sorry!

Enable the module by adding `ZfcRbac` key to your `application.config.php` file. Customize the module by copy-pasting
the `zfc_rbac.global.php.dist` file to your `config/autoload` folder.

## Documentation

The official documentation is available in the [/docs](/docs) folder.

You can also find some Doctrine entities in the [/data](/data) folder that will help you to more quickly take advantage
of ZfcRbac.

# Simple/project-name

[![Build Status](https://img.shields.io/travis/simpl-php/config.svg?style=flat-square)](https://travis-ci.org/simpl-php/config)

Skeleton for creating new simpl-php libraries.

## Installation

```bash
composer require simpl/project-name
```

## Basic Usage
```php
<?php
```

See <https://simpl-php.com/components/project-name> for full documentation.

## Testing

```bash
composer test
```

## Coding Standards
This library uses [PHP_CodeSniffer](http://www.squizlabs.com/php-codesniffer) to ensure coding standards are followed.

I have adopted the [PHP FIG PSR-2 Coding Standard](http://www.php-fig.org/psr/psr-2/) EXCEPT for the tabs vs spaces for indentation rule. PSR-2 says 4 spaces. I use tabs. No discussion.

To support indenting with tabs, I've defined a custom PSR-2 ruleset that extends the standard [PSR-2 ruleset used by PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer/blob/master/CodeSniffer/Standards/PSR2/ruleset.xml). You can find this ruleset in the root of this project at PSR2Tabs.xml


### Codesniffer

```bash
composer codensiffer
```

### Codefixer

```bash
composer codefixer
```
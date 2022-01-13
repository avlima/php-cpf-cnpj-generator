[![Packagist](https://img.shields.io/packagist/v/avlima/php-cpf-cnpj-generator.svg)](https://packagist.org/packages/avlima/php-cpf-cnpj-gerenator) 
[![PHP from Packagist](https://img.shields.io/packagist/php-v/avlima/php-cpf-cnpj-generator.svg?logo=php&logoColor=white)](https://packagist.org/packages/avlima/php-cpf-cnpj-generator)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/avlima/php-cpf-cnpj-generator/master/LICENSE)

# Brazilian document generator for PHP

#### [Star ⭐](https://github.com/avlima/php-cpf-cnpj-generator) repo to show suport 😊

## Installation

### Install Package
Require this package with composer:
```
composer require avlima/php-cpf-cnpj-generator
```

## Usage

Add the class `use Avlima\PhpCpfCnpjGerenator\Generator;` to your file:
```
Generator::cpf();
- output: 84255523037

Generator::cpf(true);
- output: 842.555.230-37

Generator::cnpj();
- output: 14905492000179

Generator::cnpj(true);
- output: 14.905.492/0001-79
```


## Thanks

```
## Support
Feel free to post your issues in the issues section.

## Credits
Developed by [Alberto Lima](https://github.com/avlima "Alberto Vieira de Lima")

## License
MIT

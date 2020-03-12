**ABANDONED! We decided to abandon the meta package because of inconsistencies in the version systems used by the PDF generation libraries. As it is up to the developers to define which PDF generation library is used in their code it should be configured as a direct dependency in their own composer.json file too.**

**Please remove this package from your composer.json and replace it by direct dependencies to [`setasign/fpdi`](https://packagist.org/packages/setasign/fpdi) and [`setasign/fpdf`](https://packagist.org/packages/setasign/fpdf).**

# FPDI-FPDF
A kind of metadata package for Composer with fixed dependencies for the latest versions of FPDI and FPDF.

## Installation with [Composer](https://packagist.org/packages/setasign/fpdi-fpdf)

```bash
$ composer require setasign/fpdi-fpdf:2.3
```

or you can include the following in your composer.json file:

```json
{
    "require": {
        "setasign/fpdi-fpdf": "^2.3"
    }
}
```

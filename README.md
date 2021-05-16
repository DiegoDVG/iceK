# icek Collection

[![Icestudio][icestudio-image]][icestudio-url]
![Version][version-image]

![](wiki/Logo/iceK-logo.png)

Working with Constant values
## Documentation
Find more information in the [WIKI page](https://github.com/FPGAwars/iceK/wiki)  


## Install

For installing and using this colection in Icestudio follow these steps:

* Download the collection: [stable](https://github.com/FPGAwars/iceK/archive/refs/tags/v0.1.0.zip) or [development](https://github.com/FPGAwars/iceK/archive/refs/heads/main.zip)
* Install the collection: *Tools > Collections > Add*
* Select the collection: *Select > Collection*

## Blocks
* **Bits**
  * bit-0
  * bit-1
  * generic
* **Bus**
  * **Bus-02**
    * generic
    * k-1
    * value-0
    * value-1
    * value-2
    * value-3
  * **Bus-03**
    * generic
    * value-0
    * value-1
    * value-2
    * value-4
    * value-7
  * **Bus-04**
    * generic
    * value-0
    * value-1
    * value-2
    * value-4
    * value-8
    * value-F
  * **Bus-05**
    * generic
    * value-0
  * **Bus-06**
    * generic
    * value-0
  * **Bus-07**
    * generic
    * value-0
  * **Bus-08**
    * Ascii-A
    * generic
    * value-0

## Examples
* 00-Index
* **TESTs**
  * **Bus**
    * **Bus-02**
      * **Alhambra-II**
        * 01-generic
        * 02-value-0
        * 03-value-1
        * 04-value-2
        * 05-value-3
        * 06-k-1
    * **Bus-03**
      * **Alhambra-II**
        * 01-generic
        * value-0
        * value-1
        * value-2
        * value-4
        * value-7
    * **Bus-04**
      * **Alhambra-II**
        * 01-generic
        * value-0
        * value-1
        * value-2
        * value-4
        * value-8
        * value-F
    * **Bus-05**
      * **Alhambra-II**
        * 01-generic
        * value-0
    * **Bus-06**
      * **Alhambra-II**
        * 01-generic
        * value-0
    * **Bus-07**
      * **Alhambra-II**
        * 01-generic
        * value-0
    * **Bus-08**
      * **Alhambra-II**
        * 01-generic
        * value-0
  * **bits**
    * **Alhambra-II**
      * 01-bit-0
      * 02-bit-1
      * 03-generic-bit

## Languages
| Language | Translated strings |
|:--------:|:------------------:|
| es_ES | ![](https://progress-bar.dev/98) |

## Authors
* [Juan Gonzalez-Gomez (Obijuan)](https://github.com/Obijuan)


## License

Licensed under [GPL-2.0](https://opensource.org/licenses/GPL-2.0).

<!-- Badges -->
[icestudio-image]: https://img.shields.io/badge/collection-icestudio-blue.svg
[icestudio-url]: https://github.com/FPGAwars/icestudio
[version-image]: https://img.shields.io/badge/version-v0.1.0-orange.svg

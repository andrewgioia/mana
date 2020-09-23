# Changelog

All notable changes to this project will be documented in this file.

## Unreleased

* v2.0 updates to add all digital product tokens and counter symbols, fix the core numbered casting cost icons, and modernize this project.
* Update this changelog for better formatting 
* Crop original full-width symbols to actual width
* Add ligatures for easier desktop use

## Versions 

### [1.9.3] 2020-09-23 Corrects evergreen class name

* **Fixed:** It's not evergreen abilities that get colorized in Arena, it's set-specific mechanics/abilities. The class name is corrected to be `.ms-mechanic`.

### [1.9.2] 2020-09-23 Adds evergreen color support

* **Added:** Class `.ms-evergreen` on ability symbols will apply the gold gradient effect in Arena.

### [1.9.1] 2020-09-04 Modal DFC symbols and Multicolor/duo support

* **Added:** Two new double-faced symbols for `modal-face` and `modal-back` added, from [Zendikar Rising](https://scryfall.com/card/znr/264/riverglide-pathway-lavaglide-pathway) [#54](https://github.com/andrewgioia/mana/issues/54)
* **Added:** Multicolor symbol with dual-layer support; add `.ms-duo` and the multicolor symbol uses both glyph layers, and adding `.ms-grad` makes it look like the Arena one with a gold gradient background [#43](https://github.com/andrewgioia/mana/issues/43)

### [1.9.0] 2020-09-03 All Arena ability symbols!

* **Added:** Excited to add _all_ 53 ability symbols from Arena! This was a big task as many had to be drawn from scratch! [#41](https://github.com/andrewgioia/mana/issues/41), [#53](https://github.com/andrewgioia/mana/issues/53), [#52](https://github.com/andrewgioia/mana/issues/52), and [#44](https://github.com/andrewgioia/mana/issues/44)
* **Fixed:** Some outdated SVG issues with the existing type symbols have been corrected
* **Added:** SVGs are now shipped [#51](https://github.com/andrewgioia/mana/issues/51)

### [1.8.0] 2020-08-21 Arena ability initial release

* **Added:** All ability symbols from Arena [#41](https://github.com/andrewgioia/mana/issues/41)
* **Fixed:** All .scss files are cleaner and a bit more optimized; probably going to move to Sass soon

### [1.7.0] 2020-08-20 Birthday release with MODO counters!

* **Added:** All counters from Magic Online [#39](https://github.com/andrewgioia/mana/issues/39)
* **Fixed:** Cleaned up some NPM package info and project meta data

### [1.6.0] 2020-01-30 Saga and Acorn symbols 

* **Added:** Acorn counter symbol from Unsanctioned ([#48](https://github.com/andrewgioia/Mana/issues/48))
* **Added:** Saga hexagon symbol from saga cards ([#47](https://github.com/andrewgioia/Mana/issues/47), [#35](https://github.com/andrewgioia/Mana/issues/35))
* **Fixed:** All current loyalties are now supported, including -25 ([#42](https://github.com/andrewgioia/Mana/issues/42)) and -X ([#45](https://github.com/andrewgioia/Mana/issues/45))

### Previous (to fix)

* v1.5.0 - updated readme on editing the source; new icons for MTGO counters
* v1.4.1 - half mana symbol fix using just the icon element (issue #6)
* v1.4.0 - big update: artist, Poleis, power/toughness, DFC enchantment, and multiple type symbols added; simplified split cost handling; more planeswalker loyalties; SASS support
* v1.3.2 - incrementing for new npm publish and jsDelivr note; fixed docs
* v1.3.1 - fixed class name issue for 1,000,000 symbol
* v1.3.0 - added Guild and Clan symbols
* v1.2.0 - added DFC symbols for the Origins planeswalkers (ignite and spark) and the Eldritch Moon meld cards (emrakul and moon)
* v1.1.0 - added the new Energy symbol
* v1.0.1 - added classes for -12 and -14 loyalty (sorry Jace and Karn!)
* v1.0 - new documentation page at http://andrewgioia.github.io/Mana/
* v0.6 - adding double-faced card symbols (day, night)
* v0.5 - adding the new colorless wastes symbol
* v0.4 - adding classes for 16, 17, 18, 19, and 20 symbols
* v0.3 - phyrexian mana classes use MTGJson standard; project-specific LESS prefix added (@JayGray)
* v0.2 - Flashback symbol added
* v0.1 - initial font creation and CSS/LESS files added
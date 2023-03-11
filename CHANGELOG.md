# Changelog

All notable changes to this project will be documented in this file.

## Unreleased

* v2.0 updates to add all digital product tokens and counter symbols, fix the core numbered casting cost icons, and modernize this project.
* Update this changelog for better formatting 
* Crop original full-width symbols to actual width

## Versions 

### [1.15.5] 2023-03-11 DFC and loyalty updates

* **Added:** DFC symbols for Saga and the flip side, Saga creatures, from NEO ([#98](https://github.com/andrewgioia/mana/issues/98))
* **Added:** New outlined version of the loyalty symbol that shows up on certain Unfinity cards ([#97](https://github.com/andrewgioia/mana/issues/97))
* **Added:** The "can't block or must attack" symbol in Arena, labeled "combat condition" here as an ability symbol ([#100](https://github.com/andrewgioia/mana/issues/100))
* **Fixed:** Loyalty line heights have been corrected cross browser ([#96](https://github.com/andrewgioia/mana/issues/96))

### [1.15.4] 2023-03-08 PRs 81 and 82

* **Added:** Goad ability symbol ([#101](https://github.com/andrewgioia/mana/issues/101))
* **Added:** Land MDFC symbol ([#58](https://github.com/andrewgioia/mana/issues/58))
* **Added:** Commander type symbol ([#59](https://github.com/andrewgioia/mana/issues/59))
* **Added:** Loyalty level up card text symbol ([#60](https://github.com/andrewgioia/mana/issues/60))
* **Added:** Zone icons from MTGA ([#62](https://github.com/andrewgioia/mana/issues/62))
* **Fixed:** CSS font name now matches compiled font name ([#87](https://github.com/andrewgioia/mana/issues/87))
* **Merged:** ([PR #81])(https://github.com/andrewgioia/mana/pull/81) by @Lisstem fixes apostrophe bug in `_variables.scss`
* **Merged:** ([PR #82])(https://github.com/andrewgioia/mana/pull/82) by @Lisstem adds missing saga loyalty to `_loyalty.scss`

### [1.15.3] 2023-03-04 Remaining split Phyrexian classes

* **Added:** All other split Phyrexian mana classes introduced recently ([#86](https://github.com/andrewgioia/mana/issues/86))

### [1.15.2] 2023-03-04 GUP and GWP classes (@Araneline)

* **Merged:** ([PR #93](https://github.com/andrewgioia/mana/pull/93)) by @Araneline to add support for the GUP and GWP split phyrexian classes

### [1.15.1] 2023-03-03 Fabricate

* **Added:** Ticket symbol from Unfinity ([#92](https://github.com/andrewgioia/mana/issues/92))
* **Changed:** Dungeon now has an alias as a card type (`.ms-dungeon`) ([#84](https://github.com/andrewgioia/mana/issues/84))
* **Fixed:** Fabricate has its own correct symbol now. It had previously been aliased and this got messed up in the last build.

### [1.15.0] 2023-03-03 Backlog of Arena ability and counter symbols

* **Added:** Finally added the huge backlog of Arena ability symbols: fabricate, changeling, domain, day/night, daybound/nightbound, coven, investigate, decayed, cleave, disturb, exploit, training, channel, ninjutsu, reconfigure, blitz, alliance, obscura (not sure what this corresponds to), casualty, hideaway, read ahead, enlist, specialist, unearth, meld, prototype, toxic, phyrexian, corrupted, and for mirrodin!
    * Big thanks to @ThePieBandit for the motivation and asset help!
* **Added:** 2 missing Arena counters: stun and shield

### [1.14.0] 2021-07-14 Strixhaven schools

* **Added:** Lorehold, Prismari, Silverquill, Quandrix, and Witherbloom school symbols added, including dual layered support

### [1.13.0] 2021-07-10 D20, alternate white symbols, basic ligature support

* **Added:** D20 ability symbol from Arena
* **Added:** Alternate white mana symbols (the original pre-Ice Age symbol and the recent List variant) ([#70](https://github.com/andrewgioia/mana/issues/70))
* **Added:** Arena's snow mana symbol variant ([#69](https://github.com/andrewgioia/mana/issues/69))
* **Fixed:** Missing variable in `_variables.scss` for `.ms-ability-grad` added ([#64](https://github.com/andrewgioia/mana/issues/64) and [#76](https://github.com/andrewgioia/mana/issues/76))
* **Fixed:** Kicker icon is no longer overwritten by the static ability icon in the Sass version ([#65](https://github.com/andrewgioia/mana/issues/65))

### [1.12.1] 2021-07-08 SVG files

* **Added:** missing SVG files for the most recent abilities and type symbols.

### [1.12.0] 2021-07-08 AFR abilities

* **Added:** Only seems to be 1 ability symbol in Arena for AFR: venturing into the dungeon. Wizards calls this "Dungeon" so we're naming it that as well.

### [1.11.0] 2021-07-06 More Arena ability symbols

* **Added:** Ability symbols for Boast, Foretell, Magecraft, Learn, and Ward
* **Added:** Lesson DFC symbol

### [1.10.0] 2020-12-21 Color indicators

* **Added:** Color indicator symbols added for all color combinations ([#40](https://github.com/andrewgioia/mana/issues/40))
* **Added:** New variables added for colors used in project as the beginning of getting all of these things into variables
* **Fixed:** Sass variables were not called correctly in `_duo.scss`, this is now fixed

### [1.9.4] 2020-10-10 Kicker, Party, and Landfall abilities

* **Added:** New ability symbols in Arena for Kicker, Party, and Landfall.

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
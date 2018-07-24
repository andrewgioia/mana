# Mana v1.3.2

## The Magic: the Gathering mana symbol font!

**New:** view the [documentation site](https://andrewgioia.github.io/Mana) to see Mana in action!

Mana is a complete set of Magic: the Gathering mana, tap, and card type symbols as a pictographic font. You can use this font anywhere you want to display mana and tap symbols&mdash;in your MtG app or website, documents, card images, anything!

## Installing

The easiest way to get Mana into your project is to use either the Bower or NPM packages, depending on your package manager:

```shell
$> bower install mana
```

```shell
$> npm install mana-font
```

We've registered `mana` with [Bower](https://bower.io/#getting-started) and 'mana-font' with [NPM](https://docs.npmjs.com/getting-started/what-is-npm). Just install using the above commands in your project and you can edit anything as needed.

You can also download the [zip file](https://github.com/andrewgioia/Mana/archive/master.zip) here at Github and use the font files and CSS files in your project as needed.

## Usage

Each mana symbol has its own font character. Display them in a manner similar to [Keyrune](http://andrewgioia.github.io/Keyrune) using the `<i class="ms ms-g"></i>` element and class syntax. Class name codes are based on textual mana symbol codes (like g for Green or 3 for, well, {3}).

To use Mana, move the web font files to your `/fonts` directory and include the mana.css stylesheet in your `<head>`:

```html
<link href="css/mana.css" rel="stylesheet" type="text/css" />
```

**NEW:** you can now include Mana via CDN thanks to the amazing [jsDelivr](http://jsdelivr.com) project! To include the latest version, reference:

```html
<link href="//cdn.jsdelivr.net/npm/mana-font@latest/css/mana.css" rel="stylesheet" type="text/css" />
```

You can also reference mana.min.css for the minified version.

## Editing the Source

Feel free to edit the source files and compile Mana to fit your needs. Currently LESS is supported, with Sass coming soon.

## Using Mana on the Desktop

If you'd like to use Mana as a desktop font (e.g., in a Word document) there are a few steps and things to know. First, to get it loaded on your system just download the [latest zip file](https://github.com/andrewgioia/Mana/archive/master.zip), extract it, and navigate to `Mana-master\fonts`. In there, install the `mana.ttf` font (typically by double clicking it).

Mana uses [private use characters](https://en.wikipedia.org/wiki/Private_Use_Areas) for the font glyphs so you unfortunately can't normally "type" anything in Word to see the symbols. To do so, open up the [Mana Cheatsheet](http://andrewgioia.github.io/Mana/cheatsheet.html) and copy the symbol you want, then paste it into Word (or whatever software you're using).

## License

All mana, tap, and card type symbol images are copyright Wizards of the Coast ([http://magicthegathering.com](http://magicthegathering.com))

The Mana font is licensed under the the SIL OFL 1.1 ([http://scripts.sil.org/OFL](http://scripts.sil.org/OFL))

Mana CSS, LESS, and Sass files are licensed under the MIT License ([http://opensource.org/licenses/mit-license.html](http://opensource.org/licenses/mit-license.html))

Attribution is **greatly appreciated** but not required!

## Changelog

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

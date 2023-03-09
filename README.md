# Mana v1.16.0

## The Magic: the Gathering mana symbol font!

**View the [documentation site](https://mana.andrewgioia.com) to see Mana in action!**

Mana is a complete set of Magic: the Gathering mana, tap, and card type symbols as a pictographic font. You can use this font anywhere you want to display mana and tap symbols&mdash;in your MtG app or website, documents, card images, anything!

## Installation

The easiest way to get Mana into your project is to use the NPM package:

```shell
$> npm install mana-font
```

Bower is still supported but given their notice to migrate away from it I recommend NPM if you're using a package manager. This project is registered as 'mana-font' with [NPM](https://docs.npmjs.com/getting-started/what-is-npm) and `mana` with [Bower](https://bower.io/#getting-started). Just install using the above commands in your project and you can edit anything as needed.

You can also download the [zip file](https://github.com/andrewgioia/mana/archive/master.zip) here at Github and use the font files and CSS files in your project as needed.

## Using Mana in your project

Each mana symbol has its own font character. Display them in a manner similar to any icon font, like [Keyrune](https://keyrune.andrewgioia.com), using the `<i class="ms ms-g"></i>` element and class syntax. Class name codes are based on textual mana symbol codes (like g for Green or 3 for, well, {3}).

To use Mana, move the web font files to your `/fonts` directory and include the `mana.min.css` stylesheet in your `<head>`:

```html
<link href="css/mana.min.css" rel="stylesheet" type="text/css" />
```

You can also include Mana via CDN thanks to the amazing [jsDelivr](http://jsdelivr.com) project! To include the latest version, reference:

```html
<link href="//cdn.jsdelivr.net/npm/mana-font@latest/css/mana.min.css" rel="stylesheet" type="text/css" />
```

Replace `mana.min.css` with `mana.css` for the unminified version, if you need that.

## Editing the source

You can edit the Sass or Less source files and compile Mana to fit your needs, add custom classes, or extend it in your project.

The `mana.svg` font file contains every glyph used in Mana. If you'd like to completely decompile it, you can view the SVG coordinates in any text editor or upload it to an SVG font editor like [IcoMoon](https://icomoon.io) (which I use for Mana and Keyrune) or [Birdfont](https://birdfont.org).

To add new icons, I recommend first creating a project in IcoMoon and uploading Mana into it. Draw any new glyphs in a vector/SVG editor of your choice export them as SVGs. Then upload each individual glyphs to your IcoMoon project and generate the font files when you're ready. You can add them to your project the same way you would with Mana (putting the font files in a `/fonts` directory and referencing them in your CSS file with an `@font-face` declaration).

## Using Mana in desktop software

If you'd like to use Mana as a desktop font (e.g., in a Word document) there are a few steps and things to know. First, to get it loaded on your system just download the [latest zip file](https://github.com/andrewgioia/mana/archive/master.zip), extract it, and navigate to `mana-master\fonts`. In there, install the `mana.ttf` font (typically by double clicking it).

Mana uses [private use characters](https://en.wikipedia.org/wiki/Private_Use_Areas) for the font glyphs so you unfortunately can't normally "type" anything in Word to see the symbols. To do so, open up the [Mana Cheatsheet](https://mana.andrewgioia.com/cheatsheet.html) and copy the symbol you want, then paste it into Word (or whatever software you're using).

## License

All mana, tap, and card type symbol images are copyright Wizards of the Coast ([http://magicthegathering.com](http://magicthegathering.com))

The Mana font is licensed under the the SIL OFL 1.1 ([http://scripts.sil.org/OFL](http://scripts.sil.org/OFL))

Mana CSS, LESS, and Sass files are licensed under the MIT License ([http://opensource.org/licenses/mit-license.html](http://opensource.org/licenses/mit-license.html))

Attribution is **greatly appreciated** but not required!
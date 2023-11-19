# [Atkinson Hyperlegible Pro](https://jacobxperez.github.io/atkinson-hyperlegible-pro/)

An updated and extended version of [Atkinson Hyperlegible](https://github.com/googlefonts/atkinson-hyperlegible).

---
![banner](docs/banner.jpg)

## Table of Contents

* [Overview](#overview)
  * [Design Features](#design-features)
  * [Installing](#installing-the-font)
  * [Language Support](#language-support)
* [OpenType Features](#opentype-features)
  * [Flip the Zero](#flip-the-zero)
  * [Ligatures](#ligatures)
* [Locally Run Website](#locally-run-website)
* [Contributing](#contributing)
* [License](#license)
  * [Font](#font)
  * [Code](#code)

## Overview

Atkinson Hyperlegible Pro is an updated and extended version of the original typeface, which was initially designed for The Braille Institute and named after its founder, J. Robert Atkinson. It was specifically designed to improve character recognition and legibility for low-vision readers by incorporating distinctive and unambiguous letterform’s. The typeface was a Winner of Fast Company’s 2019 Innovation By Design Award.

* Four fonts, including two weights (regular, italic, bold, bold italic)
* An additional 222 glyphs supporting 102 languages
* Supports 340 orthographies according to [Hyperglot](https://hyperglot.rosettatype.com/)
* 2,356 total glyphs across all fonts, 589 per font
* Improve legibility and readability for low vision readers
* Updated kerning for visual harmony and readability
* Includes standard ligatures `fi ff ffi fl ffl`
* Alternative reversed number zero `0`

### Design Features

Designed for low-vision readers, certain letters and numbers can be hard to distinguish from one another. Atkinson Hyperlegible Pro differentiates common misinterpreted letters and numbers using various design techniques: B vs. 8, 1 vs. L vs. l vs. I. Recognizable Footprints: Character boundaries are clearly defined, ensuring understanding across the visual-ability spectrum.

Unless required by applicable law or agreed to in writing, software

Differentiated letterform’s: Similar letter pairs are differentiated from each other to dramatically increase legibility. Unambiguous Characters: designed to increase legibility and distinction.

> `ER79jr Vsa36`

Exaggerated forms: Shaping of letters is exaggerated to provide better clarity. Opened Counterspace: Open areas of certain letters are expanded to provide greater distinction.

> `aGbgrpqu Åö8ij%?¡:`

Angled spurs and differentiated tails: Increase recognition and define distinctive style. Circular Details: Links to the history of Braille Institute and braille dots.

### Installing the Font

* [Download](https://github.com/jacobxperez/atkinson-hyperlegible-pro/archive/refs/heads/main.zip) the font from the main branch.
* Extract the file to reveal additional folders inside. Find the Open Type Format (.otf) files for the four Atkinson Hyperlegible Pro fonts (regular, italic, bold, bold italic) inside the “[fonts/otf](https://github.com/jacobxperez/atkinson-hyperlegible-pro/tree/main/fonts/otf)” folder.
* Note: Only the otf files are needed to install the font on a computer.
* On Windows 10: Double-click the font file, then click the “Install” button in the font preview window that opens. The font will be installed. Alternatively, right-click on the file and choose “Install” from the pop-up menu.
* On Mac: Double-click the font file in the Finder, then click “Install Font” in the font preview window that opens. After your Mac validates the font and opens the Font Book app, the font is installed and available for use.

### Language Support

Afrikaans Albanian Asturian Asu Basque Bemba Bena Breton Catalan Chiga Colognian Cornish Croatian Czech Danish Dutch Embu English Esperanto Estonian Faroese Filipino Finnish French Friulian Galician Ganda German Gusii Hungarian Icelandic Inari Sami Indonesian Irish Italian Jola-Fonyi Kabuverdianu Kalenjin Kamba Kikuyu Kinyarwanda Koyraboro Senni Koyra Chiini Lakota Latvian Lithuanian Lower Sorbian Luo Luxembourgish Luyia Machame Makhuwa-Meetto Makonde Malagasy Maltese Manx Meru Morisyen Northern Sami North Ndebele Norwegian Bokmål Norwegian Nynorsk Nyankole Oromo Polish Portuguese Quechua Romanian Romansh Rombo Rundi Rwa Samburu Sango Sangu Scottish Gaelic Sena Serbian Shambala Shona Slovak Soga Somali Spanish Swahili Swedish Swiss German Taita Tasawaq Teso Turkish Upper Sorbian Uzbek (Latin) Vietnamese Volapük Vunjo Walser Welsh Western Frisian Yoruba Zarma Zulu.

## OpenType Features

OpenType features refer to different glyphs or character styles contained within an OpenType font. These include things like ligatures, kerning, fractions, numeral styles, and several others.

### Flip the Zero

By default the zero remains with a backslash `\` this was done to prevent confusion with the Danish Ø however, when pairing the typeface with a monospace that only supports a forwardslash `/` zero, this may create a cognitive dissonance problem. On that occasion you might want to flip the zero by adding `font-variant-numeric: slashed-zero;` to your CSS file.

```css
body {
  font-family: "Atkinson Hyperlegible Pro", "Atkinson Hyperlegible", Helvetica, Arial, sans-serif;
  font-size: 100%;
  font-weight: 400;
  font-variant-numeric: slashed-zero;
}
```

### Ligatures

Web browsers have ligatures activated by default, we recommend disabling them for heading or large display text.

```css
h1, h2, h3 {
  font-variant-ligatures: no-common-ligatures;
}
```

## Locally Run Website

1) Install dependencies on your machine with [npm](https://www.npmjs.com/)

    ```bash
    npm install
    ```

2) Then run website locally with this script

    ```bash
    npm run dev
    ```

## Contributing

Help us improve Atkinson Hyperlegible Pro for everyone, any contribution or feedback is welcome.
Please read our [contributing guidelines](https://github.com/jacobxperez/atkinson-hyperlegible-pro/blob/main/.github/CONTRIBUTING.md)
before embarking on any significant pull request.

## LICENSE

### Font

Copyright (C) 2020 [Braille Institute of America, Inc](https://brailleinstitute.org/).

Licensed under the SIL Open Font License, v1.1. See [LICENSE.txt](LICENSE.txt) for details.

### Code

Copyright (C) 2023 [Jacob Perez](https://jacobxperez.github.io/blog/)

Licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0) (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

<http://www.apache.org/licenses/LICENSE-2.0>

Unless required by applicable law or agreed to in writing, software

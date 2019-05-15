# Awesome Readium [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://readium.org/assets/logos/readium-logo.png" align="right" width="200">](http://readium.org/)

A list of lists of awesome [Readium](https://readium.org/) resources.

Readium is an open-source foundation dedicated to the development of software, standards and best practices for digital publications.

**Disclaimer:** This list is created for informational purposes only and any links do not constitute an endorsement, recommendation, or favoring by the Readium Foundation.

## Contents

* [Standards](#standards)
* [Documentation](#documentation)
* [Publication Servers](#publication-servers)
* [Publication Viewers](#publication-viewers)
* [Examples](#examples)
* [Experiments](#experiments)

## Standards

The Readium community has developed several standards for publications:

* [Web Publication Manifest](https://readium.org/webpub-manifest/) - specifies a JSON manifest format for distributing publications on the Web
* [Licensed Content Protection](https://readium.org/lcp-specs/) - specifies an interoperable DRM scheme for packaged publications
* [License Status Document](https://readium.org/lcp-specs/) - specifies a JSON document that provides additional controls over a license

## Documentation

* [Architecture](https://readium.org/architecture/) - overview of the architecture of all Readium projects
* [Locators](https://readium.org/architecture/locators/) - defines a JSON object for pointing into digital publications
* [Readium CSS](https://readium.org/readium-css/docs/) - defines a set of reference stylesheets for EPUB Reading Systems

## Publication Servers

[Publications servers](https://readium.org/architecture/server/) are a key component in [Readium's architecture](https://readium.org/architecture/). These servers can output a Readium Web Publication Manifest.

* [r2-streamer-js](https://github.com/readium/r2-streamer-js) - written in TypeScript using Node.js
* [r2-streamer-go](https://github.com/readium/r2-streamer-go) - written in Go

## Publication Viewers

These viewers are all compatible with the Readium Web Publication Manifest.

* [Epub.js](https://github.com/futurepress/epub.js/) - an ebook viewer written in JS
* [R2 Reader (Android)](https://github.com/readium/r2-testapp-kotlin) - an ebook and comics viewer written in Kotlin (this is primarily a test app for Readium Mobile projects)
* [R2 Reader (iOS)](https://github.com/readium/r2-testapp-swift) - an ebook, PDF and comics viewer written in Swift (this is primarily a test app for Readium Mobile projects)
* [Vivliostyle](https://vivliostyle.org/) - a document and publication viewer written in JS
* [xbreader](https://github.com/chocolatkey/xbreader) - a manga viewer written in TypeScript

## Examples

* [Animeta! (xbreader)](https://j-novel.club/mc/animeta-volume-1-chapter-1) - first chapter of a manga distributed using RWPM in a fork of xbreader
* [Herland (Jellybooks)](https://www.jellybooks.com/cloud_reader/books/herland) - a classic distributed using RWPM in Jellybooks' take on Readium Web
* [Readium CSS Documentation (Vivliostyle)](https://vivliostyle.github.io/vivliostyle.js/viewer/vivliostyle-viewer.html#b=https://readium.org/readium-css/docs/manifest.json) - Readium CSS documentation in Vivliostyle Viewer using RWPM
* [Tom Sawyer (De Marque)](https://player.cantookaudio.com/aHR0cHM6Ly9hcGkuYXJjaGl2ZWxhYi5vcmcvYm9va3MvdG9tX3Nhd3llcl9saWJyaXZveC9vcGRzX2F1ZGlvX21hbmlmZXN0) - Tom Sawyer as an audiobook published by Librivox using RWPM in De Marque's Audiobook Reader

## Experiments

* [webpub-viewer](https://github.com/HadrienGardeur/webpub-viewer) - an `iframe` based navigator for ebooks, written in JS
* [comics-viewer](https://github.com/HadrienGardeur/comics-viewer) - an `img` based navigator for comics, written in JS
* [audiobook-player](https://github.com/HadrienGardeur/audiobook-player) - an `audio` based navigator for audiobooks, written in JS


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, all contributors waive all copyright and related neighboring rights to this work.
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
* [Desktop Apps](#desktop-apps)
* [Mobile Apps](#mobile-apps)
* [Examples](#examples)
* [Experiments](#experiments)

## Standards

The Readium community has developed several industrial standards for publications:

* [Web Publication Manifest](https://readium.org/webpub-manifest/) - specifies a JSON manifest format for distributing publications on the Web.
* [Licensed Content Protection](https://readium.org/lcp-specs/) - specifies an interoperable DRM scheme for packaged publications.
* [License Status Document](https://readium.org/lsd-specs/) - specifies a JSON document and REST protocol that provides additional controls over a license.

## Documentation

* [Architecture](https://readium.org/architecture/) - overview of the architecture of all Readium projects
* [Locators](https://readium.org/architecture/locators/) - defines a JSON object for pointing into digital publications
* [Readium CSS](https://readium.org/readium-css/docs/) - defines a set of reference stylesheets for EPUB Reading Systems

## Publication Servers

[Publications servers](https://readium.org/architecture/server/) are a key component in [Readium's architecture](https://readium.org/architecture/). These servers can output a Readium Web Publication Manifest.

* [r2-streamer-js](https://github.com/readium/r2-streamer-js) - written in TypeScript using Node.js
* [r2-streamer-go](https://github.com/readium/r2-streamer-go) - written in Go

## Publication Viewers

These open-source viewers are all compatible with the Readium Web Publication Manifest.

* [Epub.js](https://github.com/futurepress/epub.js/) - an ebook viewer written in JS
* [Vivliostyle](https://vivliostyle.org/) - a document and publication viewer written in JS
* [xbreader](https://github.com/chocolatkey/xbreader) - a manga viewer written in TypeScript

## Desktop Apps

* [Thorium Reader (Windows / Mac / Linux)](https://www.edrlab.org/software/thorium-reader/) - a free and open-source ebook / audiobook reader developed by EDRLab. Based on Readium Desktop, LCP compliant.

## Mobile Apps

* [R2 Reader (Android)](https://apps.apple.com/us/app/r2-reader/id1363963230) - the open-source test application for the Readium Mobile Android toolkit; ebook / comics reader written in Kotlin, LCP compliant. [Participate on Github](https://github.com/readium/r2-testapp-kotlin).
* [R2 Reader (iOS)](https://play.google.com/store/apps/details?id=org.readium.r2reader) - the open-source test application for the Readium Mobile iOS toolkit; ebook / PDF reader written in Swift, LCP compliant. [Participate on Github](https://github.com/readium/r2-testapp-swift).
* [Bookbeat](https://apps.apple.com/us/app/id1056652614) - an ebook / audiobook reader based on Readium Mobile iOS.
* [DITA Reader Android](https://play.google.com/store/apps/details?id=com.aferdita.urms.reader) - an ebook reader based on Readium Mobile Android, LCP compliant.
* [DITA Reader iOS](https://apps.apple.com/us/app/dita-reader/id1274807900) - an ebook reader based on Readium Mobile iOS, LCP compliant.
* [PRETNUMERIQUE en Bibliothèque](https://apps.apple.com/ca/app/id1391138546) - an ebook / audiobook reader based on Readium Mobile iOS, LCP compliant.
* [desLibris (iOS / Android)](http://www2.canadianelectroniclibrary.ca/) - an ebook / audiobook reader published by the Canadian Electronic Library, based on Readium Mobile iOS / Android, LCP compliant.
* [Allbok (iOS)](https://apps.apple.com/no/app/allbok/id1485392740) - an ebook / audiobook reader developed by Bokbasen for Norwegian public libraries. Based on Readium Mobile iOS, LCP compliant.
* [Lisa Reader (iOS / Android)](https://lis-a.fr/fr/lisa/) - an ebook reader published by Art Book Magazine for French readers. Based on the original Readium SDK, LCP compliant.
* [Baobab Reader (iOS)](https://apps.apple.com/fr/app/baobab-app/id1364023895) - an ebook reader published by Dilicom for French public libraries. Based on the original Readium SDK, LCP compliant.
* [Baobab Reader (Android)](https://play.google.com/store/apps/details?id=com.baobabapp.baobab) - an ebook reader published by Dilicom for French public libraries. Based on the original Readium SDK, LCP compliant.
* [LEA Reader (iOS / Android)](https://www.adilibre.fr/lea-reader/) - an ebook reader published by Adilibre for French readers. Based on the original Readium SDK, LCP compliant.
* [Brio Reader (iOS)](https://apps.apple.com/fr/app/brio-reader/id1475894718) - an ebook / PDF / audiobook reader published by by Eden Livres for French readers. Based on Readium Mobile iOS, LCP compliant.
* [Bibblix (iOS)](http://http://bibblix.se/) - an ebook reader targeting 6-12 years old patrons, developed by the Stockholm Public Library in Sweden. Based on Readium Mobile iOS, LCP compliant.
* [Glassboxx (iOS)](https://apps.apple.com/gb/app/glassboxx/id1464705712) - an ebook / audiobook reader published by Firsty Group for its [Glassboxx platform](https://glassboxx.co.uk/). Based on Readium Mobile iOS, LCP compliant.
* [Glassboxx (Android)](https://play.google.com/store/apps/details?id=uk.co.firstygroup.glassboxx) - an ebook / audiobook reader published by Firsty Group for its Glassboxx platform. Based on Readium Mobile Android, LCP compliant.
* [Ulverscroft (iOS)](https://apps.apple.com/gb/app/ulibrary/id977511203) - an audiobook reader published by the Ulverscroft Group for the [Ulverscroft Library](https://llc.ulverscroftulibrary.com/). Based on Readium Mobile iOS, LCP compliant.
* [Ulverscroft (Android)](https://play.google.com/store/apps/details?id=ulibrary.ulverscroftulibrary.co.uk.ulibrary) - an audiobook reader published by the Ulverscroft Group for the Ulverscroft Library. Based on Readium Mobile Android, LCP compliant.
* [Inspirata ebooks (iOS / Android)](https://https://endao.co/) - an ebook reader targeting Christian readers in Hong Kong, developed by Endao.co. Based on Readium Mobile iOS / Android, LCP compliant.
* [Shanghai Library Reader (iOS / Android)](http://www.library.sh.cn/web/index.html) - an ebook reader developed by the Shanghai Library for its patrons. Based on Readium Mobile iOS / Android, LCP compliant.


## Examples

* [Animeta! (xbreader)](https://j-novel.club/mc/animeta-volume-1-chapter-1) - first chapter of a manga distributed using RWPM (Readium Web Publication Manifest) in a fork of xbreader.
* [Herland (Jellybooks)](https://www.jellybooks.com/cloud_reader/books/herland) - a classic distributed using RWPM in Jellybooks' take on Readium Web.
* [Readium CSS Documentation (Vivliostyle)](https://vivliostyle.github.io/vivliostyle.js/viewer/vivliostyle-viewer.html#b=https://readium.org/readium-css/docs/manifest.json) - Readium CSS documentation in Vivliostyle Viewer using RWPM.
* [Tom Sawyer (De Marque)](https://player.cantookaudio.com/aHR0cHM6Ly9hcGkuYXJjaGl2ZWxhYi5vcmcvYm9va3MvdG9tX3Nhd3llcl9saWJyaXZveC9vcGRzX2F1ZGlvX21hbmlmZXN0) - Tom Sawyer as an audiobook published by Librivox using RWPM in De Marque's Audiobook Reader.

## Experiments

* [webpub-viewer](https://github.com/HadrienGardeur/webpub-viewer) - an `iframe` based navigator for ebooks, written in JS
* [comics-viewer](https://github.com/HadrienGardeur/comics-viewer) - an `img` based navigator for comics, written in JS
* [audiobook-player](https://github.com/HadrienGardeur/audiobook-player) - an `audio` based navigator for audiobooks, written in JS


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, all contributors waive all copyright and related neighboring rights to this work.

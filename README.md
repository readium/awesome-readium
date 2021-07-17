# Awesome Readium [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://readium.org/assets/logos/readium-logo.png" align="right" width="200">](http://readium.org/)

A list of lists of awesome [Readium](https://readium.org/) resources.

Readium is an open-source foundation dedicated to the development of software, standards and best practices for digital publications.

**Disclaimer:** This list is created for informational purposes only and the provided links do not constitute an endorsement, recommendation, or favoring by the Readium Foundation.

## Contents

* [Standards](#standards)
* [Documentation](#documentation)
* [Desktop Apps](#desktop-apps)
* [iOS](#ios--ipados)
* [Android](#android--chrome-os)
* [Mobile Test Apps](#mobile-test-apps)
* [Publication Servers](#publication-servers)
* [Publication Viewers](#publication-viewers)
* [Examples of web publications](#examples)
* [Mobile Apps based on the legacy Readium SDK](#mobile-apps-sdk)
* [Experiments](#experiments)

## Standards

The Readium community has developed several industrial standards for publications:

* [Web Publication Manifest](https://readium.org/webpub-manifest/) - specifies a JSON manifest format for distributing publications on the Web.
* [Licensed Content Protection](https://readium.org/lcp-specs/) or LCP - specifies an interoperable DRM scheme for packaged publications.
* [License Status Document](https://readium.org/lcp-specs/releases/lsd/latest/) or LSD - specifies a JSON document and REST protocol that provides additional controls over a DRM license.

A separate list of LCP adopters is maintained by EDRLab [here](https://www.edrlab.org/readium-lcp/certified-apps-servers/). 

## Documentation

* [Architecture](https://readium.org/architecture/) - overview of the architecture of all Readium projects
* [Locators](https://readium.org/architecture/models/locators/) - defines a JSON object for pointing into digital publications
* [Readium CSS](https://readium.org/readium-css/docs/) - defines a set of reference stylesheets for EPUB Reading Systems


## Desktop Apps

Desktop Apps based on the Readium Desktop toolkit (in alphabetical order). 

* [Thorium Reader (Windows 10 / MacOS / Linux)](https://www.edrlab.org/software/thorium-reader/) - a free and open-source ebook, audiobook, comics and PDF reader developed by EDRLab; fully accessible; LCP certified.
* [eKitabu Reader (Windows 10 / MacOS / Linux)](https://www.ekitabu.com/) - an ebook reader developed by eKitabu, targeting education in Africa.

Desktop Apps using Readium JS:
* [Wiley eText (MacOS)](https://apps.apple.com/fr/app/wiley-etext/id1523684519) - an education reader developed by Wiley Publishing.

## iOS & iPadOS

Mobile Apps based on the Readium Mobile iOS toolkit (in alphabetical order). 

* [Aldiko Next (iOS)](https://apps.apple.com/us/app/aldiko-next/id1476410111) - an ebook, audiobook and comics reader developed by De Marque; LCP certified.
* [Allbok (iOS)](https://apps.apple.com/no/app/allbok/id1485392740) - an ebook / audiobook reader developed by Bokbasen for Norwegian public libraries; LCP certified.
* [Bibblix (iOS)](http://http://bibblix.se/) - an ebook reader targeting 6-12 years old patrons, developed by the Stockholm Public Library in Sweden; LCP certified.
* [Biblio Library (iOS)](https://apps.apple.com/us/app/biblio-library/id1286685079) - an ebook / audiobook reader developed by Axiell Media for public libraries in Sweden and Finland; LCP compliant.
* [Brio Reader (iOS)](https://apps.apple.com/fr/app/brio-reader/id1475894718) - an ebook / PDF / audiobook reader published by by Eden Livres for French readers; LCP certified.
* [Bookbeat](https://apps.apple.com/us/app/id1056652614) - an ebook / audiobook reader developed by Bookbeat for its users.
* [DITA Reader (iOS)](https://apps.apple.com/us/app/dita-reader/id1274807900) - an ebook / PDF / audiobook reader developed by DITA; LCP certified.
* [Gantec EasyReadz (iOS)](https://apps.apple.com/us/app/easyreadz/id1527785244) - an EPUB / PDF reader with direct access to a catalog of ebooks in English (ebooks2go), published by [Gantec publishing](https://www.gantecpublishing.com); side-loading available; LCP certified.
* [Glassboxx (iOS)](https://apps.apple.com/gb/app/glassboxx/id1464705712) - an ebook / audiobook reader published by Firsty Group for its [Glassboxx platform](https://glassboxx.co.uk/); LCP certified.
* [Inspirata ebooks (iOS)](https://https://endao.co/) - an ebook reader targeting Christian readers in Hong Kong, developed by Endao.co; LCP certified.
* [NABU Reader (iOS)](https://apps.apple.com/fr/app/nabu-org/id1483607930) - an EPUB reader for children in Rwanda and Kenya, published by [NABU.org](https://thenewpublishingstandard.com/2020/10/10/nabu-digital-reading-app-launches-in-kenya-with-free-content-in-english-and-kiswahili/); LCP certified. 
* [NetGalley Shelf (iOS)](https://apps.apple.com/us/app/netgalley-shelf/id1499581600) - NetGalley helps publishers and authors promote digital review copies and audiobooks to book advocates and industry professionals.
* [PretNumerique (iOS)](https://apps.apple.com/ca/app/id1391138546) - an ebook / audiobook reader published by Pretnumerique.ca for its patrons; LCP certified.
* [Shanghai Library Reader (iOS)](http://www.library.sh.cn/web/index.html) - an EPUB reader developed by the Shanghai Library for its patrons; LCP certified.
* [SUSS Reader (iOS)](https://apps.apple.com/sg/app/suss-reader-for-ebooks-epubs/id1477574366) - an EPUB / PDF reader for Interactive Study Guides published by the [Singapore University of Social Sciences](https://www.suss.edu.sg/).
* [Ulverscroft (iOS)](https://apps.apple.com/gb/app/ulibrary/id977511203) - an audiobook reader published by the Ulverscroft Group for the [Ulverscroft Library](https://llc.ulverscroftulibrary.com/); LCP certified.

## Android & Chrome OS

Mobile Apps based on the Readium Mobile Android toolkit (in alphabetical order). 

* [Aldiko (Android)](https://play.google.com/apps/testing/com.aldiko.android) - an ebook, audiobook and comics reader developed by De Marque; LCP certified.
* [Allbok (Android)](https://play.google.com/store/apps/details?id=no.bokbasen.allbok) - an ebook / audiobook reader developed by Bokbasen for Norwegian public libraries; LCP certified.
* [Biblio Library (Android)](https://play.google.com/store/apps/details?id=com.Axiellmedia.LibraryApp) - an ebook / audiobook reader developed by Axiell Media for public libraries in Sweden and Finland; LCP compliant.
* [Brio Reader (Android)](https://play.google.com/store/apps/details?id=com.eden.brioreader) - an ebook / PDF / audiobook reader published by by Eden Livres for French readers; LCP certified.
* [DITA Reader (Android)](https://play.google.com/store/apps/details?id=com.aferdita.urms.reader) - an ebook / PDF / audiobook reader developed by DITA; LCP certified.
* [Glassboxx (Android)](https://play.google.com/store/apps/details?id=uk.co.firstygroup.glassboxx) - an ebook / audiobook reader published by Firsty Group for its [Glassboxx platform](https://glassboxx.co.uk/); LCP certified.
* [Inspirata ebooks (Android)](https://https://endao.co/) - an ebook reader targeting Christian readers in Hong Kong, developed by Endao.co; LCP certified.
* [NABU Reader (Android)](https://play.google.com/store/apps/details?id=org.libraryforall.simplified&hl=en_US&gl=US) - an EPUB reader for children in Rwanda and Kenya, published by [NABU.org](https://thenewpublishingstandard.com/2020/10/10/nabu-digital-reading-app-launches-in-kenya-with-free-content-in-english-and-kiswahili/); LCP certified. 
* [NetGalley Shelf (Android)](https://play.google.com/store/apps/details?id=com.netgalley.shelf&hl=en) - NetGalley helps publishers and authors promote digital review copies and audiobooks to book advocates and industry professionals.
* [PretNumerique (Android)](https://play.google.com/store/apps/details?id=com.bibliopresto.pretnumerique) - an ebook / audiobook reader published by Pretnumerique.ca for its patrons; LCP certified.
* [Shanghai Library Reader (Android)](http://www.library.sh.cn/web/index.html) - an ebook reader developed by the Shanghai Library for its patrons; LCP certified.
* [SUSS Reader (Android)](https://play.google.com/store/apps/details?id=sg.edu.suss.etp.sreader2) - an EPUB / PDF reader for Interactive Study Guides published by the [Singapore University of Social Sciences](https://www.suss.edu.sg/).
* [Ulverscroft (Android)](https://play.google.com/store/apps/details?id=ulibrary.ulverscroftulibrary.co.uk.ulibrary) - an audiobook reader published by the Ulverscroft Group for the [Ulverscroft Library](https://llc.ulverscroftulibrary.com/); LCP certified.

## Mobile Test Apps 

These are Readium Mobile *test apps* intended to demonstrate Readium Mobile technology. Both apps are available on beta channels and are not targeting end-users; both are under active development and evolve continuously. These apps are LCP compliant, but in "test" mode only. 

* [R2 Reader (Android)](https://play.google.com/apps/testing/org.readium.r2reader) -  ebook, audiobook, comics and PDF reader written in Kotlin. [Participate on Github](https://github.com/readium/r2-testapp-kotlin).
* [R2 Reader (iOS)](https://testflight.apple.com/join/lYEMEfBr) - ebook, audiobook, comics and PDF reader written in Swift. [Participate on Github](https://github.com/readium/r2-testapp-swift).

## Publication Servers

[Publications servers](https://readium.org/architecture/server/) are a key component in [Readium's architecture](https://readium.org/architecture/). These servers can output a Readium Web Publication Manifest.

* [r2-streamer-js](https://github.com/readium/r2-streamer-js) - written in TypeScript using Node.js
* [r2-streamer-go](https://github.com/readium/r2-streamer-go) - written in Go

## Publication Viewers

Open source Web viewers compatible with the Readium Web Publication Manifest.

* [Epub.js](https://github.com/futurepress/epub.js/) - an ebook viewer written in JS
* [Vivliostyle](https://github.com/vivliostyle/vivliostyle.js) - a document and publication viewer written in JS
* [xbreader](https://github.com/chocolatkey/xbreader) - a manga viewer written in TypeScript

## Examples

* [Animeta! (xbreader)](https://j-novel.club/mc/animeta-volume-1-chapter-1) - first chapter of a manga distributed using RWPM (Readium Web Publication Manifest) in a fork of xbreader.
* [Herland (Jellybooks)](https://www.jellybooks.com/cloud_reader/books/herland) - a classic distributed using RWPM in Jellybooks' take on Readium Web.
* [Readium CSS Documentation (Vivliostyle)](https://vivliostyle.github.io/vivliostyle.js/viewer/vivliostyle-viewer.html#b=https://readium.org/readium-css/docs/manifest.json) - Readium CSS documentation in Vivliostyle Viewer using RWPM.
* [Tom Sawyer (De Marque)](https://player.cantookaudio.com/aHR0cHM6Ly9hcGkuYXJjaGl2ZWxhYi5vcmcvYm9va3MvdG9tX3Nhd3llcl9saWJyaXZveC9vcGRzX2F1ZGlvX21hbmlmZXN0) - Tom Sawyer as an audiobook published by Librivox using RWPM in De Marque's Audiobook Reader.

## Mobile Apps based on the legacy Readium SDK

Mobile Apps based on the legacy Readium SDK. 

* [Adobe Digital Editions (iOS / Android)](https://www.adobe.com/solutions/ebook/digital-editions.html) - an ebook reader published by Adobe. Partially based on the original Readium SDK. [iOS version](https://apps.apple.com/us/app/adobe-digital-editions/id952977781), [Android version](https://play.google.com/store/apps/details?id=com.adobe.digitaleditions).
* [Baobab Reader (iOS / Android)](https://baobabapp.com/) - an ebook reader published by Dilicom for French public libraries: LCP compliant. [iOS version](https://apps.apple.com/fr/app/baobab-app/id1364023895), [Android version](https://play.google.com/store/apps/details?id=com.baobabapp.baobab).
* [LEA Reader (iOS / Android)](https://www.adilibre.fr/lea-reader/) - an ebook reader published by Adilibre for French readers; LCP compliant. [iOS version](https://apps.apple.com/fr/app/lea-reader/id1313873614), [Android version](https://play.google.com/store/apps/details?id=com.adilibre.leareader)
* [Lisa Reader (iOS / Android)](https://lis-a.fr/fr/lisa/) - an ebook reader published by Art Book Magazine for French readers. Based on the original Readium SDK, LCP compliant. [iOS version](https://apps.apple.com/fr/app/lis-a/id1096168122), [Android version](https://play.google.com/store/apps/details?id=com.artbookmagazine.lisa).

## Experiments

* [webpub-viewer](https://github.com/HadrienGardeur/webpub-viewer) - an `iframe` based navigator for ebooks, written in JS
* [comics-viewer](https://github.com/HadrienGardeur/comics-viewer) - an `img` based navigator for comics, written in JS
* [audiobook-player](https://github.com/HadrienGardeur/audiobook-player) - an `audio` based navigator for audiobooks, written in JS


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, all contributors waive all copyright and related neighboring rights to this work.

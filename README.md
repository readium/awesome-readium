# Awesome Readium [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://readium.org/assets/logos/readium-logo.png" align="right" width="200">](http://readium.org/)

A list of lists of awesome [Readium](https://readium.org/) resources.

Readium is an open-source foundation dedicated to the development of software, standards and best practices for digital publications.

**Disclaimer:** This list is created for informational purposes only and the provided links do not constitute an endorsement, recommendation, or favoring by the Readium Foundation.

## Contents

* [Toolkits](#toolkits)
* [Open-source applications](#open-source-applications)
* [Specifications](#specifications)
* [Live examples](#live-examples)
* [Apps based on Readium Mobile](#apps-based-on-readium-mobile)
* [Compatible with Readium Web Publications](#compatible-with-readium-web-publications)
* [Other toolkits related to Readium](#other-toolkits-related-to-readium)

## Toolkits

* [Readium Mobile](https://readium.org/mobile)
  * [Swift toolkit](https://github.com/readium/swift-toolkit) for iOS, iPadOS and macOS
  * [Kotlin toolkit](https://github.com/readium/kotlin-toolkit) for Android and Chrome OS
* [Readium Web](https://readium.org/web)
  * [TS toolkit](https://github.com/readium/ts-toolkit) primarily used for client-side applications
  * [Go toolkit](https://github.com/readium/go-toolkit) primarily used for server-side applications
 
## Open-source applications

* [Readium CLI](https://github.com/readium/cli), a multi-command utility for interacting with EPUB files
* [Thorium Web](https://github.com/edrlab/thorium-web) for reading EPUB on the Web
* [Thorium Desktop](https://github.com/edrlab/thorium-reader) for EPUB, PDF and audiobooks on Windows, macOS and Linux

## Specifications

The Readium community maintains several specifications for the publishing industry:

* [Readium Web Publication Manifest](https://readium.org/webpub-manifest/), a JSON manifest format for distributing publications on the Web
* [Readium Licensed Content Protection (LCP)](https://readium.org/lcp-specs/), an interoperable DRM scheme for packaged publications
* [Readium License Status Document (LSD)](https://readium.org/lcp-specs/releases/lsd/latest/), a REST protocol that provides additional controls over a DRM license

A separate list of LCP adopters is maintained by EDRLab [here](https://www.edrlab.org/readium-lcp/certified-apps-servers/).

## Live examples

* [Readium Playground](https://playground.readium.org), a reference deployment of Thorium Web, meant for playing with the capabilities of Readium technologies
* [Readium Speech](https://readium.org/speech/demo), a cross-platform voice selector demo
* [Flatland (De Marque)](https://player.cantookaudio.com/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL3JlYWRpdW0vd2VicHViLW1hbmlmZXN0L3JlZnMvaGVhZHMvbWFzdGVyL2V4YW1wbGVzL0ZsYXRsYW5kL21hbmlmZXN0Lmpzb24=) an audiobook published by Librivox distributed using [the audiobook profile](https://readium.org/webpub-manifest/profiles/audiobook) in De Marque's Audiobook Reader
* [Animeta! (xbreader)](https://labs.j-novel.club/embed/v2/PRT-OKSLU4Y) a manga distributed using [the Divina profile](https://readium.org/webpub-manifest/profiles/divina) in a fork of xbreader

## Apps based on Readium Mobile

[Readium Mobile](https://github.com/readium/mobile) is a toolkit for ebooks, PDF documents, audiobooks and comics written in Swift & Kotlin. It targets primarily Android, iOS and iPadOS but can also be useful to build macOS and Chrome OS apps. With hundreds of apps using Readium Mobile and an open license (BSD-3), it's impossible to track down every single app built on top of it. This list is meant to identify some of them, to illustrate its adoption around the world.

### Certified as Readium LCP compliant

* 🇳🇴 [Allbok](https://www.allbok.no/) (Bokbasen)
  * [Apple AppStore](https://apps.apple.com/no/app/allbok/id1485392740)
  * [Google Play Store](https://play.google.com/store/apps/details?id=no.bokbasen.allbok)
* 🇫🇷 [Baobab](https://baobabapp.com) (Dilicom, built by ABM)
  * [Apple AppStore](https://apps.apple.com/fr/app/baobab-app/id1364023895)
  * [Google Play Store](https://play.google.com/store/apps/details?id=com.baobabapp.baobab)
* 🇸🇪 [Bibblix](https://bibblix.se/) (Stockholm Public Library)
  * [Apple AppStore](https://itunes.apple.com/se/app/bibblix/id1086942072)
  * [Google Play Store](https://play.google.com/store/apps/details?id=se.stockholm.bibblix)
* 🇪🇸 [Biblio-e Instituto Cervantes](https://cervantes.org/es/sobre-nosotros/app-moviles-ic) (Spain's Ministry of Culture)
  * [Apple AppStore](https://apps.apple.com/us/app/biblio-e-instituto-cervantes/id1555225654)
  * [Google Play Store](https://play.google.com/store/apps/details?id=com.demarque.cervantes)
* 🇵🇹 [BiblioLED](https://www.biblioled.gov.pt/)
  * [Apple AppStore](https://apps.apple.com/pt/app/biblioled/id6670559776)
  * [Google Play Store](https://play.google.com/store/apps/details?id=com.demarque.biblioled)
* 🇩🇰 [Biblio Library](https://publizon.com/) (Publizon by WeDoBooks)
  * [Apple AppStore](https://apps.apple.com/us/app/biblio-library/id1286685079)
  * [Google Play Store](https://play.google.com/store/apps/details?id=com.Axiellmedia.LibraryApp)
* 🇸🇪 [Bokus Reader](https://www.bokus.com/) (Bokus AB - bokusgruppen)
  * [Apple Store](https://apps.apple.com/fr/app/bokus-reader/id6446397156)
  * [Google Play Store](https://play.google.com/store/apps/details?id=com.bokus.reader)
* 🇺🇸 [Bookshop.org](https://www.bookshop.org/ebooks)
  * [Apple Store](https://apps.apple.com/us/app/bookshop-org/id6465290096)
  * [Google Play Store](https://play.google.com/store/apps/details?id=org.bookshop.app)
* 🇨🇦 [Cantook by Aldiko](https://www.demarque.com/) (De Marque)
  * [Apple AppStore](https://apps.apple.com/fr/app/cantook-par-aldiko/id1476410111)
  * [Google Play Store](https://play.google.com/store/apps/details?id=com.aldiko.android)
* 🇬🇧 [Christian360](www.christian360.com) (Christian360 Ltd - Eden Ecommerce Ltd)
  * [Apple Store](https://apps.apple.com/us/app/christian360/id1669286686)
  * [Google Play Store](https://play.google.com/store/apps/details?id=com.christian360.android)
* 🇺🇦 [Chytanka](https://chytanka.com/) (Chytanka.com, built by Beleven)
  * [Apple AppStore](https://apps.apple.com/us/app/%D1%87%D0%B8%D1%82%D0%B0%D0%BD%D0%BA%D0%B0/id1543172038)
  * [Google Play Store](https://play.google.com/store/apps/details?id=com.beleven.chytanka)
* 🇮🇳 [Classplus](https://classplusapp.com) (Bunch Microtechnologies Pvt Ltd)
  * [Apple Store](https://apps.apple.com/us/app/classplus/id1324522260)
  * [Google Play Store](https://play.google.com/store/apps/details?id=my.classroom.app)
* 🇪🇸 [eBiblio](https://ebiblio.es/) (Spain's Ministry of Culture)
  * [Apple AppStore](https://apps.apple.com/es/app/ebiblio/id1541822581)
  * [Google Play Store](https://play.google.com/store/apps/details?id=com.demarque.ebiblio)
* 🇰🇪 [eKitabu](https://www.ekitabu.com/)
  * [Google Play Store](https://play.google.com/store/apps/details?id=com.ekitabu.ereader)
* 🇫🇮 [E-Kirjasto](https://www.kansalliskirjasto.fi/fi/e-kirjasto) (National Library of Finland)
  * [Apple Store](https://apps.apple.com/fr/app/e-kirjasto/id6471490203)
  * [Google Play Store](https://play.google.com/store/apps/details?id=fi.kansalliskirjasto.ekirjasto)
* 🇬🇧 [Glassboxx](https://glassboxx.co.uk/)
  * [Apple AppStore](https://apps.apple.com/gb/app/glassboxx/id1464705712)
  * [Google Play Store](https://play.google.com/store/apps/details?id=uk.co.firstygroup.glassboxx)
* 🇭🇰 [Inspirata ebooks](https://ebook.endao.co/index-Reader)
  * [Apple AppStore](https://apps.apple.com/us/app/恩道電子書-inspirata-ebooks/id1463909109)
  * [Google Play Store](https://play.google.com/store/apps/details?id=life.tti.readerui)
* 🇪🇬 [iRead](https://shop.ireadhub.com/)
  * [Apple Store](https://apps.apple.com/eg/app/iread-app/id1475743219)
  * [Google Play Store](https://play.google.com/store/apps/details?id=com.vl.iread)
* 🇱🇰 [KReader](https://www.kbooks.lk/)
  * [Google Play Store](https://play.google.com/store/apps/details?id=lk.kreader.android)
* 🇮🇹 [MLOL Ebook Reader](https://www.medialibrary.it/help/appinfo.aspx) (Horizons Unlimited)
  * [Apple AppStore](https://apps.apple.com/it/app/mlol-ebook-reader/id1516845341)
  * [Google Play Store](https://play.google.com/store/apps/details?id=it.horizons.mlolreaderlcp)
* 🇰🇪 [NABU Reader](https://thenewpublishingstandard.com/2020/10/10/nabu-digital-reading-app-launches-in-kenya-with-free-content-in-english-and-kiswahili/)
  * [Apple AppStore](https://apps.apple.com/fr/app/nabu-org/id1483607930)
  * [Google Play Store](https://play.google.com/store/apps/details?id=org.libraryforall.simplified)
* 🇺🇸 [NetGalley Shelf](https://www.netgalley.com/) (Firebrand Technologies)
  * [Apple AppStore](https://apps.apple.com/us/app/netgalley-shelf/id1499581600)
  * [Google Play Store](https://play.google.com/store/apps/details?id=com.netgalley.shelf)
* 🇩🇰 [Nota Bibliotek](https://nota.dk/services/nota-bibliotek-20-app)
  * [Apple AppStore](https://apps.apple.com/dk/app/nota-bibliotek-2-0/id1539941161)
  * [Google Play Store](https://play.google.com/store/apps/details?id=dk.nota.lyt4)
* 🇺🇸 [The Palace Project](https://thepalaceproject.org) (Lyrasis)
  * [Apple AppStore](https://apps.apple.com/us/app/the-palace-project/id1574359693)
  * [Google Play Store](https://play.google.com/store/apps/details?id=org.thepalaceproject.palace)
* 🇧🇬 [Ozon](https://www.ozone.bg) (Ozone Entertainment JSC)
  * [Apple AppStore](https://apps.apple.com/ru/app/ozon-товары-и-авиабилеты/id407804998)
  * [Google Play Store](https://play.google.com/store/apps/details?id=ru.ozon.app.android)
* 🇨🇦 [PretNumerique](https://www.pretnumerique.ca/) (Bibliopresto)
  * [Apple AppStore](https://apps.apple.com/ca/app/id1391138546)
  * [Google Play Store](https://play.google.com/store/apps/details?id=com.bibliopresto.pretnumerique)
* 🇨🇳 [Shanghai Library Reader](http://www.library.sh.cn/web/index.html)
  * [Apple AppStore](https://apps.apple.com/us/app/%E4%B8%8A%E6%B5%B7%E5%9B%BE%E4%B9%A6%E9%A6%86-shanghai-library/id408876565)
* 🇮🇹 [Torrossa Reader](https://www.torrossa.com/en/reader) (Casalini Libri)
  * [Apple AppStore](https://apps.apple.com/us/app/torrossa-reader/id1621262664)
  * [Google Play Store](https://play.google.com/store/apps/details?id=com.torrossa.reader)
* 🇬🇧 [uLibrary](https://www.ulverscroft.com/home.php?countryCode=UK) (Ulversoft Group)
  * [Apple AppStore](https://apps.apple.com/gb/app/ulibrary/id977511203)
  * [Google Play Store](https://play.google.com/store/apps/details?id=ulibrary.ulverscroftulibrary.co.uk.ulibrary)
* 🇫🇷 [Vivlio](https://www.vivlio.com)
  * [Apple AppStore](https://apps.apple.com/be/app/vivlio/id1512792763)
  * [Google Play Store](https://play.google.com/store/apps/details?id=com.vivlio.mobile.app)
* 🇪🇸 [Vivlio Casa del Libro](https://www.casadellibro.com/vivlio-ereader-ebooks)
  * [Apple AppStore](https://apps.apple.com/es/app/vivlio-casa-del-libro/id6445927450)
  * [Google Play Store](https://play.google.com/store/apps/details?id=com.casadellibro.lecturadigital)
* 🇷🇴 [Voxa](https://www.voxa.ro)
  * [Apple AppStore](https://apps.apple.com/ro/app/voxa-audiobooks-e-books/id1584777343)
  * [Google Play Store](https://play.google.com/store/apps/details?id=com.wolfpackdigital.voxa) 

### Other apps

* 🇸🇪 [Bläddra](https://kb.se/bladdra) (Kungliga Biblioteket)
  * [Apple AppStore](https://apps.apple.com/se/app/bläddra/id1501134109)
  * [Google Play Store](https://play.google.com/store/apps/details?id=se.kb.eboksappen)
* 🇺🇸 [cloudLibrary](https://www.yourcloudlibrary.com) (Bibliotheca)
  * [Apple AppStore](https://apps.apple.com/us/app/cloudlibrary-by-bibliotheca/id466446054)
  * [Google Play Store](https://play.google.com/store/apps/details?id=com.txtr.android.mmm)
* 🇸🇬 [SUSS Reader](https://www.suss.edu.sg/) (Singapore University of Social Sciences)
  * [Apple AppStore](https://apps.apple.com/sg/app/suss-reader-for-ebooks-epubs/id1477574366)
  * [Google Play Store](https://play.google.com/store/apps/details?id=sg.edu.suss.etp.sreader2)

## Compatible with Readium Web Publications

In addition to Readium projects, a number of other apps or open-source projects can support Readium Web Publications:

* [Epub.js](https://github.com/futurepress/epub.js/) - an ebook viewer written in JS
* [Vivliostyle](https://github.com/vivliostyle/vivliostyle.js) - a document and publication viewer written in JS
* [xbreader](https://github.com/chocolatkey/xbreader) - a manga viewer written in TypeScript

## Other toolkits related to Readium

* [React Native Readium](https://github.com/5-stones/react-native-readium) A react-native wrapper for Readium Mobile & Web
* [Iridium](https://github.com/Mantano/iridium) A Flutter port of Readium Mobile

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, all contributors waive all copyright and related neighboring rights to this work.

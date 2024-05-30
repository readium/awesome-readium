# Awesome Readium [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://readium.org/assets/logos/readium-logo.png" align="right" width="200">](http://readium.org/)

A list of lists of awesome [Readium](https://readium.org/) resources.

Readium is an open-source foundation dedicated to the development of software, standards and best practices for digital publications.

**Disclaimer:** This list is created for informational purposes only and the provided links do not constitute an endorsement, recommendation, or favoring by the Readium Foundation.

## Contents

* [Open Standards](#open-standards)
* [Documentation](#documentation)
* [Readium toolkits](#readium-toolkits)
* [Other toolkits related to Readium](#other-toolkits-related-to-readium)
* [Apps based on Readium Mobile](#apps-based-on-readium-mobile)
* [Apps based on Readium Desktop](#apps-based-on-readium-desktop)
* [Apps based on Readium Web](#apps-based-on-readium-web)
* [Compatible with Readium Web Publications](#compatible-with-readium-web-publications)
* [Examples & Experiments](#examples--experiments)

## Open Standards

The Readium community has developed several industrial open standards for publications:

* [Readium Web Publication Manifest](https://readium.org/webpub-manifest/) - specifies a JSON manifest format for distributing publications on the Web.
* [Readium Licensed Content Protection](https://readium.org/lcp-specs/) or LCP - specifies an interoperable DRM scheme for packaged publications.
* [Readium License Status Document](https://readium.org/lcp-specs/releases/lsd/latest/) or LSD - specifies a JSON document and REST protocol that provides additional controls over a DRM license.

A separate list of LCP adopters is maintained by EDRLab [here](https://www.edrlab.org/readium-lcp/certified-apps-servers/). 

## Documentation

* [Architecture](https://readium.org/architecture/) - overview of the architecture of all Readium projects
* [Locators](https://readium.org/architecture/models/locators/) - defines a JSON object for pointing into digital publications
* [Readium CSS](https://readium.org/readium-css/docs/) - defines a set of reference stylesheets for EPUB Reading Systems

## Readium toolkits

* [Swift toolkit](https://github.com/readium/swift-toolkit) Readium Mobile for iOS devices
* [Kotlin toolkit](https://github.com/readium/kotlin-toolkit) Readium Mobile for Android devices
* [TS toolkit](https://github.com/readium/ts-toolkit) Readium Web, client part
* [Go toolkit](https://github.com/readium/go-toolkit) Readium Web, server part
* [Readium Desktop](https://github.com/readium/kotlin-toolkit) The Node.js navigator used in Thorium Desktop (EDRLab)
* [Readium CSS](https://github.com/readium/readium-css) The reading CSS used in every Readium toolkit

## Other toolkits related to Readium

* [React Native Readium](https://github.com/5-stones/react-native-readium) A react-native wrapper for Readium Mobile & Web
* [Iridium](https://github.com/Mantano/iridium) A Flutter port of Readium Mobile

## Apps based on Readium Mobile

[Readium Mobile](https://github.com/readium/mobile) is a toolkit for ebooks, audiobooks and comics written in Swift & Kotlin.

* [Allbok](https://www.allbok.no/) (Bokbasenn Norway) - available on [Apple AppStore](https://apps.apple.com/no/app/allbok/id1485392740), [Google Play Store](https://play.google.com/store/apps/details?id=no.bokbasen.allbok)  [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Baobab](https://baobabapp.com) (Dilicom, by ABM) - available on [Apple AppStore](https://apps.apple.com/fr/app/baobab-app/id1364023895), [Google Play Store](https://play.google.com/store/apps/details?id=com.baobabapp.baobab&hl=fr&gl=FR)  [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Beleven](https://chytanka.com/) (Estonia; Chytanka.com, Ukrain) - available on [Apple AppStore](https://apps.apple.com/us/app/%D1%87%D0%B8%D1%82%D0%B0%D0%BD%D0%BA%D0%B0/id1543172038), [Google Play Store](https://play.google.com/store/apps/details?id=com.beleven.chytanka&hl=uk&gl=US)  [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Bibblix](https://bibblix.se/) (Stockholm Public Library, Sweden) - available on [Apple AppStore](https://itunes.apple.com/se/app/bibblix/id1086942072), [Google Play Store](https://play.google.com/store/apps/details?id=se.stockholm.bibblix)  [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Biblio Library](https://publizon.com/) (Publizon - formerly Axiell Media) - available on [Apple AppStore](https://apps.apple.com/us/app/biblio-library/id1286685079), [Google Play Store](https://play.google.com/store/apps/details?id=com.Axiellmedia.LibraryApp)  [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Bläddra](https://kb.se/bladdra) (Kungliga Biblioteket, Sweden) available on [Apple AppStore](https://apps.apple.com/se/app/bläddra/id1501134109), [Google Play Store](https://play.google.com/store/apps/details?id=se.kb.eboksappen) 
* [Brio Reader](https://actessudaudio.boutique.edenlivres.fr/fr/pages/brio-reader) (Eden Livres, France) available on [Apple AppStore](https://apps.apple.com/fr/app/brio-reader/id1475894718), [Google Play Store](https://play.google.com/store/apps/details?id=com.eden.brioreader)  [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Bookbeat](https://www.bookbeat.com) available on [Apple AppStore](https://apps.apple.com/us/app/id1056652614)
* [Bokus Reader](https://www.bokus.com/) (Bokus AB - bokusgruppen) available on [Apple Store] (https://apps.apple.com/fr/app/bokus-reader/id6446397156) [Google Play Store](https://play.google.com/store/apps/details?id=com.bokus.reader&hl=en_US) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Cantook by Aldiko](https://www.demarque.com/) (De Marque) available on [Apple AppStore](https://apps.apple.com/fr/app/cantook-par-aldiko/id1476410111), [Google Play Store](https://play.google.com/store/apps/details?id=com.aldiko.android)  [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [cloudLibrary](https://www.yourcloudlibrary.com) (Bibliotheca, USA) available on [Apple AppStore](https://apps.apple.com/us/app/cloudlibrary-by-bibliotheca/id466446054), [Google Play Store](https://play.google.com/store/apps/details?id=com.txtr.android.mmm)
* [Christian360](www.christian360.com)(Christian360 Ltd - Eden Ecommerce Ltd) available on [Apple Store](https://apps.apple.com/us/app/christian360/id1669286686) [Google Play Store](https://play.google.com/store/apps/detailsid=com.christian360.android&hl=en&gl=US)[![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue) (https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Classplus] (https://classplusapp.com) available on [Apple Store] (https://apps.apple.com/us/app/classplus/id1324522260) [Google Play Store] (https://play.google.com/store/apps/details?id=my.classroom.app&hl=en&gl=US) ![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [DITA Reader](https://www.linkedin.com/company/d-i-t-a/) (DITA, USA) available on [Apple AppStore](https://apps.apple.com/us/app/dita-reader/id1274807900), [Google Play Store](https://play.google.com/store/apps/details?id=com.aferdita.urms.reader) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [eKitabu](https://www.ekitabu.com/) (eKitabu, Kenya) available on [Google Play Store](https://play.google.com/store/apps/details?id=com.ekitabu.ereader) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [E-Kirjasto] (https://www.kansalliskirjasto.fi/fi/e-kirjasto)(National Library of Finland) available on [Apple Store] (https://apps.apple.com/fr/app/e-kirjasto/id6471490203)[ Google Play Store] (https://play.google.com/store/apps/details?id=fi.kansalliskirjasto.ekirjasto&hl=fr_CH&gl=US) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Gantec EasyReadz](https://www.ebooks2go.com/ereader) (Gantec publishing, USA) available on [Google Play Store](https://play.google.com/store/apps/details?id=com.ebooks2go_mobile_app) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Glassboxx](https://glassboxx.co.uk/) (Glassboxx, UK) available on [Apple AppStore](https://apps.apple.com/gb/app/glassboxx/id1464705712), [Google Play Store](https://play.google.com/store/apps/details?id=uk.co.firstygroup.glassboxx) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Glassboxx for Columbia University Press] (https://cup.columbia.edu/) available on [Apple Store](https://apps.apple.com/us/app/columbia-university-press/id6450259271), [Google Play Store](https://play.google.com/store/apps/details?id=uk.co.glassboxx.cup&hl=en&gl=US) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Glassboxx eLearning](https://glassboxx.co.uk/) (Glassboxx, UK) available on [Apple AppStore](https://apps.apple.com/us/app/glassboxx-elearning/id1474971723), [Google Play Store](https://play.google.com/store/apps/details?id=uk.co.firstygroup.elearning) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Glassboxx for Edinburgh University Press](https://www.euppublishing.com/) (UK) available on [Apple AppStore](https://apps.apple.com/us/app/edinburgh-university-press/id6449391234), [Google Play Store](https://play.google.com/store/apps/details?id=uk.co.glassboxx.eup) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Glassboxx for Fordham University Press] (https://www.fordhampress.com/) available on [Apple Store](https://apps.apple.com/gb/app/fordham-university-press/id1663778584), [Google Play Store](https://play.google.com/store/apps/details?id=uk.co.glassboxx.fordham&hl=en&gl=US) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Glassboxx for hopeBooks](https://hopebooks.com.au) (hopebooks, Australia) available on [Apple AppStore](https://apps.apple.com/au/app/hope-books/id1609579613), [Google Play Store](https://play.google.com/store/apps/details?id=uk.co.glassboxx.hopebooks) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Glassboxx for Leaf e-Reader] (https://leaf.glassboxx.com/auth1.php) available on [Apple Store](https://apps.apple.com/us/app/leaf-e-reader/id6467753185), [Google Play Store](https://play.google.com/store/apps/details?id=uk.co.glassboxx.lon&hl=en&gl=US) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Glassboxx for Living Reader] (https://www.tyndale.com/stories/living-reader-app-your-digital-library-tyndale-ebooks-and-audiobooks) available on [Apple Store](https://apps.apple.com/us/app/living-reader/id6444275050), [Google Play Store] (https://play.google.com/store/apps/details?id=uk.co.glassboxx.tyndale&hl=en&gl=US) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* Glassboxx for Macmillan Publishers](https://us.macmillan.com/) available on [Apple Store](https://apps.apple.com/fr/app/macmillan-publishers/id6445850725), [Google PlayStore](https://play.google.com/store/apps/details?id=uk.co.glassboxx.macus&hl=en&gl=US) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Glassboxx for Princeton University Press] (https://press.princeton.edu/) available on [Apple Store](https://apps.apple.com/us/app/princeton-university-press/id1645831611), [Google Play Store](https://play.google.com/store/apps/details?id=uk.co.glassboxx.princeton&hl=en&gl=US)  [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Glassboxx for readingHouse](https://thereadinghouse.co.uk) (The Reading House, UK) available on [Google Play Store]() [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Glassboxx for SFGateway](https://www.sfgateway.com) (SFGateway, UK) available on [Apple AppStore](https://apps.apple.com/gb/app/sf-gateway/id1547970167), [Google Play Store](https://play.google.com/store/apps/details?id=uk.co.glassboxx.sfgateway) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Glassboxx for Uni. of West Indies Press] (https://www.uwipress.com/) available on [Apple Store](https://apps.apple.com/au/app/uni-of-west-indies-press/id1658481955), [Google Play Store](https://play.google.com/store/apps/details?id=uk.co.glassboxx.uwip&hl=en&gl=US) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Glassboxx for Yale University Press] (https://yalebooks.yale.edu/) available on [Apple Store](https://apps.apple.com/sg/app/yale-university-press/id6451439398), [Google Play Store](https://play.google.com/store/apps/details?id=uk.co.glassboxx.yup&hl=en&gl=US) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/) 
* [Inspirata ebooks](https://ebook.endao.co/) (Inspirata, Hong Kong) available on [Apple AppStore](https://apps.apple.com/us/app/恩道電子書-inspirata-ebooks/id1463909109), [Google Play Store](https://play.google.com/store/apps/details?id=life.tti.readerui) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [iRead](https://shop.ireadhub.com/) (iRead) available on [Apple Store] (https://apps.apple.com/eg/app/iread-app/id1475743219 ) [Google Play Store] (https://play.google.com/store/apps/details?id=com.vl.iread&hl=en) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [KReader](https://www.kbooks.lk/)(KReader Pvt Ltd) available on [Google Play Store] (https://play.google.com/store/apps/detailsid=lk.kreader.android&hl=en) 
* [MLOL Ebook Reader](https://www.medialibrary.it) (medialibraryonline, Italy) available on [Apple AppStore](https://apps.apple.com/it/app/mlol-ebook-reader/id1516845341?l=en), [Google Play Store](https://play.google.com/store/apps/details?id=it.horizons.mlolreaderlcp&hl=en&gl=US) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [NABU Reader](https://thenewpublishingstandard.com/2020/10/10/nabu-digital-reading-app-launches-in-kenya-with-free-content-in-english-and-kiswahili/) (publisher) available on [Apple AppStore](https://apps.apple.com/fr/app/nabu-org/id1483607930), [Google Play Store](https://play.google.com/store/apps/details?id=org.libraryforall.simplified) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [NetGalley Shelf](https://www.netgalley.com/) (USA) available on [Apple AppStore](https://apps.apple.com/us/app/netgalley-shelf/id1499581600), [Google Play Store](https://play.google.com/store/apps/details?id=com.netgalley.shelf) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Ozon: товары и авиабилеты](https://www.ozone.bg) (Ozone Entertainment JSC, Bulgaria) available on [Apple AppStore](https://apps.apple.com/ru/app/ozon-товары-и-авиабилеты/id407804998), [Google Play Store](https://play.google.com/store/apps/details?id=ru.ozon.app.android) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [PUBNiTO Book Reader] (https://www.notionwave.com/) available on [Apple Store] (https://apps.apple.com/us/app/pubnito-book-reader/id6461774046) [Google Play Store] (https://play.google.com/store/apps/details?id=com.notionwave.pubnito&hl=en&gl=US) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [PretNumerique](https://www.pretnumerique.ca/) (Canada) available on [Apple AppStore](https://apps.apple.com/ca/app/id1391138546), [Google Play Store](https://play.google.com/store/apps/details?id=com.bibliopresto.pretnumerique) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [SaxoAccess] (https://pubfront.com/)(Pubfront APS) available on [Apple Store] (https://apps.apple.com/uy/app/saxo-access/id6468798982) [Google Play Store] (https://play.google.com/store/apps/details?id=com.saxoaccess.app&hl=fr) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Shanghai Library Reader](http://www.library.sh.cn/web/index.html) (Shanghai Library, China) available on [Apple AppStore](https://apps.apple.com/us/app/%E4%B8%8A%E6%B5%B7%E5%9B%BE%E4%B9%A6%E9%A6%86-shanghai-library/id408876565) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [SUSS Reader](https://www.suss.edu.sg/) (Singapore University of Social Sciences) available on [Apple AppStore](https://apps.apple.com/sg/app/suss-reader-for-ebooks-epubs/id1477574366), [Google Play Store](https://play.google.com/store/apps/details?id=sg.edu.suss.etp.sreader2) 
* [The Palace Project](https://thepalaceproject.org) (Lyrasis & DPLA, USA) available on [Apple AppStore](https://apps.apple.com/us/app/the-palace-project/id1574359693), [Google Play Store](https://play.google.com/store/apps/details?id=org.thepalaceproject.palace)
* [Torrossa Reader](https://www.torrossa.com/) (Casalini Libri, Italy) available on [Apple AppStore](https://apps.apple.com/us/app/torrossa-reader/id1621262664), [Google Play Store](https://play.google.com/store/apps/details?id=com.torrossa.reader) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [uLibrary](https://www.ulverscroft.com/home.php?countryCode=UK) (Ulversoft Group, UK) available on [Apple AppStore](https://apps.apple.com/gb/app/ulibrary/id977511203), [Google Play Store](https://play.google.com/store/apps/details?id=ulibrary.ulverscroftulibrary.co.uk.ulibrary) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Vivlio](https://www.vivlio.com) (Vivlio, France) available on [Apple AppStore](https://apps.apple.com/be/app/vivlio/id1512792763?l=fr), [Google Play Store](https://play.google.com/store/apps/details?id=com.vivlio.mobile.app) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Voxa](https://www.voxa.ro) (Voxa Software, Romania) available on [Apple AppStore](https://apps.apple.com/ro/app/voxa-audiobooks-e-books/id1584777343), [Google Play Store](https://play.google.com/store/apps/details?id=com.wolfpackdigital.voxa) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Xeread](https://xeread.xebook.es) (Xercode, Spain) available on [Google Play Store](https://play.google.com/store/apps/details?id=es.xeread.read) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/) 

## Apps based on Readium Desktop

[Readium Desktop](https://github.com/readium/desktop) is a toolkit for ebooks, PDF documents, audiobooks and comics written Typescript, using node.js and Electron.js, for use on Windows, MacOS and Linux.

The applications listed below have been developed out of Thorium Reader, which is also open-source. 

* [Thorium Reader](https://www.edrlab.org/software/thorium-reader/) (EDRLab) available on the product page of from the [Windows Store](https://bit.ly/thoriumreader-en) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [eKitabu e-reader](https://www.ekitabu.com/) (eKitabu, Kenya) available from the [Windows Store](https://www.microsoft.com/en-us/p/ekitabu-e-reader/9mtzsjs9jsvw?SilentAuth=1&wa=wsignin1.0&activetab=pivot:overviewtab) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Glassboxx](https://glassboxx.co.uk/) (Glassboxx, UK) available from the [product page](https://glassboxx.com/glassboxx-downloads/) and the [Windows Store](https://www.microsoft.com/en-us/p/glassboxx/9nzklr5v4fq6?activetab=pivot:overviewtab) [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [MLOL Ebook Reader](https://www.medialibrary.it) (medialibraryonline, Italy) available [here](https://www.medialibrary.it/pagine/pagina.aspx?id=881)  [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Xeread](https://xeread.xebook.es) (Xercode, Spain) available [here]()  [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Inspirata ebooks](https://ebook.endao.co/index-Reader) (Inspirata, Hong Kong) available [here]()  [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)
* [Torrossa Reader](https://www.casalini.it) (Casalin Libri, Italy) available [here]()  [![Readium LCP Certified](https://img.shields.io/badge/Readium%20LCP-Certified-blue)](https://www.edrlab.org/readium-lcp/certified-apps-servers/)

## Other Desktop Apps

Using Readium JS:
* [Wiley eText (MacOS)](https://apps.apple.com/fr/app/wiley-etext/id1523684519) - an education reader developed by Wiley Publishing. (Has been [removed](https://web.archive.org/web/20220320041556/https://apps.apple.com/us/app/id1523684519) from the US app store.) 

## Apps based on Readium Web

...

## Compatible with Readium Web Publications

In addition to Readium projects, a number of other apps or open-source projects can support Readium Web Publications:

* [Epub.js](https://github.com/futurepress/epub.js/) - an ebook viewer written in JS
* [Vivliostyle](https://github.com/vivliostyle/vivliostyle.js) - a document and publication viewer written in JS
* [xbreader](https://github.com/chocolatkey/xbreader) - a manga viewer written in TypeScript

## Examples & Experiments

* [Animeta! (xbreader)](https://j-novel.club/mc/animeta-volume-1-chapter-1) - first chapter of a manga distributed using RWPM (Readium Web Publication Manifest) in a fork of xbreader.
* [Herland (Jellybooks)](https://www.jellybooks.com/cloud_reader/books/herland) - a classic distributed using RWPM in Jellybooks' take on Readium Web.
* [Readium CSS Documentation (Vivliostyle)](https://vivliostyle.github.io/vivliostyle.js/viewer/vivliostyle-viewer.html#b=https://readium.org/readium-css/docs/manifest.json) - Readium CSS documentation in Vivliostyle Viewer using RWPM.
* [Tom Sawyer (De Marque)](https://player.cantookaudio.com/aHR0cHM6Ly9hcGkuYXJjaGl2ZWxhYi5vcmcvYm9va3MvdG9tX3Nhd3llcl9saWJyaXZveC9vcGRzX2F1ZGlvX21hbmlmZXN0) - Tom Sawyer as an audiobook published by Librivox using RWPM in De Marque's Audiobook Reader.
* [webpub-viewer](https://github.com/HadrienGardeur/webpub-viewer) - an `iframe` based navigator for ebooks, written in JS
* [comics-viewer](https://github.com/HadrienGardeur/comics-viewer) - an `img` based navigator for comics, written in JS
* [audiobook-player](https://github.com/HadrienGardeur/audiobook-player) - an `audio` based navigator for audiobooks, written in JS


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, all contributors waive all copyright and related neighboring rights to this work.

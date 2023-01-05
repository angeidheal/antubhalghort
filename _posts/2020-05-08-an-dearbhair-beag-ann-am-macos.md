---
id: 77
title: 'An Dearbhair Beag ann am macOS'
date: '2020-05-08T15:00:24+00:00'
author: 'Crìstean MacMhìcheil'
layout: post
guid: 'https://macmhicheil.scot/?p=77'
permalink: /2020/05/08/an-dearbhair-beag-ann-am-macos/
image: /images/posts/an-dearbhar-beag-macos.png
categories:
    - Apple
    - Gàidhlig
    - Litreachadh
tags:
    - 'An Dearbhair Beag'
    - Gaelic
    - Gàidhlig
    - Hunspell
    - litreachadh
    - 'Mac OS X'
    - macOS
---

Tha an Dearbhair Beag ’na dhearbhair-litreachaidh a tha stèidhichte air stòr-dàta nam faclan a tha san Fhaclair Bheag agus is esan an dearbhair as motha a tha ri fhaighinn aig an àm seo. Tha e air a fhilleadh ann an tionndaidhean Gàidhlig de na prògraman LibreOffice, OpenOffice agus Firefox o thùs. Is e adhbhar am post seo ge-tà sealltainn dhut mar a ghabhas a chleachdadh le taghadh nas fharsainge de phrògraman ann am MacOS.

### A’ stàladh an dearbhair

An toiseach, feumar Homebrew a stàladh.

1. Fosgail a’ phrògram Terminal. Faodaidh tu a lorg ann an Applications -&gt; Utilities.
2. Cuir ann na leanas /bin/bash -c “$(curl -fsSL <https://raw.githubusercontent.com/Homebrew/install/master/install.sh>)” agus brùth an iuchair cuir a-steach.
3. Cuir a-steach am facal-faire cleachdaiche agad ma thèid iarraidh ort. (Cha tèid a thaisbeanadh air an scrìon nuair a tha thu ga thaidhpeadh mar sin dìreach taidhp e agus brùth an iuchair cuir a-steach.)
4. Fuirich airson a’ chomannd a bhith deiseil.

Nuair a tha Homebrew air a stàladh, feumaidh tu Hunspell a stàladh.

1. Fosgail “Terminal”, mura h-eil e fosgailte mar thà.
2. Cuir ann na leanas brew install hunspell agus brùth air an iuchair cuir a-steach.
3. Fuirich airson a’ chomannd a bhith deiseil.

An uairsin, tha thu deiseil airson an dearbhair fhèin a stàladh.

1. Faodar an dreach as ùire a lorg aig <https://extensions.libreoffice.org/extensions/an-dearbhair-beag-scottish-gaelic-spellchecker> (Is e 3.3 am fear as ùire nuair a sgrìobh mi seo.)
2. Nuair a tha thu air seo a luchdachadh sìos feumaidh a ath-ainmeachadh bho hunspell-gd-3.3.oxt gu hunspell-gd-3.3.zip.
3. Dì-dhùmhlaich am faidhle zip agus gheibh thu pasgain hunspell-gd-3.3.
4. Fosgail am pasgain seo, agus bu chòir dhut am pasgain Dictionaries a lorg le dà fhaidhle na bhroinn: gd\_GB.aff agus gd\_GB.dic.
5. Tagh an dà fhaidhle seo agus gluais iad gu ~/Library/Spelling/ no /Library/Spelling/

### A’ cleachdadh an dearbhair

1. Fosgail prògram sgrìobhaidh a-leithid Notes no TextEdit.
2. Brùth air Edit anns a’ bhar-taice agus air Spelling and Grammar -&gt; Show Spelling and Grammar.
3. Atharraich Automatic by Language gu Gàidhlig.
4. Dùin a’ bhogsa Spelling and Grammar.
5. Faodaidh tu tòiseachadh air sgrìobhadh.
6. Chi thu loidhne dearg fo fhaclan ceàrr agus faodaidh tu brùthadh orra leis a’putan-lucha deas gus an ceartachadh. Air neo faodaidh tu an sgrìobhainn air fad a cheartachadh le bhith a’ fosgladh Spelling and Grammar a-rithist (ceum 2).

Gu mì-fhortanach, chan obraich e leis a h-uile prògram, MS Word mar eisimpleir, ach bu chòir dha obrachadh anns a’ chuid as motha de na prògaman a bhios a’ cleachdadh dearbhair MacOS fhèin.

# Stórt verkefni 1 - Vefforritun
## Höfundar: Atli, Halldór og Hjalti

Atli Fannar Franklín, aff6. Nemandi á fyrsta ári í HÍ í stærðfræði og tölvunarfræði.

Halldór Benediktsson, halldbe. Nemandi á fyrsta ári í Tölvunarfræði.

Hjalti Daníelsson, hjd1. Nemandi á lokaönn í Tölvunarfræði til B.S. gráðu í HÍ.

## Keyrsla
1. Ná í Node.js af nodejs.org og setja það upp
2. Keyra command prompt
3. Fara í vinnumöppu
4. Gera öll forritin klár, sjá töflu

Skipanir | Útskýring
--- | ---
`npm install` | _Installar pakka sem eru í lista í package.json (linter, browser-sync og node-sass)_
`npm run dev` | _Opnar síðu í browser og keyrir scss-compiler_
`npm run lint -s` | _Keyrir linter með supressed output. Sýnir bara linter villur, outputtar engu ef engar linter villur finnast_

## Hlutverk scss skráa:

#### styles.scss

Aðal scss skráin. Þessi skrá skilgreinir nokkur grunnatriði og kallar svo á allar aðrar scss skrár.

#### about.scss

Efni í um.html.

#### backimage.scss

Stóru bakgrunnsmyndirnar á um og kaupa síðum og allt innan þeirra.

#### button.scss

Takkar á öllum síðum, nema í navbar.

#### footer.scss

Footer, með upplýsingum um fooþjónustuna sem finna má á hverri síðu.

#### frontimage.scss

Stóra bakgrunnsmyndin á index síðu og allt innan hennar.

#### grid.scss

Stýrir hegðun megingrindar síðanna ásamt hegðun dálka og lína innan þess.

#### infoblock.scss

Lýsir hegðun dálka af input elementum á kaupa síðu ásamt hegðun elementa innan þess.

#### navbar.scss

Navbars á hverri síðu og allt innan hans.

#### points.scss

Lýsir hegðun myndar og punkta um fooþjónustuna sem finna má beint fyrir neðan forsíðumyndina á forsíðu.

#### purchase.scss

Kaupa takki og texti neðst á forsíðu, fyrir ofan footer.

#### testament.scss

Lýsir hegðun hringlótta mynda með tilvitnunum á forsíðu.

## HTML skrár:

#### index.html

Lýsir byggingu forsíðar fooþjónustunnar. Þar eru meðmæli, ummæli og tenglar yfir á hinar síðurnar.

#### um.html

Undirsíða með texta um fooþjónustuna og stofnanda hennar.

#### kaupa.html

Undirsíða með form til að setja inn upplýsingar til að geta keypt áskrift að fooþjónustunni.

## Myndir:

#### bg-subpage.jpg

Bakgrunnsmynd sem birtist á kaupa og um síðu.

#### bg.jpg

Bakgrunnsmynd sem birtist á forsíðu.

#### check.svg

Haki sem birtist í points elementum á forsíðu.

#### favicon.png

Mynd sem birtist í tabinu í browser til að hægt sé að þekkja síðuna.

#### image.jpg

Mynd sem birtist á forsíðu við hliðina á pointum.

#### profile1.jpg, profile2.jpg, profile3.jpg

Myndir af meðmælendum sem birtast í testament elementum.

# Stórt verkefni 1 - Vefforritun
### Höfundar: Atli, Halldór og Hjalti

#### Atli:

#### Halldór:  
1. max-width 1200px eða?
  * Ef það er max-width á að láta navbar content fylgja eða ekki?
2. 0.3s, 1.3s og 2.3s í stað 1s, 2s og 3s eins og sagt er í fyrirmælum?
  * Persónulega finnst mér það betra að hafa hratt vegna þess að þetta keyrir í hvert sinn sem síðan er refreshed. Búinn að athuga og það er ekki hægt að stoppa það án JS.
3. Skrifa .md skrá um keyrslu, skil ekki alveg hvað er átt við.
4. HTML uppsetning?
  * persónulega finnst mér betra að hafa bil á milli t.d. sections og já mér finnst gott að nota eins mörg mismunandi elements, ekki bara vegna þess að það er merkingafræðilega rétt heldur er það líka læsilegra.


#### Hjalti:



### Keyrsla
1. Ná í Node.js af nodejs.org og setja það upp
2. Keyra command prompt
3. Fara í vinnumöppu
4. Gera öll forritin klár, sjá töflu

Skipanir | Útskýring
--- | ---
`npm install` | _Installar pakka sem eru í lista í package.json (linter, browser-sync og node-sass)_
`npm run dev` | _Opnar síðu í browser og keyrir scss-compiler_
`npm run lint -s` | _Keyrir linter með supressed output. Sýnir bara linter villur, outputtar engu ef engar linter villur finnast_

### Hlutverk scss skráa:

#### about.scss

Stýrir hegðun á texta í um.html.

#### backimage.scss

Stýrir hegðun stóru bakgrunnsmyndarinnar á um og kaupa síðum og hluta innan þess.

#### button.scss

Lýsir útliti alla takka, sem dreifast víða um síðurnar.

#### footer.scss

Lýsir útliti footers með upplýsingum um fooþjónustuna sem finna má á hverri síðu.

#### frontimage.scss

Stýrir hegðun stóru bakgrunnsmyndarinnar á index síðu og hluta innan þess.

#### grid.scss

Stýrir hegðun megingrindar síðanna ásamt hegðun dálka og lína innan þess.

#### gridabout.scss

Lýsir fráviki grindar á um síðu frá hegðun aðalgrindarinnar.

#### infoblock.scss

Lýsir hegðun dálka af input elementum á kaupa síðu ásamt hegðun elementa innan þess.

#### navbar.scss

Lýsir hegðun navbars sem finna má efst á hverri síðu.

#### points.scss

Lýsir hegðun myndar og punkta um fooþjónustuna sem finna má beint fyrir neðan forsíðumyndina á forsíðu.

#### purchase.scss 

Lýsir hegðun og útliti kaupa takka neðst á forsíðu.

#### testament.scss

Lýsir hegðun hringlótta mynda með tilvitnunum á forsíðu (eru milli pointa og kaupa takka).

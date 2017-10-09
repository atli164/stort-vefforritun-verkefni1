# Stórt verkefni 1 - Vefforritun
### Höfundar: Atli, Halldór og Hjalti

### TODO:

1. Samræma px, em, vh/wh notkun
2. Setja inn merkingarfræðilega rétt element í html skjöl
3. Taka loka lint á scss eftir að breytingum lýkur
4. Implementa max width á grid
5. Sameina gridabout og grid
6. Breyta transition tímum
7. Elements síða?
8. Linta HTML skjöl einhvern veginn.

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

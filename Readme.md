# Stórt verkefni 1 - Vefforritun
### Höfundar: Atli, Halldór og Hjalti

#### Atli:
1. Svör við öðrum spurningum hér:
  * Halldór, 1: Sýnist ekki vera neitt slíkt á myndum.
  * Halldór, 2: Tel það afar góða hugmynd.
  * Halldór, 4: Uppsetning á npm, sass. Keyrsla (npm run lint, npm run dev etc.). Bara tæknileg atriði sem þú þarft að vita til að geta hlaðað niður þessu repo og sett upp síðuna sjálfur.

#### Halldór:  
1. max-width 1200px eða?
  * Ef það er max-width á að láta navbar content fylgja eða ekki?
2. Fooþjónustan í navbar sem linkur á upphafssíðu?
3. 0.3s, 1.3s og 2.3s í stað 1s, 2s og 3s eins og sagt er í fyrirmælum?
  * Persónulega finnst mér það betra að hafa hratt vegna þess að þetta keyrir í hvert sinn sem síðan er refreshed. Búinn að athuga og það er ekki hægt að stoppa það án JS.
4. Skrifa .md skrá um keyrslu, skil ekki alveg hvað er átt við.
5. HTML uppsetning?
  * persónulega finnst mér betra að hafa bil á milli t.d. sections og já mér finnst gott að nota eins mörg mismunandi elements, ekki bara vegna þess að það er merkingafræðilega rétt heldur er það líka læsilegra.


#### Hjalti:



### Keyrsla
1. Ná í Node.js af nodejs.org
2. Keyra command prompt
3. Fara í vinnumöppu
4. Gera öll forritin klár, sjá töflu

Skipanir | Útskýring
--- | ---
`npm install` | _Installar pakka sem eru í lista í package.json (linter, browser-sync og node-sass)_
`npm run dev` | _Opnar síðu í browser og keyrir scss-compiler_
`npm run lint -s` | _Keyrir linter með supressed output. Sýnir bara linter villur, outputtar engu ef engar linter villur finnast_

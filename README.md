# ProjektiLista
Erinäisiä projektejani 

Kokoelma pienempiä ja keskikokoisia projekteja, joissa on kokeiltu eri työkaluja, rajapintoja ja datankäsittelytapoja.

Fokus:
- käytännön toteutus; työnkulkujen harjoittelu & työkalujen yhdistäminen; datan keruu, tallennus ja jatkokäsittely
- toimivat työvälineet tekstien tuottamisen ja käsittelyn työnkulkuihin; hauskat kokeilut

---

## Projektitaulukko

| Projekti | Tyyppi | Teknologia / Stack | Ydinidea |
|----------|--------|-------------------|----------|
| 🛠️ InDesign / InCopy -skriptit | Desktop automaatio / julkaisu | InDesign/InCopy scripting (JS/ExtendScript), Word/RTF import | Julkaisuteksti, rakenteet | Rakenteisen tekstin hallinta ja automaatio (esim. hakemistot, viitteet, kommentit) |
| 🛠️ PDF / Word -tekstityökalut | Tekstin muotoilu | Python (PDF/Word parsing), fokus offline lokaalisti | PDF/Word-teksti | Tekstin siivous, muunnos |
| 🤖 Tekstianalyysiskriptit | Tekstianalyysi / data | Python (NLP Stanza, SpaCy, regex) | Tekstin kielelliset ominaisuudet, NER-entiteettilistaukset (henkilöt, organisaatiot, paikat) | Kustomoitu analyysi tekstiversioiden vertailuun ja NER-poimintoihin |
| 🎤 Teksti- ja puheloki-työkalu | Web-sovellus | Apps Script (web app), Google Sheets (tietokanta), HTML/JS (UI), Android (selain) | Rakenteinen mobiililokitus (teksti + aikaleima + sijainti) |
| 📅 Reading/Writing Calendar | Ajanhallinta / työnkulku | Kustomoitu HTML/JS (local tool), Excel | Projektinhallinta, työvaiheet | Tekstien aikataulutus ja etenemisen seuranta eri työvaiheissa |
| 🔍 Hakupikanäppäimet | Automaatio | AutoHotkey v2, Windows, selaimen URL-hakut | Pikanäppäimillä ohjattu haku (Kielitoimisto, Google, Synonyymit) |
| 🔍 Offline Highlight Tool | Selainlaajennus | JavaScript, Chrome/Edge (Manifest V3), Clipboard API, contextMenus API | Valitun tekstin kopiointi lähde-URL:n kanssa (offline) |
| 🗺️ Muinaisia mestoja | Kartta / dataputki / AI-rikastus| Excel PowerQuery (WFS), Museovirasto API, KYPPI, GenAI, Google Maps | API → siivous → rikastus → interaktiivinen kartta |
| 🗺️ Hiisi-paikannimet | Kartta / dataputki / AI-rikastus | Nimisampo, Sotasampo, Excel-käsittely, GenAI, Google Maps | Laaja nimidata → teematasot → karttatutkiminen |
| 🗺️ Arkeologiset alueet (Satakunta) | Kartta / dataputki / AI-rikastus | Kulttuuriympäristö API, KYPPI/VARK, GenAI, Google Maps | Kuratoitu paikkadata → tiivistys → karttakohteet |
| 🗺️ QGIS – paikkatietoanalyysi | Data-analyysi / GIS | QGIS, geodata, shapefiles, raster/vektori | Tutkimusdata, paikkatieto | Tutkimusdatan tarkastelu ja visualisointi paikkatiedon kautta |
| 🌄 QGIS + Blender – 3D maisemavisualisointi | Paikkatieto + 3D / visualisointi | QGIS, Blender, Python scripting, geodata (DEM/vektori) | Paikkatieto, korkeusdata, tutkimusdata | QGIS-datan muuntaminen 3D-maisemaksi ja visualisointi Blenderissä |
| 🧊 Blender – dataohjattu 3D | 3D / visualisointi | Blender, Python scripting, Excel-data | Taulukkomuotoinen data, 3D-objektit | Excel-datan visualisointi 3D-objektien avulla kustomoidulla skriptillä |
| 🤖 LLM fine-tuning (FI GPT-2) | NLP / mallikoulutus | Hugging Face (transformers, datasets), PyTorch, Colab (T4 GPU) | Pienen aineiston fine-tuning → tyylisiirtymä |
| 🌐 Wiki API -datakysely | Datahaku / API / SQL | Wikipedia/Wikidata API, SQL/queries, JSON | Wiki-data, rakenteinen tieto | Datan haku rajapinnasta SQL-tyyppisillä kyselyillä ja jatkokäsittely |
| 🧠 Opintomuistiinpanot & minisisällöt | Sisältöputki | ChatGPT, manuaalinen kuratointi, audio/video/grafiikkatyökalut | Muistiinpanot → jäsennys → minisisällöt |
| 🧠 Custom GPT:t | AI-konfiguraatio / promptikehitys | ChatGPT (custom GPTs), järjestelmäpromptit, ohjauspromptit | Käyttötapauskohtaiset GPT:t (räätälöity IT-tuki, tekstilähteiden tiivistäjät, tyylianalyysipohjaiset persoonat) |
| 🧰 Työkalut & ympäristöt | Kehitysympäristö / tooling | Anaconda/JupyterLab (Python), Colab, VS Code, Cursor, GitHub, JavaScript, AutoHotkey, Excel, R, Orange, QGIS, Blender, MSOffice, GoogleDocs/Sheets, Trados, Wordfast | Projektikehitys | Monityökalupohjainen kehitys eri käyttötarkoituksiin |

## Lisätietoja

🛠️ InDesign / InCopy -skriptit — Skriptit rakenteisen tekstin hallintaan & automatisointiin (hakemistot, viitteet, kommentit; tyylimääritykset) sekä Word/RTF-aineiston käsittelyyn osana InDesign-julkaisutyövuota.

🛠️ PDF / Word -tekstityökalut — Python-skriptit PDF- ja Word-tekstin siivoamiseen ja julkaisutyövuohon sopivaksi, painotus paikallisessa ja offline-käsittelyssä.

🤖 Tekstianalyysiskriptit — Python-pohjaiset työkalut tekstin kielellisten piirteiden tarkasteluun (spaCy/Stanza, regex), NER-poimintoja (henkilöt, organisaatiot, paikat) ja tekstiversioiden vertailua lokaalisti.

📅 Reading/Writing Calendar — Kustomoitu lokaali HTML/JS-työkalu tekstien käsittelyn suunnitteluun ja seurantaan; työ pilkotaan vaiheisiin ja aikataulutetaan kunkin työvaiheen mukaan lokaalisti.

🎤 Teksti- ja puheloki-työkalu — Selainpohjaine mobiilikäyttöön tehty kevyt lokityökalu, jossa käyttäjä syöttää tai sanelee tekstin ja data tallentuu Google Sheetiin aikaleiman ja sijainnin kanssa ilman ulkoisia API:ita. Helposti räätälöitävissä eri tarkoituksiin.

🔍 Hakupikanäppäimet — AutoHotkey-pohjainen Windows-työkalu, joka hakee valitun tekstin suoraan määritellyistä sanakirjoista ja hakukoneista pikanäppäimillä käyttäen samaa selainvälilehteä. 

🧩 Offline Highlight Tool — Chromium-selaimiin tehty laajennus, joka kopioi valitun tekstin ja lähde-URL:n leikepöydälle täysin paikallisesti ilman verkkoyhteyksiä tai backendia.

🗺️ Muinaisia mestoja — Rajapintapohjainen dataputki, jossa Museoviraston WFS-data haetaan Exceliin, siivotaan, rikastetaan AI:lla ja esitetään klikattavina kohteina kartalla.

🗺️ Hiisi-paikannimet — Laajan nimidatan yhdistely ja analyysi useista lähteistä, jonka tuloksena syntyy teematasoilla selattava karttavisualisointi.

🗺️ Arkeologiset alueet (Satakunta) — Kuratoitu paikkatietoaineisto, jossa viralliset kohdetiedot tiivistetään ja esitetään kartalla helposti selattavassa muodossa.

🗺️ QGIS – paikkatietoanalyysi — Tutkimusdatan tarkastelu ja visualisointi QGIS-ympäristössä paikkatiedon avulla (vektori- ja rasteriaineistot, karttatasot, alueelliset analyysit).

🌄 QGIS + Blender – 3D maisemavisualisointi — Paikkatiedon (esim. korkeusmallit ja karttatasot) käsittely QGIS:ssä ja siirto Blenderiin, jossa data muunnetaan 3D-maisemaksi ja visualisoidaan Python-skriptien avulla.

🧊 Blender – dataohjattu 3D — Python-skripteillä ohjattu 3D-työskentely Blenderissä, jossa Excel-muotoinen data muunnetaan visuaalisiksi objekteiksi ja rakenteiksi.

🤖 LLM fine-tuning (FI GPT-2) — Kokeellinen mallikoulutus, jossa suomenkielistä GPT-2-mallia hienosäädetään pienellä aineistolla tyylinsiirron tutkimiseksi.

🌐 Wiki API -datakysely — Datan haku Wikipedia/Wikidata-rajapinnoista SQL-tyyppisillä kyselyillä (esim. SPARQL), tulosten käsittely ja hyödyntäminen rakenteisena aineistona.

🧠 Opintomuistiinpanot & minisisällöt — Iteratiivinen ihmisen ja AI:n yhdistävä workflow, jossa tutkimusmuistiinpanot jalostetaan jäsennellyiksi teksteiksi ja edelleen audio-, video- ja grafiikkamuotoon.

🧠 Custom GPT:t — Kokoelma käyttötarkoituskohtaisia GPT-malleja, joissa promptikehityksen avulla ohjataan mallia tuottamaan tukea, tiivistyksiä ja tyylillisesti eriytettyä tekstiä.



NinaLista

# ProjektiLista
Erinäisiä projektejani 

Fokus:
- käytännön toteutus; työnkulkujen harjoittelu & työkalujen yhdistäminen; datan keruu, tallennus ja jatkokäsittely
- toimivat työvälineet tiedon- ja sisällöntuottamisen työnkulkuihin; hauskat kokeilut

---

## Projektitaulukko

| Projekti | Tyyppi | Teknologia / Stack | Ydinidea |
|----------|--------|-------------------|----------|
| 🛠️ InDesign / InCopy -skriptit | Desktop automaatio / julkaisu | InDesign/InCopy scripting (JS/ExtendScript), Word/RTF import | Rakenteisen tekstin hallinta ja automaatio (esim. hakemistot, viitteet, kommentit) |
| 🛠️ PDF / Word -tekstityökalut | Tekstiformaatin muotoilu | Python (PDF/Word parsing), fokus: offline lokaalisti | PDF/Word-teksti tyyppimuunnos & merkkien siivous halutusti | 
| 🛠️ Word-tekstityökalut | Tiedonhaku | AutoHotkey v2, Windows, URL-haut / AHK | Kustomoitava, pikanäppäimillä ohjattu haku (esim. Kielitoimisto, wikit, SAOB, synonyymit, Kansalliskirjasto) |
| 🛠️ NER kyrilliset, aasialaiset erisnimet | Translitterointi standardinmukaisella koodilla, tietokannan rakentaminen wikidatasta | Python & Vercel | Lokaali ja webapp-versio: nimen translitterointi standardoidusti & tietohaku tarkistuksen tueksi | 
| 🛠️ EPUB tekstin vierassanojen kielikoodit (WIP) | Saavutettavuus | Python, valinnainen AI-vaihe | EPUB → sanojen poiminta → koodin upotus EPUBiin | 
| 🤖 Tekstianalyysiskriptit | Tekstianalyysi / data | Python (NLP Stanza, SpaCy, regex) | Kustomoitu analyysi tekstiversioiden kielellisten muutosten vertailuun; NER-poimintoihin, vierassanapoimintoihin (henkilöt, organisaatiot, paikat) |
| 🎤 Teksti- ja puheloki-työkalu | Web-sovellus | Apps Script (web app), Google Sheets (tietokanta), HTML/JS (UI), Android (selain) | Rakenteinen mobiililokitus sarakkeisiin (teksti + aikaleima + sijainti + karttalinkki + valokuvaliite Drive-linkillä) |
| 📅 Reading/Writing Calendar | Ajanhallinta / työnkulku | Kustomoitu HTML/JS (local tool), Excel | Projektinhallinta, työvaiheet | Tekstien aikataulutus ja etenemisen seuranta eri työvaiheissa |
| 🔍 Offline Highlight Tool | Selainlaajennus | JavaScript, Chrome/Edge (Manifest V3), Clipboard API, contextMenus API | Valitun tekstin kopiointi lähde-URL:n kanssa selaimesta |
| 🗺️ Rautakausiretki | Kartta / dataputki / AI-rikastus | GeoLibre StoryMaps, JSON/GeoJSON, GitHub Pages | Sisältö → rikastus → interaktiivinen kartta |
| 🗺️ Muinaisia mestoja | Kartta / dataputki / AI-rikastus| Excel PowerQuery (WFS), Museovirasto API, KYPPI, GenAI, Google Maps | API → siivous → rikastus → interaktiivinen kartta |
| 🗺️ Hiisi-paikannimet | Kartta / dataputki / AI-rikastus | Nimisampo, Sotasampo, Excel-käsittely, GoogleAIStudio, GenAI ChatGPT & Claude, Google Maps; Illustrator | Laaja nimidata → teematasot → karttatutkiminen |
| 🗺️ Arkeologiset alueet (Satakunta) | Kartta / dataputki / AI-rikastus | Kulttuuriympäristö API, KYPPI/VARK, GenAI, Google Maps | Kuratoitu paikkadata → tiivistys → karttakohteet |
| 🗺️ QGIS – paikkatietoanalyysi | Data-analyysi / GIS | QGIS, geodata, shapefiles, raster/vektori | Tutkimusdata, paikkatieto | Tutkimusdatan tarkastelu ja visualisointi paikkatiedon kautta |
| 🌄 QGIS + Blender – 3D maisemavisualisointi | Paikkatieto + 3D / visualisointi | QGIS, Blender, Python scripting, geodata (DEM/vektori) | Paikkatieto, korkeusdata, tutkimusdata | QGIS-datan muuntaminen 3D-maisemaksi ja visualisointi Blenderissä |
| 🧊 Blender – dataohjattu 3D | 3D / visualisointi | Blender, Python scripting, Excel-data | Taulukkomuotoinen data, 3D-objektit | Excel-datan visualisointi 3D-objektien avulla kustomoidulla skriptillä |
| 🤖 LLM fine-tuning | NLP / kielimallikoulutus | Hugging Face (transformers); custom MiCA; datasets; PyTorch, Colab (T4 GPU), CSC Puhti; Unsloth | Kielimallin fine-tuning eri tekniikoilla → toivottu tyylisiirtymä |
| 🌐 Wiki API -datakysely & tietokantapohjainen webapp-hakutoiminto | Datahaku / API / SQL  | Wikipedia/Wikidata API, SQL/queries, JSON; Vercel; Git | Wiki-data, rakenteinen tieto | Datan haku rajapinnasta SQL-tyyppisillä kyselyillä ja jatkokäsittely webapp-tyyppiseksi tietokannaksi |
| 🧠 Sisällöntuotanto: muistiinpanot & minisisällöt | Sisältöputki | ChatGPT, manuaalinen kuratointi, audio/video/grafiikkatyökalut | Muistiinpanot → jäsennys → minisisällöt |
| 🧠 Custom GPT:t | AI-konfiguraatio / promptikehitys | ChatGPT (custom GPTs), järjestelmäpromptit, ohjauspromptit | Käyttötapauskohtaiset GPT:t (räätälöity IT-tuki, tekstilähteiden tiivistäjät, tyylianalyysipohjaiset persoonat) |
| 🧠 Ohjeet | Sisältöputki | Workflow- ja tulostiedostojen kuratointi, perinteiset ja AI-audio/video/grafiikkatyökalut | Muistiinpanot → jäsennys → sisällöt |
| 🤖 Videoanalyysi (WIP) | Liikeanalyysi: hahmon liikkeet videolta dataksi | Python | Video → pose tracking videolle → eleet yhdistetyksi dataksi jatkotarkastelua varten |
| 🤖 Lokin lentorytmin mallinnus (test level) | ML/transformer käyttäytymisanalyysissä | Collab (..) | Lokin lentodata (GPS) → Markov chain vs. transformerin ennuste → minidata |

| 🧰 Työkalut & ympäristöt | Kehitysympäristö / tooling | Anaconda/JupyterLab (Python), Colab, CSC Puhti; VS Code, Cursor, GitHub, Git; Excel, RStudio, Orange, QGIS, Blender, Gephi; AutoHotkey; GenAI (eri mallit), Replit, Vercel. Ollama, LMStudio, AnythingLLM, Unsloth; Adobe CC (InDesign, Lightroom, PhotoShop, Illustrator, Premiere), MSOffice, GoogleDocs/Sheets; Trados, Wordfast | Projektikehitys | Monityökalupohjainen kehitys eri käyttötarkoituksiin |

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

🤖 LLM fine-tuning (FI GPT-2) — Kokeellinen mallikoulutus, jossa suomenkielistä GPT-2-mallia hienosäädetään pienellä aineistolla tyylinsiirron tutkimiseksi. Heikko semanttinen koherenssi, rajoitteet kontekstissa ja mallikoossa; seuraava askel esim LoRA.

🌐 Wiki API -datakysely — Datan haku Wikipedia/Wikidata-rajapinnoista SQL-tyyppisillä kyselyillä (esim. SPARQL), tulosten käsittely ja hyödyntäminen rakenteisena aineistona.

🧠 Opintomuistiinpanot & minisisällöt — Iteratiivinen ihmisen ja AI:n yhdistävä workflow, jossa tutkimusmuistiinpanot jalostetaan jäsennellyiksi teksteiksi ja edelleen audio-, video- ja grafiikkamuotoon.

🧠 Custom GPT:t — Kokoelma käyttötarkoituskohtaisia GPT-malleja, joissa promptikehityksen avulla ohjataan mallia tuottamaan tukea, tiivistyksiä ja tyylillisesti eriytettyä tekstiä.



NinaLista

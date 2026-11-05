# Isikliku projekti arendus

## 1. Projekti nimi

Hättasattunud metsloomade juhtumilahendaja

## 2. Eesmärk

Projekti eesmärk on luua interaktiivne veebirakendus, mis aitab ametnikel ja metsloomade päästeorganisatsioonidel kiiresti määratleda metsloomaga seotud juhtumi olemuse ning leida sellele õige lahendus.

Ametiasutused ja vabatahtlikud organisatsioonid saavad igapäevaselt hulgaliselt teavitusi ning kõnesid. Suur osa neist käsitleb olukordi, kus loom ei vaja reaalset sekkumist või vajab teistsugust abi kui esialgu arvatud. Rakendus suunab kasutaja samm-sammult läbi lihtsa küsimustiku õige tegevusjuhiseni või vastava asutuseni (nt Keskkonnaamet, Päästeamet, kohalik omavalitsus või sobilik loomakaitseorganisatsioon), vähendades sellega teadmatust ja kiirendades reaalses hädas olevate loomade abistamist.

## 3. Sihtgrupp

* **Metsloomade päästeorganisatsioonid**
* **Ametiasutused ja ametnikud:** Keskkonnaamet, Häirekeskus (1247) ja kohalike omavalitsuste keskkonnaspetsialistid, kes puutuvad kokku metsloomadega seotud juhtumite haldamisega.

## 4. Funktsionaalsus

1. **Samm-sammuline otsustuspuu (Wizard):** Kasutajat juhendatakse üldistest küsimustest spetsiifilisteni (nt *Kas tegemist on linnu või imetajaga?* $\rightarrow$ *Kas linnupoja või täiskasvanud linnuga?* $\rightarrow$ *Kas ta on haavatud?*).
2. **Automaatne tegevussoovitus ja kontaktide kuvamine:** Küsimustiku lõpus kuvatakse selge tegevusjuhis (nt "Jäta linnupoeg puutumata" või "Võta ühendust Keskkonnaametiga numbril 1247").
3. **Haldusliides (Admin-vaade):** Organisatsiooni esindajad saavad lisada, muuta ja täiendada küsimuste ning vastuste loogikapuud vastavalt kehtivatele regulatsioonidele.
4. **Liikide ja olukordade kiirotsing (Infobaas):** Otsinguriba, kus saab otsida otse märksõna või loomaliigi järgi (nt "rebane", "varesepoeg", "nastik"), et jõuda vastava tegevusjuhiseni ilma otsustuspuud läbimata.
5. **Hooajalised teabebännerid ja meelespead avalehel:** Avalehel kuvatavad dünaamilised meelespead vastavalt aastaajale (nt kevadel "Linnupoegade hooaeg – millal sekkuda?", talvel "Veelindude lisatoitmise reeglid").

## 5. Tehnoloogiad

* **Kasutajaliides (Frontend):** HTML5, CSS3, JavaScript (React.js või Vue.js), Tailwind CSS (mobiilisõbraliku disaini tagamiseks).
* **Taustasüsteem (Backend):** Python (FastAPI / Flask) või Node.js (Express).
* **Andmebaas:** PostgreSQL või MongoDB (sobiva otsustuspuu puustruktuuri salvestamiseks).
* **Versioonihaldus ja majutus:** Git, GitHub, Vercel/Render (veebirakenduse avalikustamiseks).

## 6. Teostusplaan

1. **Nõuete ja loogika kaardistamine:** Otsustuspuu küsimuste ahela ja reeglistiku koostamine vastavalt parimatele praktikatele.
2. **Disain ja prototüüpimine:** Kasutajaliidese traatmudelite (wireframes) ja prototüübi loomine (Figma).
3. **Andmemudeli ja API projekteerimine:** Küsimustiku andmestruktuuri ja taustasüsteemi liideste defineerimine.
4. **Testimine:** Kasutatavustestid nutiseadmetes ja loogikapuude läbimängimine veasituatsioonide tuvastamiseks.
5. **Juhend ja avalikustamine:** Rakenduse majutamine veebiserveris ja lõppdokumentatsiooni vormistamine.

## 7. Valmisoleku kriteeriumid

* Küsimustiku tulemusena kuvatakse kasutajale õiged kontaktandmed ja konkreetsed juhised.
* Administraator saab haldusliidese kaudu küsimustikku uusi otsustusliine lisada.
* Veebirakendus on reageeriv (responsive) ning mobiilseadmega hõlpsalt kasutatav.
* Rakendus on avalikult kättesaadav toimiva veebilingi kaudu.

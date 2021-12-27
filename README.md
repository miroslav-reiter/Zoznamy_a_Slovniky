# ☑️ Zoznamy a Slovníky
Rôzne zoznamy a slovníky (všeobecný, synonymický, frazeologický, odborný, cudzích slov, slang/vulgarizmy, archaizmy) a pre rôzne jazyky (ENG, LAT, CZ, SK, ESP, DE). Zoznamy pre PSč a ZIP kódy obcí všetkých krajín sveta.

## 📬 Zoznam Poštové Smerové Čísla (PSČ a ZIP)
### Zdroj GeoNames (Licencia Creative Commons Attribution 4.0)

* Obcí celosvetovo (najmenšia administratívna jednotka): 1 548 344
* Obcí na Slovensku (najmenšia administratívna jednotka): 4 231
* Podporované krajiny: podporovaných takmer 100 krajín

Súbor `allCountries.zip`: všetky podporované krajiny, pre Spojené kráľovstvo iba vonkajšie kódy  
Súbor `Zoznam_Vsetkych_Krajin_Miest_Orezany.xlsx`: skoro všetky krajiny sveta (orezané pre obmedzenie v Exceli: 1 048 576)  
Súbor `SK.txt`: Dáta pre Slovensko  
Súbor `CZ.txt`: Dáta pre Česko  
Súbor `DE.txt`: Dáta pre Nemecko  
Súbor `ES.txt`: Dáta pre Španielsko  
Súbor `HU.txt`: Dáta pre Maďarsko  
Súbor `GB_full.csv.zip `: Dáta pre Spojené kráľovstvo (úplné kódy), približne 1,7 milióna riadkov  

Toto dielo podlieha licencii Creative Commons Attribution 4.0 License. To znamená, že výpis môžete používať, pokiaľ dáte meno geonames (odkaz na vašej webovej stránke www.geonames.org je v poriadku) pozri http://creativecommons.org/licenses/by/3.0/. Údaje sa poskytujú „tak ako sú“ bez záruky alebo akéhokoľvek vyjadrenia presnosti, aktuálnosti alebo úplnosti. V mnohých krajinách sa zemepisná šírka/dĺžka určuje pomocou algoritmu, ktorý vyhľadáva názvy miest v hlavnej databáze geonázvov použitie administratívneho členenia a číselnej blízkosti poštových smerovacích čísel ako faktorov pri vyjasňovaní názvov miest. Pre poštové smerovacie čísla a názov miesta, pre ktoré nebolo možné nájsť žiadne zodpovedajúce toponymum v hlavnej databáze geografických mien, priemer zemepisná šírka/dĺžka „susedných“ poštových smerovacích čísel.

**Štruktúra dát:**
* Formát údajov je text oddelený tabulátormi v kódovaní utf8 s nasledujúcimi poliami/Hlavičkou (header):
  * Kód krajiny (country code): ISO kód krajiny, 2 znaky  
  * PSČ (postal code): varchar(20)  
  * Názov miesta (place name): varchar(180)  
  * Admin name1: 1. poradie subdivision (štát/state) varchar(100)  
  * Admin code1: 1. poradie pododdiel (štát/state) varchar(20)  
  * Admin name2: 2. poradie subdivízia (kraj/provincia) varchar(100)  
  * Admin code2: 2. poradie subdivízia (kraj/provincia) varchar(20)  
  * Admin name3: 3. poradie pododdelenie (komunita) varchar(100)  
  * Admin code3: 3. poradie pododdiel (komunita) varchar(20)  
  * Zemepisná šírka (latitude): odhadovaná zemepisná šírka 
  * Zemepisná dĺžka (longitude): odhadovaná zemepisná dĺžka 
  * Presnosť (accuracy): presnosť zemepisnej šírky/dĺžky from 1=estimated, 4=geonameid, 6=centroid of addresses or shape

#### Poznámky
* 1° zemepisnej šírky (latitude) = 111 km   
* 1° zemepisnej dĺžky (longitude) = 73/111 km  
  
- Pre Čile sú len prvé číslice úplných poštových smerovacích čísel (z dôvodov autorských práv).
- Pre Írsko sú iba prvé písmená úplných poštových smerovacích čísel (z dôvodov autorských práv).
- Pre Maltu sú len prvé písmená celých poštových smerovacích čísel (z dôvodov autorských práv).
- Dátový súbor pre Argentínu obsahuje prvých 5 pozícií PSČ.
- Pre Brazíliu sú k dispozícii iba hlavné poštové smerovacie čísla (iba smerovacie čísla končiace na -000 a hlavné smerovacie číslo pre obec).

## Zoznam Slovenských Obcí (Villages), Okresov (Districts) a Krajov (Regions)  
A. Obcí (1. najmenšia administratívna jednotka Slovenska): 4208  
B. Okresov (2. najmenšia administratívna jednotka Slovenska): 79  
C. Krajov (3. najmenšia (najväčšia) administratívna jednotka Slovenska): 8  
  
## 💭 Anglický zoznam slov/slovník
Počet slov: 62996  
  
## 👅 Slovenský zoznam slov/slovník
A. Podstatné mená: 24891    
B. Prídavné mená: 14691    
C. Slovesá: 13955    

## 📚 Dôležité zdroje
1. [Sk-spell](http://sk-spell.sk.cx/ispell-sk) - Licencie **GPL (v2)**, LGPL (v2.1) a MPL (1.1)
2. [Register Adries a Okresov](https://data.gov.sk/dataset/register-adries-register-okresov) - Verejne poskytuje **Ministerstvo vnútra SR**
3. [Poštové smerovacie čísla obcí, ulíc a POBOXov](https://www.posta.sk/sluzby/postove-smerovacie-cisla) - Verejne poskytuje **Slovenská pošta**
4. [Veřejný dálkový přístup a overenie adresy](https://vdp.cuzk.cz/vdp/ruian/overeniadresy/vyhledej?) - Verejne poskytuje **Český úřad zeměměřický a katastrální**
5. [GeoNames Postal Code dataset](http://download.geonames.org/export/zip/) - Licencia **creative commons attribution**
6. [Nominativ Openstreet map](https://wiki.openstreetmap.org/wiki/Nominatim?) - **Open source**
7. [Nominativ](https://nominatim.org/ ) - **Open source**
8. [Maprequest](https://business.mapquest.com/products) - **Free prvých 15000 transakcií** potom [**platené podľa plánu**](https://business.mapquest.com/pricing-plans)
9. [Databáza miest a obcí s GPS súradnicami](http://www.progressive.sk/?m=software_db-cities) - **Platené**, formáty SQL, CSV alebo iný podľa požiadaviek
10. [ARES Administrativní registr ekonomických subjektů](https://wwwinfo.mfcr.cz/ares/ares_es.html.cz) - Verejne poskytuje **Ministerstva financí ČR**
11. [Elektronické služby SR](https://portal.minv.sk/wps/wcm/connect/sk/site/main/ohlasovne/) - verejne poskytuje **Ministerstvo vnútra SR**
12. [PC Translator 2010 - slovník a prekladač](http://www.teos.sk/translat.htm) - Platené, najväčší slovenský slovník, vyvíja sa viac ako 23 rokov
13. [Gunsoft - Obce, okresy a kraje v SR](https://github.com/gunsoft/obce-okresy-kraje-slovenska) - Licencia **GPL-2.0**
14. [BramboraSK - Slovník slovenského jazyka](https://github.com/BramboraSK/slovnik-slovenskeho-jazyka) - Licencia **GPL-2.0**
15. [Zoznam okresov Slovensko Wikipedia](https://sk.wikipedia.org/wiki/Okres_(Slovensko)) - Licencia **Creative Commons Attribution/Share-Alike License 3.0 Unported**
16. [Zoznam krajov Slovensko Wikipedia](https://sk.wikipedia.org/wiki/Zoznam_krajov_na_Slovensku) - Licencia **Creative Commons Attribution/Share-Alike License 3.0 Unported**
17. [Zoznam obcí a vojenských obvodov Slovensko Wikipedia](https://sk.wikipedia.org/wiki/Zoznam_slovenských_obcí_a_vojenských_obvodov) - Licencia C**reative Commons Attribution/Share-Alike License 3.0 Unported**

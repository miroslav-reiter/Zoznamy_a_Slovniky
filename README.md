# ☑️ Zoznamy a Slovníky
Rôzne zoznamy a slovníky (všeobecný, synonymický, frazeologický, odborný, cudzích slov, slang/vulgarizmy, archaizmy) a pre rôzne jazyky (ENG, LAT, CZ, SK, ESP, DE)

## 📬 Zoznam Poštové Smerové Čísla (PSČ a ZIP)
### Zdroj GeoNames

allCountries.zip: všetky podporované krajiny, pre Spojené kráľovstvo iba vonkajšie kódy, celkové kódy Spojeného kráľovstva sú v GB_full.csv.zip 
GB_full.csv.zip úplné kódy pre Spojené kráľovstvo, približne 1,7 milióna riadkov
<iso countrycode>: podmnožina špecifická pre krajinu je tiež zahrnutá v allCountries.zip
Toto dielo podlieha licencii Creative Commons Attribution 4.0 License.
To znamená, že výpis môžete používať, pokiaľ dáte meno geonames (odkaz na vašej webovej stránke www.geonames.org je v poriadku)
pozri http://creativecommons.org/licenses/by/3.0/
Spojené kráľovstvo (GB_full.csv.zip): Obsahuje údaje Royal Mail Copyright a právo databázy Royal Mail 2020.
Údaje sa poskytujú „tak ako sú“ bez záruky alebo akéhokoľvek vyjadrenia presnosti, aktuálnosti alebo úplnosti.

Tento súbor readme popisuje súbor údajov PSČ GeoNames.
Hlavný výpis údajov z vestníka GeoNames je tu: http://download.geonames.org/export/dump/


Podporované krajiny: V súčasnosti je podporovaných takmer 100 krajín. Keď národná pošta začne zverejňovať údaje na základe kompatibilnej licencie, pridá sa oblasť nových krajín.

V mnohých krajinách sa zemepisná šírka/dĺžka určuje pomocou algoritmu, ktorý vyhľadáva názvy miest v hlavnej databáze geonázvov 
použitie administratívneho členenia a číselnej blízkosti poštových smerovacích čísel ako faktorov pri vyjasňovaní názvov miest. 
Pre poštové smerovacie čísla a názov miesta, pre ktoré nebolo možné nájsť žiadne zodpovedajúce toponymum v hlavnej databáze geografických mien, priemer 
zemepisná šírka/dĺžka „susedných“ poštových smerovacích čísel.
Ak v súbore údajov nájdete nejaké chyby, dajte nám vedieť. Vďaka



Formát údajov je text oddelený tabulátormi v kódovaní utf8 s nasledujúcimi poľami:

kód krajiny : kód krajiny iso, 2 znaky  
PSČ: varchar(20)  
názov miesta: varchar(180)  
admin name1 : 1. objednávka subdivision (state) varchar(100)  
admin code1 : 1. objednávka pododdiel (štát) varchar(20)  
admin name2 : 2. objednávka subdivízia (kraj/provincia) varchar(100)  
admin code2 : 2. objednávka subdivízia (kraj/provincia) varchar(20)  
admin name3 : 3. objednávka pododdelenie (komunita) varchar(100)  
admin code3 : 3. objednávka pododdiel (komunita) varchar(20)  
zemepisná šírka: odhadovaná zemepisná šírka (wgs84)  
zemepisná dĺžka : odhadovaná zemepisná dĺžka (wgs84)  
presnosť : presnosť zemepisnej šírky/dĺžky od 1=odhad, 4=geonameid, 6=ťažisko adries alebo tvaru  


#### Poznámky
* 1° zemepisnej šírky (latitude) = 111 km   
* 1° zemepisnej dĺžky (longitude) = 73/111 km  
  
- Pre Čile sú len prvé číslice úplných poštových smerovacích čísel (z dôvodov autorských práv).
- Pre Írsko sú iba prvé písmená úplných poštových smerovacích čísel (z dôvodov autorských práv).
- Pre Maltu sú len prvé písmená celých poštových smerovacích čísel (z dôvodov autorských práv).
- Dátový súbor pre Argentínu obsahuje prvých 5 pozícií PSČ.
- Pre Brazíliu sú k dispozícii iba hlavné poštové smerovacie čísla (iba smerovacie čísla končiace na -000 a hlavné smerovacie číslo pre obec).

## 💭 Anglický zoznam slov/slovník
  
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
  

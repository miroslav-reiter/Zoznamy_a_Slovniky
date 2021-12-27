# ☑️ Zoznamy a Slovníky
Rôzne zoznamy a slovníky (všeobecný, synonymický, frazeologický, odborný, cudzích slov, slang/vulgarizmy, archaizmy) a pre rôzne jazyky (ENG, LAT, CZ, SK, ESP, DE). Zoznamy pre **PSČ** a **ZIP kódy** obcí všetkých krajín sveta. Súbory majú kódovanie **UTF-8**.

## 📬 Zoznam Poštové Smerové Čísla (PSČ a ZIP)
### Zdroj GeoNames (Licencia Creative Commons Attribution 4.0)

* **Obcí celosvetovo**: **1 548 344**
* Obcí na Slovensku: 4 231
* **Podporované krajiny**: **takmer 100 krajín**

Súbor `allCountries.zip`: všetky podporované krajiny, pre Spojené kráľovstvo iba vonkajšie kódy  
Súbor `Zoznam_Vsetkych_Krajin_Miest_Orezany.xlsx`: skoro všetky krajiny sveta (orezané pre obmedzenie v Exceli: 1 048 576)  
Súbor `SK.txt`: Dáta pre Slovensko  
Súbor `CZ.txt`: Dáta pre Česko  
Súbor `DE.txt`: Dáta pre Nemecko  
Súbor `ES.txt`: Dáta pre Španielsko  
Súbor `HU.txt`: Dáta pre Maďarsko  
Súbor `GB_full.csv.zip`: Dáta pre Spojené kráľovstvo (úplné kódy), približne 1,7 milióna riadkov  

Toto dielo podlieha licencii Creative Commons Attribution 4.0 License. To znamená, že výpis môžete používať, pokiaľ dáte meno geonames (odkaz na vašej webovej stránke www.geonames.org je v poriadku) pozri http://creativecommons.org/licenses/by/3.0/. Údaje sa poskytujú „tak ako sú“ bez záruky alebo akéhokoľvek vyjadrenia presnosti, aktuálnosti alebo úplnosti. V mnohých krajinách sa zemepisná šírka/dĺžka určuje pomocou algoritmu, ktorý vyhľadáva názvy miest v hlavnej databáze geonázvov použitie administratívneho členenia a číselnej blízkosti poštových smerovacích čísel ako faktorov pri vyjasňovaní názvov miest. Pre poštové smerovacie čísla a názov miesta, pre ktoré nebolo možné nájsť žiadne zodpovedajúce toponymum v hlavnej databáze geografických mien, priemer zemepisná šírka/dĺžka „susedných“ poštových smerovacích čísel.

**📇 Štruktúra dát a Formát údajov** je text oddelený tabulátormi v kódovaní utf8 s nasledujúcimi poliami/**Hlavičkou** (header):
  1. **Kód krajiny** (country code): ISO kód krajiny, 2 znaky  
  2. PSČ (postal code): varchar(20)  
  3. **Názov miesta** (place name): varchar(180)  
  4. Admin name1: 1. poradie name (štát/state) varchar(100)  
  5. **Admin code1**: 1. poradie code (štát/state) varchar(20)  
  6. Admin name2: 2. poradie name (kraj/provincia) varchar(100)  
  7. **Admin code2**: 2. poradie code (kraj/provincia) varchar(20)  
  8. Admin name3: 3. poradie name (komunita) varchar(100)  
  9. **Admin code3**: 3. poradie code (komunita) varchar(20)  
  10. Zemepisná šírka (latitude)
  11. **Zemepisná dĺžka** (longitude)
  12. Presnosť (accuracy): presnosť zemepisnej šírky/dĺžky from 1=estimated, 4=geonameid, 6=centroid of addresses or shape

#### ℹ️ Poznámky
* 1° zemepisnej šírky (latitude) = 111 km   
* 1° zemepisnej dĺžky (longitude) = 73/111 km  
  
- Pre Čile sú len prvé číslice úplných poštových smerovacích čísel (z dôvodov autorských práv).
- Pre Írsko sú iba prvé písmená úplných poštových smerovacích čísel (z dôvodov autorských práv).
- Pre Maltu sú len prvé písmená celých poštových smerovacích čísel (z dôvodov autorských práv).
- Dátový súbor pre Argentínu obsahuje prvých 5 pozícií PSČ.
- Pre Brazíliu sú k dispozícii iba hlavné poštové smerovacie čísla (iba smerovacie čísla končiace na -000 a hlavné smerovacie číslo pre obec).

## 🏙️ Zoznam Slovenských Obcí (Villages), Okresov (Districts) a Krajov (Regions)  
A. **Obce** (1. najmenšia administratívna jednotka Slovenska): **4 208/3 791** (Slovenská pošta 2021)      
B. Okresy (2. najmenšia administratívna jednotka Slovenska): 79/76 (Slovenská pošta 2021)   
C. **Kraje** (3. najmenšia (najväčšia) administratívna jednotka Slovenska): **8**   
D. Pošty: 1 209 (Slovenská pošta 2021)  
E. **Ulice**: **10 554** (Slovenská pošta 2021)  
F. Uliče jedinečné cca: 6 384 (Slovenská pošta 2021)  
G. **POBOXy**: **13 790** (Slovenská pošta 2021)  
H. PSČ: 1 285 (Niektoré obce môžu byť bez uličného systéme alebo s 2 a viac PSČ)  

### Zoznam slovenských krajov
| ID_Kraj | Kraj | ISO_3166 | Obyvatelov | Rozloha | Hustota_Obyv | Obci | Miest | Okresov | Okresy
| --------------- | --------------- | --------------- | --------------- | --------------- | --------------- | --------------- | --------------- | --------------- | --------------- |
| 1 | **Bratislavský** | SK-BL |	677 024 |	2 052,5 |	330 |	73	 |7 |	8	| Bratislava I, Bratislava II, Bratislava III, Bratislava IV, Bratislava V, Malacky, Pezinok, Senec |
| 2 | **Trnavský** |	SK-TA |	565 324	| 4 146,6 |	136 |	251 |	17 |	7 |	Dunajská Streda, Galanta, Hlohovec, Piešťany, Senica, Skalica, Trnava |
| 3 | Trenčiansky |	SK-TC |	582 567 |	4 502,0 |	129 |	276 |	18 |	9	 |Bánovce nad Bebravou, Ilava, Myjava, Nové Mesto nad Váhom, Partizánske, Považská Bystrica, Prievidza, Púchov, Trenčín |
| 4 | Nitriansky |	SK-NI |	671 508	 | 6 343,8 |	106 |	354	| 16 |	7 |	Komárno, Levice, Nitra, Nové Zámky, Šaľa, Topoľčany, Zlaté Moravce |
| 5 | Žilinský |	SK-ZI |	691 136	| 6 808,7	| 102	| 315	 | 19 |	11	| Bytča, Čadca, Dolný Kubín, Kysucké Nové Mesto, Liptovský Mikuláš, Martin, Námestovo, Ružomberok, Turčianske Teplice, Tvrdošín, Žilina | 
| 6 | Banskobystrický	| SK-BC	| 643 102 |	9 454,4 |	68 |	516 |	24 |	13 |	Banská Bystrica, Banská Štiavnica, Brezno, Detva, Krupina, Lučenec, Poltár, Revúca, Rimavská Sobota, Veľký Krtíš, Zvolen, Žarnovica, Žiar nad Hronom |
| 7 | Prešovský	| SK-PV	| 827 028 |	8 973,9 |	92 |	665 |	23 |	13 |	Bardejov, Humenné, Kežmarok, Levoča, Medzilaborce, Poprad, Prešov, Sabinov, Snina, Stará Ľubovňa, Stropkov, Svidník, Vranov nad Topľou |
| 8 | **Košický**	| SK-KI	| 802 092 |	6 754,5 |	119 |	440 |	17 |	11 | Gelnica, Košice I, Košice II, Košice III, Košice IV, Košice-okolie, Michalovce, Rožňava, Sobrance, Spišská Nová Ves, Trebišov |

### Zoznam vybraných slovenských okresov
| ID_Kraj | Okres | ECV | Kod | Kraj | Pocet_Obyv | Zien | Rozloha | Hustota_Obyv | Obci | Miest |
| --------------- | --------------- | --------------- |  --------------- | --------------- | --------------- | --------------- | --------------- | --------------- | --------------- | --------------- |
| 1 | Banská Bystrica	 | BB, BC, BK	| 601 |	Banskobystrický	| 110 631 |	52,4	| 809,4	| 137 |	42 |	1 |
| 2 | Bratislava I	| BA, BL, BT, BD, BE, BI |	101	|Bratislavský |	42 546 |	53,8 |	9,6 |	4 436 |  | |
| 3 | Bratislava II	| BA, BL, BT, BD, BE, BI |	102	|Bratislavský |	116 669 |	54,2 |	92,5 |	1 261 |  | |
| 4 | Bratislava III	| BA, BL, BT, BD, BE, BI |	103	|Bratislavský |	70 641|	53,7 |	74,7 |	946 |  | |
| 5 | Bratislava IV	| BA, BL, BT, BD, BE, BI |	104	|Bratislavský |	98 404 |	52,8 |	96,7 |	1 018 |  | |
| 6 | Bratislava V	| BA, BL, BT, BD, BE, BI |	105	|Bratislavský |	112 688 |	52,1 |	94,2 |	1 196 |  | |
| 7 | Košice I |	KE, KC, KI |	802 |	Košický	 | 67 421 |	52,9 |	85,4 |	789	 | | |
| 8 | Košice II |	KE, KC, KI |	803 |	Košický	 | 82 115	| 51,9 |	73,9 |	1 112	 | | |
| 9 | Košice III |	KE, KC, KI |	804 |	Košický	 | 28 535 |	51,4 |	16,9 |	1 693	 | | |
| 10 | Košice IV |	KE, KC, KI |	805 |	Košický	 | 60 067	| 52,7 |	60,9 |	986 | | |
| 11 | Žilina  |ZA, ZI, ZL	| 511 |	Žilinský |	158 456 |	51,4 |	815,1 |	194 |	53 |	3 | |
| 12 | Trnava | TT, TA, TB |	207 |	Trnavský |	133 154 |	51,3 |	741,3 |	180	| 45 |	1 | |
| 13 | Prešov	| PO, PV, PS	| 707 |	Prešovský |	176 781 |	51,3 |	933,7 |	189	| 91 |	2 | |
| 14 | Nitra |	NR, NI, NT |	403 |	Nitriansky |	161 499 |	51,7 |	870,7	| 185	| 62 |	2 | |
| 15 | Trenčín |	TN, TC, TE |	309 |	Trenčiansky |	114 837	| 51,3 |	674,8 |	170 |	37 |	3 | |

## 💭 Anglický zoznam slov/slovník
Počet slov: 62 996  
  
## 👅 Slovenský zoznam slov/slovník
A. **Podstatné mená**: **24 891**   
B. Prídavné mená: 14 691    
C. **Slovesá**: **13 955**  
D. Všetky slová (Zdroj: [ispell](http://sk-spell.sk.cx/ispell-sk), súbor: `Zoznam_SK_Vsetko_ispell.txt`): 175 835

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
17. [Zoznam obcí a vojenských obvodov Slovensko Wikipedia](https://sk.wikipedia.org/wiki/Zoznam_slovenských_obcí_a_vojenských_obvodov) - Licencia **Creative Commons Attribution/Share-Alike License 3.0**

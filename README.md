# # Pontozólap
**Név**: Beniczky Tamás
**Neptun**: HMKFPV

## Projekt rövid leírása

Egy egyszerű weblap az adatbázis adatainak megjelenítésére, valamint egy windows formos projekt. Az index.html az adatbázis alapján dinamikus tartalommal töltődik fel az oldal megnyitásakor. Itt adhatunk hozzá sorokat, törölhetünk értékeket id alapján, vagy egy id megadásával megváltoztathatjuk az oda tartozó terméknevet / egységárat. Az windows formsos projektben szűrni lehet a tábla tartalmát, illetve a tábla tartalmát ki lehet menteni egy excel fileba.


# Hozott anyagok
## Saját adatbázis
![azure adatbazis kepe](https://github.com/tamasbeniczky/zh3k-pek/blob/main/hozottanyag.png?raw=true)

 -  `1p`  Az alkalmazásban használt táblánként pont (Rendeles)
-   `1p`  Az adatbázis tartalmaz Constraint-eket (min 2)
-   `2p`  Az adatbázis saját Azure SQL szerveren van
-   `1p`  Az adatbázis adatainak forrásmegjelölése értsd: miből készült és hogyan:
- Az adatbázisthoz az SQL-t a copilottal generáltattam a megfelelő prompt után. Csatlakoztam Azure Data Studioban az adatbázishoz, majd lefuttattam a scripteket. Az adatbázisnak egy táblája van, a rendelés tábla, melyben a rendelés néhány adata található.

## weboldal
![weboldal kinézete](https://github.com/tamasbeniczky/zh3k-pek/blob/main/weboldal.png?raw=true)

-   `1p`  A weboldalnak van egy értelmezhető struktúrája
-   `1p`  A weboldal dinamikus tartalommal tölthető fel adatbázison keresztül
-   `1p`  A weboldal használ legalább 20 sor értelmes css-t
-   `1p`  A weboldal javascriptje más funkciót is ellát, mint az adatok betöltése

## Egyéb,  extra
![scaffold](https://github.com/tamasbeniczky/zh3k-pek/blob/main/scaffold.png?raw=true)

-   `1p`  `Scaffold-DbContext`  használata

##  ASP .NET
 -   `2p`  `program.cs`  beállítása  `wwwroot`  mappában tárolt statikus tartalmak megosztására
#### API végpontok
 -   `3p`  Teljes SQL tábla adatainak szolgáltatása API végponton keresztül
 -   `3p`  SQL tábla egy választható rekordjának törlése
 -   `5p`  Új rekord felvétele  `HttpPost`  metóduson keresztül SQL táblába
 -   `2x3p`  Rekord módosítása  `HttpPost`  metóduson keresztül SQL táblában (termeknev, egysegar)
 -   `5p`  Külső API végpont használata JS kódban, itt: https://api.openweathermap.org/data/2.5/weather?q=Budapest&appid=fe020ad6bb55fe106f34e88f73154155&units=metric
###  Excel
 -   `7` Excel munkafüzet generálása kódból, adatbázstába tartalmának megjelenítésével, legalább egy formázással
 - ![excel kep helye](https://github.com/tamasbeniczky/zh3k-pek/blob/main/excel.png?raw=true)

 - 
##  Windows forms
 - `2p`  **Anchorok alkalmazása**: az alkalmazás egészében meg van oldva, hogy az ablak átméretezésekor ki legyen használva a rendelkezésre álló terület.
###  Listbox
 - `2p`Adatok  megjelenítése
 - `2p`Ha a tábla adatforrása saját osztály.
###  Datagridview
 - `2p`Adatok  megjelenítése
 - `2p`Ha a tábla adatforrása saját osztály.
###  Bindingsource
 - `2p`Működő  `BindingSource`

![szuro1](https://github.com/tamasbeniczky/zh3k-pek/blob/main/szures1.png?raw=true)![szuro2](https://github.com/tamasbeniczky/zh3k-pek/blob/main/szures2.png?raw=true)

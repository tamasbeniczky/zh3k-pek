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

# Synchronization

Synchronization is one of the biggest features of StackEdit. It enables you to synchronize any file in your workspace with other files stored in your **Google Drive**, your **Dropbox** and your **GitHub** accounts. This allows you to keep writing on other devices, collaborate with people you share the file with, integrate easily into your workflow... The synchronization mechanism takes place every minute in the background, downloading, merging, and uploading file modifications.

There are two types of synchronization and they can complement each other:

- The workspace synchronization will sync all your files, folders and settings automatically. This will allow you to fetch your workspace on any other device.
	> To start syncing your workspace, just sign in with Google in the menu.

- The file synchronization will keep one file of the workspace synced with one or multiple files in **Google Drive**, **Dropbox** or **GitHub**.
	> Before starting to sync files, you must link an account in the **Synchronize** sub-menu.

## Open a file

You can open a file from **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Open from**. Once opened in the workspace, any modification in the file will be automatically synced.

## Save a file

You can save any file of the workspace to **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Save on**. Even if a file in the workspace is already synced, you can save it to another location. StackEdit can sync one file with multiple locations and accounts.

## Synchronize a file

Once your file is linked to a synchronized location, StackEdit will periodically synchronize it by downloading/uploading any modification. A merge will be performed if necessary and conflicts will be resolved.

If you just have modified your file and you want to force syncing, click the **Synchronize now** button in the navigation bar.

> **Note:** The **Synchronize now** button is disabled if you have no file to synchronize.

## Manage file synchronization

Since one file can be synced with multiple locations, you can list and manage synchronized locations by clicking **File synchronization** in the **Synchronize** sub-menu. This allows you to list and remove synchronized locations that are linked to your file.


# Publication

Publishing in StackEdit makes it simple for you to publish online your files. Once you're happy with a file, you can publish it to different hosting platforms like **Blogger**, **Dropbox**, **Gist**, **GitHub**, **Google Drive**, **WordPress** and **Zendesk**. With [Handlebars templates](http://handlebarsjs.com/), you have full control over what you export.

> Before starting to publish, you must link an account in the **Publish** sub-menu.

## Publish a File

You can publish your file by opening the **Publish** sub-menu and by clicking **Publish to**. For some locations, you can choose between the following formats:

- Markdown: publish the Markdown text on a website that can interpret it (**GitHub** for instance),
- HTML: publish the file converted to HTML via a Handlebars template (on a blog for example).

## Update a publication

After publishing, StackEdit keeps your file linked to that publication which makes it easy for you to re-publish it. Once you have modified your file and you want to update your publication, click on the **Publish now** button in the navigation bar.

> **Note:** The **Publish now** button is disabled if your file has not been published yet.

## Manage file publication

Since one file can be published to multiple locations, you can list and manage publish locations by clicking **File publication** in the **Publish** sub-menu. This allows you to list and remove publication locations that are linked to your file.


# Markdown extensions

StackEdit extends the standard Markdown syntax by adding extra **Markdown extensions**, providing you with some nice features.

> **ProTip:** You can disable any **Markdown extension** in the **File properties** dialog.


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```

And this will produce a flow chart:

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```

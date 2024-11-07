# Weboldal  követelmények és felépítés

Ebben a dokumentumban leírom mit kell tenni hogy kész legyen a weboldal, hogy épül fel, mennyibe kerül fenntartani, hogy kell kezelni, és nekem mire van szükségem tőled.

El tudom kezdeni az oldalt és a technikai részét megoldom. Amint elkezdtem küldök egy linket amin láthatod hogy alakul.

## Hiányzó dolgok

*Úgy kérek mindent hogy nem tudok semmit, nem tudom mi van már meg neked vagy mi nincs. Ha van már egy elképzelésed akkor ignoráld ennek a nagy részét*

### Alap információk

* Cégnév

* Logó - ez lehet csak a cég név szövegként ha nincs

### Weboldal stílus

Megbeszéltük hogy a [Corporio](https://themes.gohugo.io/themes/corporio/) témát-t használjuk. Itt a [Demo oldal](https://corporio.onrender.com/) amit meg tudsz nézni hogy pontosan hogy néz ki. Láttam pár hibát a mobil verzióban amit majd javítok.

Ha van egy elképzelésed hogy hogy nézzen ki az oldal akkor mondd, el, de a minimum az ez:

* Háttérszín - a demó oldalon jelenleg fehér

* Elsődleges szín - a demó oldalon jelenleg zöld. Majdnem minden más szín az oldalon ebből készül

### Weboldal tartalom

A demó oldal van referenciaként, minden szöveget és képet amit látsz rajta meg kell változtatnunk. Minden részt el lehet tüntetni. Ez az amit nagyrészt neked kell megírni (képeknél előkeríteni). Ebben talán én is segíthetek vagy [ChatGPT](https://chatgpt.com/) referenciának ha csak nagyvonalakban tudod.

#### Főoldal

Minden szekciót el lehet tüntetni ebből a részből.

1. Hős szekciónak hívják, az első rész az oldalon. Minden opcionális de a kép, rövid összegzés és a kapcsolat gomb ajánlott.
   
   1. Cím
   
   2. Rövid összegzés
   
   3. Kicsit hosszabb kifejtés arról amit csinálsz
   
   4. Egy kép egy munkádról amire legjobban büszke vagy, vagy valami ami reprezentálja mit csinálsz
   
   5. Videó
   
   6. Kapcsolat gomb

2. Szolgáltatás kategóriák - ezt gondolom tudod, pl javítás, új ruha tervezés és varrás, satöbbi. 

3. Releváns képzettségek, stb.

4. Rólad (Rólatok)
   
   1. Rövid összegzés ami tartalmazza hogy hol tartotok most (pl "A történetünk hogy hogy lettünk egy többfős cég stb")
   
   2. Hosszabb kifejtés
      
      1. Mikortól
      
      2. Mit csináltok
      
      3. hogy nőttetek
      
      4. hogy szélesedett a kínálatotok
      
      5. stb

5. Termékek - Ha nem árultok kész dolgokat akkor ez a rész nem kell, ha igen akkor Mindhez kell kép és név

6. Ajánlások

7. Blog - ha nem akarsz írni blogot akkor ki lehet venni

8. Kapcsolat rész
   
   1. Szöveg felhívás rendelés felvételre
   
   2. Gomb szövege 

### Kapcsolat oldal

#### Alap adatok

- Telefonszám

- Cím

- Email

- Munkaidő?

#### Kapcsolat kérdőív

Nem tudom milyen opciókat szeretnél ide, email, név és üzenet a minimum, de lehet még "szolgáltatás kiválasztása lista", vagy amit akarsz. Te tudod hogy veszel fel rendeléseket, ennek a kérdőívnek nagyjából meg kell felelnie annak.

## Felépítés fenntartási költségekkel

Az árakon kívül ez a rész nem annyira fontos most. Majd ha majdnem kész leszünk az oldallal akkor kell ide mindehova regisztrálni neked, valahol nekem is engedélyt adni stb. Most egy ideiglenes helyen dolgozok majd rajta amit elküldök később neked. 

- Kód [Github](https://github.com)-on - ingyen

- Domain név [Cloudflare](https://www.cloudflare.com/)-en - Ára kb **5000Ft/év** a választott névtől függően (ez az ami a böngésző url részén látszódik majd, pl az enyém `www.attilagreguss.co.uk`)

- Weboldal hostolása Cloudflare-en - ingyen

- Kapcsolat (rendelés) form - **50 rendelés/hó-ig ingyenes, utána** **egyszeri ár 22000Ft**. Ez ráér ha túlléped a határt

- Könnyebb weboldal szerkesztés neked [TinaCMS](https://tina.io/) - ingyenes két emberig, de majd meglátjuk mennyire hasznos ha már dolgoztam a weboldalon egy kicsit.

## Oldal technológiák

Ez a rész megint csak nem kell, majd ha odáig eljutunk hogy tényleg tudnod kell ezekről akkor TeamViewerezünk róla.

* [Hugo](https://gohugo.io/)

* Fileok [yml](https://megnyitasa.com/extension/yml) és [markdown](https://www.greelane.com/hu/tudom%C3%A1ny-tech-math/sz%C3%A1m%C3%ADt%C3%A1stechnika/what-is-markdown-formatting-4689009/) formátumban

* [Corporio](https://themes.gohugo.io/themes/corporio/)

* Verziókezelés [Git]([Git bevezető | Petrik segédletek](https://segedletek.level14.hu/2018/02/21/git-bevezeto.html))-el - egyszerre a legnehezebb megtanulni és a leghasznosabb dolog ha szöveges fájlok verziókezeléséről van szó.

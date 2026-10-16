# Vizsgaremek-2026-2027
Figler Zalán
# Költöztető- és fuvarszervező alkalmazás – Vizsgaremek-tervezet
# 1. A projekt bemutatása

A vizsgaremek célja egy költöztető- és fuvarszervező webalkalmazás megtervezése és megvalósítása, amely megkönnyíti a költöztetéssel és áruszállítással foglalkozó vállalkozások mindennapi adminisztrációját. A rendszer egy központi felületen teszi lehetővé a megrendelések kezelését, a fuvarok megszervezését, a járművek és sofőrök beosztását, valamint a szállítási folyamatok nyomon követését.

A projekt egy valós problémára kínál megoldást, hiszen a kisebb fuvarozócégek gyakran telefonon, papíron vagy különböző táblázatokban tartják nyilván a megrendeléseiket. Ez nehezíti az adatok rendszerezését, a munkák összehangolását és a szállítások állapotának követését. Az alkalmazás célja ezen folyamatok egyszerűsítése, az adminisztráció csökkentése és a munkavégzés hatékonyabbá tétele.

# 2. A rendszer fő funkciói

Az alkalmazásban a felhasználók regisztrálhatnak, bejelentkezhetnek, és jogosultságuktól függően érhetik el az egyes funkciókat. Az adminisztrátor kezelheti a felhasználókat, a járműveket, a sofőröket és a megrendeléseket. A diszpécser feladata a fuvarok megszervezése, a megfelelő jármű és sofőr hozzárendelése, valamint az időpontok összehangolása. Az ügyfelek megadhatják a szállítás részleteit, megtekinthetik megrendeléseik állapotát, és értékelhetik a teljesített szolgáltatásokat.

A megrendelések rögzítésekor megadható a felrakodás és a célállomás címe, a kívánt időpont, a szállítandó tárgyak mennyisége és típusa, valamint az esetleges különleges igények. A rendszer a megadott adatok alapján előzetes díjkalkulációt készíthet, amely figyelembe veszi például a távolságot, a rakomány méretét, a szükséges munkaerőt és az extra szolgáltatásokat.

A fuvarok különböző státuszokat kaphatnak, például új megrendelés, jóváhagyásra vár, ütemezve, folyamatban, teljesítve vagy lemondva. Ennek segítségével a diszpécser és az ügyfél is könnyebben áttekintheti a szállítás aktuális helyzetét. A rendszer továbbá lehetőséget biztosít a korábbi megrendelések visszakeresésére, a teljesített fuvarok értékelésére és különböző statisztikák megjelenítésére.

# 3. Technológiai megvalósítás és adatbázis

A projekt webalkalmazásként készülne, amely kliensoldali és szerveroldali komponenseket egyaránt tartalmaz. A kliensoldal feladata a felhasználói felület megjelenítése, az űrlapok kezelése, az adatok listázása és a visszajelzések megjelenítése. A szerveroldal felelne az üzleti logikáért, a jogosultságok ellenőrzéséért, a díjkalkulációért, a fuvarok ütközésének vizsgálatáért és az adatbázis-műveletek végrehajtásáért.

Az alkalmazás egy relációs adatbázist használna, amely pontosan tíz, egymással kapcsolatban álló táblából épül fel. Ezek a felhasználók, ügyfelek, címek, megrendelések, járművek, sofőrök, fuvarok, rakományok, díjszabások és értékelések adatait tárolnák. Az elsődleges és idegen kulcsok biztosítanák az adatok közötti kapcsolatokat és az adatintegritást.

# 4. Tesztelés és várható eredmények

A fejlesztés során kiemelt szerepet kapna a tesztelés. Ellenőrizni kellene többek között a kötelező mezők kitöltését, a hibás adatok kezelését, a jogosultságokat, a díjszámítás helyességét, valamint azt, hogy egy járműhöz vagy sofőrhöz ne lehessen azonos időpontra egymást kizáró fuvarokat rendelni. A tesztelés egységtesztekkel, API-tesztekkel és a felhasználói felület automatizált tesztjeivel történhetne.

A projekt eredményeként egy átlátható, könnyen használható és bővíthető alkalmazás jönne létre, amely támogatja a költöztető- és fuvarozóvállalkozások napi munkáját. A rendszer bemutatná a teljes fejlesztési folyamatot a követelmények meghatározásától az adatbázis kialakításán és a programozáson át a tesztelésig és a dokumentáció elkészítéséig.

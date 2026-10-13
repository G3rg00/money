PÉNZTÁRAM – iPhone Safari webalkalmazás

TARTALOM
- index.html: az alkalmazás
- manifest.json, icon.svg, sw.js: telepítési ikon és offline gyorsítótár
- Az adatok a böngésző helyi tárhelyén maradnak.

FONTOS KORLÁT
Az index.html önmagában is kipróbálható számítógépen, de az iPhone főképernyőre telepítéséhez és az offline működéshez HTTPS-en kell elérhetővé tenni a teljes mappát. A ZIP nem egy App Store-os natív alkalmazás.

HASZNÁLAT IPHONE-ON
1. Töltsd fel a ZIP-ben található fájlokat egy HTTPS-t támogató statikus tárhelyre (például GitHub Pages).
2. Nyisd meg az oldal HTTPS-linkjét az iPhone Safari böngészőjében.
3. Nyomd meg a Megosztás gombot.
4. Válaszd a „Főképernyőhöz adás” lehetőséget, majd a Hozzáadás gombot.
5. Ezután a Pénztáram ikonról indíthatod.

FUNKCIÓK
- Bevétel és kiadás rögzítése, kategória, dátum, megjegyzés
- Egyenleg és havi összesítések
- Kategóriánkénti kiadási grafikonok
- Havi költségkeret
- CSV-export és JSON biztonsági mentés/visszaállítás
- Tranzakció törlése

ADATVÉDELEM
Az adatok a böngésző helyi tárhelyén vannak, nem szinkronizálódnak automatikusan másik készülékre. A böngészőadatok törlése elveszítheti őket, ezért készíts időnként JSON biztonsági mentést. Banki fiókokhoz nem csatlakozik.

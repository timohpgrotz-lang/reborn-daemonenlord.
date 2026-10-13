REBORN: DÄMONENLORD – SAUBERE NEUINSTALLATION (V3.6)

Dieses Paket ist für die flache Dateistruktur deines aktuellen GitHub-Repositorys vorbereitet. Alle Dateien aus diesem ZIP müssen direkt im Hauptverzeichnis (root) liegen.

DATEIEN IM PAKET
- index.html: Spieloberfläche und Spielcode
- sw.js: Service Worker mit aktualisiertem Cache-Namen und Netzwerk-vorrangigem Laden
- manifest.webmanifest: PWA-Metadaten
- icon.svg: Spielsymbol
- demonlord_legendary_armor.glb: vorhandenes 3D-Modell
- legendary_weapons.glb: vorhandenes Waffenmodell

NEUINSTALLATION AUF ANDROID/GITHUB
1. Lade dieses ZIP herunter und entpacke es auf deinem Handy.
2. Öffne dein GitHub-Repository.
3. Lösche im Repository-Hauptverzeichnis die bisherigen Spieldateien: index.html, sw.js, manifest.webmanifest, icon.svg, demonlord_legendary_armor.glb und legendary_weapons.glb (falls vorhanden). README.txt kannst du behalten oder ersetzen.
4. Lade die sechs Dateien aus diesem Paket direkt ins Hauptverzeichnis hoch – NICHT in einen zusätzlichen Unterordner.
5. Commit changes. Warte kurz, bis GitHub Pages veröffentlicht hat.
6. Öffne die Spielseite neu. Falls der alte Stand bleibt: Browser-Website-Daten für die Seite löschen oder in einem privaten Tab öffnen.

WICHTIG
- Die GLB-Dateien liegen absichtlich im Hauptverzeichnis; index.html wurde auf diese Pfade angepasst.
- Three.js wird weiterhin über externe CDN-Module geladen und benötigt eine funktionierende Internetverbindung. Dieses Paket verbessert den Service-Worker-Cache, garantiert aber keinen Engine-Start, falls die CDN-Imports auf dem Gerät/Netzwerk blockiert werden.
- Wenn die 3D-Engine danach weiterhin nicht startet, ist der nächste Schritt die genaue Fehlermeldung aus dem catch-Block/Browser-Konsole zu prüfen.
- Die Dateien wurden paketiert und Pfade angepasst, aber nicht auf deinem Android-Gerät live getestet.

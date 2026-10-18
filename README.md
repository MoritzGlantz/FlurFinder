# FlurFinder Rheinland-Pfalz

**[FlurFinder öffnen](https://moritzglantz.de/flurfinder/)** · [Weitere Projekte](https://moritzglantz.de/projects/)

Kostenlose, interaktive Flurkarte für Rheinland-Pfalz mit amtlichen Katasterdaten. Funktioniert direkt im Browser, ohne eigenes Backend.

## Funktionen

- Nach Orten, Adressen und Flurstücken suchen
- Flurstücke per Klick markieren und abwählen
- Mehrere Flurstücke auswählen, aus der Liste auf der Karte anspringen und optional Notizen ergänzen
- Karte und Luftbild umschalten
- Kartenausschnitt und Auswahl über kompakte Links teilen (mit Notizen, falls vorhanden)
- Aktuellen Ausschnitt drucken oder als PDF speichern
- Bei Bedarf nur Flurstücksdaten für den sichtbaren Bereich laden
- Hinweis bei Navigation außerhalb von Rheinland-Pfalz

## Veröffentlichung

Die Dateien aus diesem Repository im Webverzeichnis `/flurfinder/` bereitstellen. `index.html` ist der Einstiegspunkt; `assets/` enthält die App-Icons. Die Anwendung nutzt öffentliche Karten- und Katasterdienste und benötigt hierfür Internetzugang.

**Öffentliche URL:** https://moritzglantz.de/flurfinder/

## Datenquellen

ALKIS / LVermGeo Rheinland-Pfalz, Grundkarte basemap.de / BKG, DOP20-Luftbilder des LVermGeo und Ortssuche über Photon / OpenStreetMap. Ausführliche Quellenhinweise stehen in der Anwendung. Die Karte ersetzt keinen amtlichen Katasterauszug. Bereits geteilte Links mit dem bisherigen `s`-Parameter bleiben lesbar.

## Quellcode

https://github.com/MoritzGlantz/FlurFinder

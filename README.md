Diese Erweiterung erweitert die vorhandene [MotionKit V2](https://github.com/tinysuperlab/MotionKitV2) Erweiterung um neue Blöcke. Mit diesen neuen Blöcken soll die Steuerung vereinfacht werden. Es gibt Blöcke, um den Roboter zu drehen oder eine bestimmte Strecke fahren zu lassen.

## Als Erweiterung verwenden

Dieses Repository kann als **Erweiterung** in MakeCode hinzugefügt werden.

* öffne [https://makecode.calliope.cc/](https://makecode.calliope.cc/)
* klicke auf **Neues Projekt**
* klicke auf **Erweiterungen** unter dem Zahnrad-Menü
* nach **Roboter** suchen und importieren

## Kalibrierung

`Roboter.set_velocity(0)` Strecke[cm], die der Robotor in 1s zurücklegt
`Roboter.set_angular_velocity(0)` Grandzahl[°], die der Robotor sich in 500ms dreht

## Nicht blockierendes Fahren

Der Befehl `Roboter.drive_time_non_blocking bzw.` der Block `Für [ZEIT] ms [RICHTUNG] fahren, dabei das Programm weiterlaufen lassen` lässt das Programm nicht anhalten. Befehle nach diesem Block

## Dieses Projekt bearbeiten

Um dieses Repository in MakeCode zu bearbeiten.

* öffne [https://makecode.calliope.cc/](https://makecode.calliope.cc/)
* klicke auf **Importieren** und dann auf **Importiere URL**
* füge **https://github.com/galbatoriz/roboter** ein und klicke auf Importieren

#### Metadaten (verwendet für Suche, Rendering)

* for PXT/calliopemini
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>

> Diese Seite bei [https://galbatoriz.github.io/roboter/](https://galbatoriz.github.io/roboter/) öffnen

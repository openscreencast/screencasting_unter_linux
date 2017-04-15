## Gnome Shell Recorder

Seit jeher gehört die Screenshot-Funktionalität (Bildschirmfotos erstellen) zur Grundausstattung von Gnome.
Mit Gnome3 hielt ein weiteres Feature, die Screencast-Funktion (Bildschirmvideoaufnahme),
Einzug in die Ausstattungspalette der grafischen Benutzeroberfläche. 
Der Gnome Shell Recorder streicht somit die Notwendigkeit ein zusätzliches Screencast-Tool zu installieren,
um Bildschirmaktivitäten in einem Video festzuhalten. Leider gilt dies nicht für alle Situationen,
denn der Gnome Shell Recorder nimmt nur den ganzen Bildschirm auf, und das ohne Ton.
Möchten Sie ohne Nachbearbeitung lediglich einen Teil des Bildschirms mit Audio aufzeichnen, 
ist die Installation einer Anwendung, die über ein weitgefächertes Spektrum an Leistungsmerkmalen verfügt, unumgänglich. 

### Anwendung

Mittels Tastenkombination `Strg+Alt+Shift+R` können Sie die Bildschirmaufnahme starten und beenden.
Die Aufnahme wird durch einen kleinen roten Kreis, rechts in der Taskleiste, signalisiert.

![Gnome Shell Recorder](../../images/gnome_shell_recorder.png)    
***Abbildung:*** Gnome Shell Recorder - Aufnahme

Die festgehaltenen Bilder werden in eine .webm-Datei geschrieben. 
Die Datei mit dem Muster "Bildschirmvideo von [Datum] [Uhrzeit].webm"
(Beispiel: "Bildschirmvideo von 15.04.2017 16:03:30.webm") befindet sich im Home-Verzeichnis,
im Unterordner Videos, und enthält den VP9-Videocodec. 
Die Framerate beträgt den Wert 30, was bedeutet, dass 30 Bilder pro Sekunde gespeichert werden.

### Einstellungen

Nach 30 Sekunden wird die Aufnahme automatisch beendet, denn jenes ist die Standard-Einstellung
für die maximale Screencast-Länge. Diese Einstellung und die Tastenkombination für den Start der Aufnahme
können geändert werden. Hier kommt das Einstellungstool dconf-editor ins Spiel. 
Dconf-editor gehört nicht zum Standard und muss nachinstalliert werden.
Bei der Linuxdistribution Fedora leitet man dies mit dem Befehl `su -c "dnf install dconf-editor"`
oder dem Paketmanager seiner Wahl in die Wege.

![dconf-editor - Installation](../../images/dconf-editor_fedora_install.png)    
***Abbildung:*** dconf-editor - Installation - Fedora


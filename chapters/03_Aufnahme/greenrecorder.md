## Green Recorder

![Green Recorder](../../images/greenrecorder_areachooser.png)    
***Abbildung:*** Green Recorder mit Area Chooser

Wer versucht mit dem SimpleScreenRecorder oder mit recordmydesktop unter [Wayland](https://wayland.freedesktop.org/) Screencasts aufzunehmen, 
der wird womöglich sein schwarzes Wunder erleben, denn in den Aufnahmen ist nichts weiter als ein schwarzer Bildschirm zu sehen.
Der Green Recorder ist ein weiteres Tool im großen Screencasting-Repertoire, aber eines der wenigen in der Sammlung
Screencasting unter Wayland. Was unter Wayland funtioniert ist der hauseigene Shell-Recorder von Gnome, der mit der
Tastenkombination Strg+Alt+Shift+R aktiviert und deaktiviert werden kann. 
Zur Erinnerung, die Länge der Aufnahme ist eventuell standardmäßig auf 30 Sekunden begrenzt,
kann aber mit dem dconf-editor verändert werden.
Der Green Recorder funktioniert ebenfalls unter Wayland und ist bei [github](https://github.com/green-project/green-recorder) zu finden. 
Die Installationshinweise für Ubuntu, Linux Mint, Fedora und Arch Linux stehen im git-Repository zur Verfügung.

### Installation

Unter Ubuntu und Linux Mint fügen Sie zuerst das dazugehörige PPA für den Green Recorder hinzu.
Nach dem Update können Sie den Green Recorder installieren. Folgende Kommandos werden für die Installation benötigt:

```
sudo add-apt-repository ppa:mhsabbagh/greenproject
sudo apt-get update
sudo apt-get install green-recorder
```

### Anwendung

Der Green Recorder ist fortan Teil der Multimedia-Sektion im Menü. 
Das Programm kann über das Menü oder mittels Kommando `green-recorder` gestartet werden. 
Unmittelbar nach dem Start wird eine kleine, einfache Oberfläche präsentiert.
Wo, in welchem Format und was aufgenommen wird kann ohne Umwege eingestellt werden.
Den Startschuss für die Aufnahme können Sie über den Button Aufnahme/Record, oben links im Fenster, geben.
Beendet ist die Aufnahme wenn Sie in der Taskleiste auf das Icon des Green Recorders klicken und anschließend auf "Stop Recording".

![Green Recorder - Stop Recording](../../images/greenrecorder_stoprecording.png)    
***Abbildung:*** Green Recorder - Aufnahme stoppen

Genutzt werden python, Gtk+3 und ffmpeg. Momentan werden die Formate mkv, avi, mp4, wmv und nut unterstützt.
Für Wayland wird nur das Format webm supportet. Der V8-Encoder wird für die Aufnahmen eingesetzt.
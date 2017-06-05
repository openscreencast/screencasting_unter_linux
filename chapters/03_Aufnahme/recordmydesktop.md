### recordMyDesktop {#recordMyDesktop}

![RecordMyDesktop](../../images/recordmydesktop.png)    
***Abbildung:*** RecordMyDesktop

[RecordMyDesktop](http://recordmydesktop.sourceforge.net/about.php) ist 
neben [Istanbul](https://wiki.gnome.org/Projects/Istanbul) und
[xvidcap](http://xvidcap.sourceforge.net/) eines der ältesten Screencast-Tools unter Linux.
Es war mein erstes Programm, das mich beim Erstellen von Bildschirmaufnahmen für lange Zeit unterstützt hat.
Die letzte Version 0.3.8.1 wurde im Dezember 2008 veröffentlicht.

Was vielleicht nur manche wissen, recordmydesktop ist ein Kommandozeilentool.
Die Pakete gtk-recordMyDesktop und qt-recordMyDesktop sind die Frontends.
Die mit den Bibliotheken für grafische Benutzeroberflächen GTK+ und Qt behafteten
Programme formen den benutzerfreundlichen Zugang auf Desktop-Umgebungen für recordMyDesktop.
Das Kommandozeilentool wurde in C geschrieben
und steht unter der [GPL](https://de.wikipedia.org/wiki/GNU_General_Public_License).
Die Programmiersprache Python mit pyGtk und pyQt4 wurde für die beiden Frontends benutzt.

#### Installation {#recordMyDesktop_Installation}

recordMyDesktop gehört bei den meisten Linux-Distributionen zum Standard. Für die Installation
muss keine weitere Paketquelle hinzugefügt werden. Das Paket für das Kommandozeilentool
heißt `recordmydesktop`. Die Pakete für die Frontends heißen `gtk-recordmydesktop` und
`qt-recordmydesktop`. 

##### Installation unter Fedora {#recordMyDesktop_Installation_Fedora}

Bei Fedora lauten die Befehle für Installation:

```
dnf install recordmydesktop
dnf install gtk-recordmydesktop
dnf install qt-recordmydesktop
# für alle drei Pakete auf einmal
dnf install recordmydesktop gtk-recordmydesktop qt-recordmydesktop
```

In der Gnome3-Desktopumgebung kann das Programme Software verwendet werden.

##### Installation unter Fedora {#recordMyDesktop_Installation_LinuxMint}



#### Anwendung {#recordMyDesktop_Anwendung}

##### Anwendung in der Kommandozeile {#recordMyDesktop_Terminal}

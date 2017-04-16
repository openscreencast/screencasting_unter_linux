### EasyScreenCast {#easyscreencast}

![EasyScreenCast](../../images/easyscreencast.png)    
***Abbildung:*** EasyScreenCast

[EasyScreenCast](https://extensions.gnome.org/extension/690/easyscreencast/) ist eine Gnome Shell-Erweiterung.
Ebenso wie der [Gnome Shell Recorder](gnome_shell_recorder.md),
benutzt EasyScreenCast die integrierte Screencast-Funktion von Gnome.
Aber im Vergleich zum Gnome Shell Recorder besitzt EasyScreenCast einen erheblich ausgedehnten Handlungsspielraum.
Das Multimedia-Framework [gstreamer](https://de.wikipedia.org/wiki/GStreamer)
verwaltet die Aufnahmen von EasyScreenCast und dem Gnome Shell Recorder.

#### Installation {#easyscreencast_installation}

Möchten Sie den Funktionsrahmen von Gnome durch eine Gnome Shell-Erweiterung aufstocken,
werden Sie vermutlich auf der Webseite https://extensions.gnome.org/ fündig.
Durch die Erweiterung [GNOME Shell-Integration](https://addons.mozilla.org/de/firefox/addon/gnome-shell-integration/)
für den Webbrowser Firefox können die Gnome Shell-Erweiterungen direkt
auf der [Webseite für Extensions](https://extensions.gnome.org/) gemanagt werden.
Damit die Browser-Erweiterung funktioniert, muss außerdem noch
der [Native Host-Connector](https://wiki.gnome.org/Projects/GnomeShellIntegrationForChrome/Installation) installiert werden.
Bei Fedora wird dazu das Copr region51/chrome-gnome-shell aktiviert und daraus das Paket chrome-gnome-shell installiert.

```
su -c "dnf copr enable region51/chrome-gnome-shell"
su -c "dnf install chrome-gnome-shell"
```

Unter Ubuntu und Linux Mint ist das Paket
für den [Native Host-Connector](https://wiki.gnome.org/Projects/GnomeShellIntegrationForChrome/Installation)
in den Universe Repositories vorhanden und kann mittels `sudo apt-get install chrome-gnome-shell` installiert werden.

![EasyScreenCast - Webseite](../../images/easyscreencast_webseite.png)    
***Abbildung:*** EasyScreenCast - Webseite

Daraufhin können Sie die Gnome Shell-Erweiterung [EasyScreenCast](https://extensions.gnome.org/extension/690/easyscreencast/)
auf der Webseite https://extensions.gnome.org/ auswählen. 
Bewertungen, Kommentare, eine kurze Beschreibung und ein
Link zu dem [git-Repository](https://github.com/EasyScreenCast/EasyScreenCast) des Projektes befinden sich
auf der Detailseite von EasyScreenCast.
Für die Inbetriebnahme der funktionsreichen Screencast-Erweiterung müssen Sie auf den Kippschalter (On/Off) klicken
und anschließend die Frage: "EasyScreenCast" von extensions.gnome.org herunterladen und installieren ? mit Installieren
beantworten.

![EasyScreenCast - Installation](../../images/easyscreencast_install.png)    
***Abbildung:*** EasyScreenCast - Installation


#### Einstellungen {#easyscreencast_einstellungen}

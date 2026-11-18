# Charli FPS — For Low Performance Usage

Eine Windows-App für FPS- und Frametime-Messungen, kompakte Gaming-Overlays und nachvollziehbare Benchmarks – mit einstellbarer Oberfläche und acht animierten Themes.

**[Aktuelle Version herunterladen](https://github.com/yousefayat732-prog/charli-fps-releases/releases/latest)** · **[Alle Veröffentlichungen](https://github.com/yousefayat732-prog/charli-fps-releases/releases)**

Dieses öffentliche Repository enthält Installationspakete, den Update-Kanal und Vorschaubilder. Der Quellcode bleibt privat.

## Ein Blick in Charli FPS

![Dashboard mit Solar-Dusk-Hintergrund](screenshots/dashboard.png)

Die Vorschau zeigt die echte Windows-Oberfläche ohne laufende Spielmessung. Fehlende Messwerte erscheinen ausdrücklich als nicht verfügbar.

![Acht Themes in den Einstellungen](screenshots/designs.png)

Forest, Pure Black, Azure Night, Glacier, Solar Dusk, Violet Pulse, Emerald Luxe und Crimson Steel sind direkt in der App auswählbar.

## Was die App bietet

- Externe FPS- und Frametime-Erfassung über PresentMon/ETW, mit klar erkennbarer Messquelle und Verfügbarkeit.
- Anpassbare Overlays mit Position, Größe, Farben und auswählbaren Messwerten; Spielprofile, Benchmark-Auswertung und Exporte.
- Vollständige Einstellungsseite mit Suche, Kategorien und passenden Untergruppen.
- Ein gemeinsamer Player für acht lokale MP4-Hintergründe. Nur das aktive Theme wird geladen; Hardwaredecodierung wird genutzt, wenn Windows und Treiber sie unterstützen. Minimieren und aktivierte Spiel-Pausierung reduzieren die Hintergrundarbeit. Reduced Motion verwendet das Originalbild.
- Einstellbare Hover- und Klickübergänge sowie Eco-, Balanced- und Premium-Profile für die Oberfläche. Die visuelle Glättung verändert keine gemessenen FPS.

## Installation und Updates

1. Das aktuelle **Setup-x64.exe** unter [Releases](https://github.com/yousefayat732-prog/charli-fps-releases/releases/latest) herunterladen und ausführen.
2. Den Einrichtungsassistenten durchgehen. Die externe Messhilfe kann eine Windows-Berechtigungsabfrage benötigen.
3. Spätere Updates stehen unter **Einstellungen → System & Allgemein → Updates → Nach Updates suchen** bereit. Bei einer neueren Version erscheint rechts **Installieren**. Andernfalls erscheint der rote Hinweis **Kein neues Update verfügbar**; Verbindungsfehler werden gesondert angezeigt.

Bestehende Einstellungen und Profile bleiben bei normalen Updates erhalten. Eine Deinstallation mit ausdrücklich gewählter Datenlöschung ist davon ausgenommen. Sehr alte Versionen ohne Update-Funktion benötigen einmalig das aktuelle Setup.

## Voraussetzungen und Spielkompatibilität

Windows 10 oder 11, **64 Bit**. Nicht verfügbare Sensoren werden nicht durch Beispielwerte ersetzt. Videohintergründe sind optional; bei fehlender Medienunterstützung oder einem Ladefehler bleibt das Originalbild erhalten.

Ein externes Overlay ist nicht in jedem Spiel und exklusiven Vollbildmodus sichtbar. Für VALORANT/Vanguard gelten die vorhandenen Schutzregeln: keine Umgehung und keine erzwungenen Hooks. Je nach Spiel ist die Anzeige im Dashboard auf einem zweiten Monitor die geeignete Alternative. Eine allgemeine Anti-Cheat-Freigabe wird nicht behauptet.

![Sichtbares Eingabefeld beim Speichern eines Presets](screenshots/preset-speichern.png)

## Transparente Veröffentlichung

Update-Dateien werden mit **Ed25519** signiert und zusätzlich mit einer SHA-256-Prüfsumme veröffentlicht. Diese Update-Signatur ist kein Windows-Authenticode-Herausgeberzertifikat. Es werden keine Benutzerkonfigurationen, privaten Protokolle oder Signierschlüssel veröffentlicht.

Version 0.24.0 wurde mit gezielten Mess-, Einstellungs-, Layout- und Interaktionstests geprüft. Die acht Videos wurden lokal über jeweils zwei vollständige Loops geprüft. Das ist keine Garantie für jeden GPU-Treiber, physisch sichtbare 180 Bilder/s oder die Sichtbarkeit in jedem Spiel. Weitere Einzelheiten stehen in den jeweiligen Release-Hinweisen.

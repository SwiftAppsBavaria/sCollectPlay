# Hilfe zu sCollectPlay und sCollectPlay Lite

## Was die App tut

sCollectPlay spielt Musik, Hörbücher, Podcasts, Filme und E-Books direkt aus deinen Ordnern,
aus einer iTunes- oder Apple-Music-XML oder aus einer sCollect-Mediathek. Es kopiert nichts,
importiert nichts und schreibt nichts in deine Dateien.

## Erste Schritte

Wähle beim Start eine der drei Quellen — oder später über das Menü **Ablage**:

1. **Ordner scannen…** — ein beliebiger Ordner samt Unterordnern.
2. **XML-Mediathek öffnen…** — eine aus Apple Music exportierte XML-Datei. Du erzeugst sie in
   Apple Music unter **Ablage → Mediathek → Mediathek exportieren**.
3. **sCollect Mediathek wählen…** (⇧⌘O) — den Hauptordner einer mit sCollect angelegten
   Mediathek.

Die Titelzeile des Fensters nennt danach, was geladen ist, etwa „Ordner „Musik““; zeigst du
auf den Titel, erscheint der vollständige Pfad.

## Häufige Fragen

**Warum heißen die Medientypen „bis 10 Min.“ oder „30–60 Min.“?**
Beim Ordner-Scan weiß die App nicht, ob eine Datei ein Song, ein Hörbuch oder ein Podcast
ist — das steht in keinem Ordner. Sie teilt Audio und Video deshalb nach der Spieldauer ein.
Bei einer XML oder einer sCollect-Mediathek stehen die echten Typen da, also Musik, Hörbuch,
Spielfilm und so weiter.

**Die App fragt nach einem Ordner, den ich schon einmal gewählt habe.**
macOS erlaubt einer App nur den Zugriff auf Ordner, die du ihr ausdrücklich gibst. Liegen
die Dateien einer XML oder die Medienordner einer Mediathek außerhalb des gewählten Ordners,
fragt die App einmal nach jedem dieser Ordner und merkt sich die Erlaubnis.

**Ein Titel meldet „Datei nicht lesbar“.**
Der App fehlt die Erlaubnis für den Ordner, in dem die Datei liegt — oder das Laufwerk ist
nicht angeschlossen. Unter **Einstellungen → Allgemein → Medienordner** siehst du, welche
Ordner erlaubt sind, und kannst mit **Wählen** eine fehlende Erlaubnis nachholen.

**Ein Film öffnet sich in einem anderen Programm.**
Formate, die macOS nicht selbst abspielt — etwa MKV, AVI oder DivX —, gibt die App an einen
anderen Player weiter. Welchen, stellst du unter **Einstellungen → Wiedergabe/Playlist →
Externer Player für nicht-unterstützte Codecs** ein; VLC und IINA werden erkannt, wenn sie
installiert sind.

**Beim Start fragt die App, ob sie eine Quelle auf einem Netzlaufwerk laden soll.**
Ein nicht erreichbares Netzlaufwerk könnte den Start lange aufhalten. Die Frage lässt sich
mit **Nicht mehr nachfragen** abschalten und unter **Einstellungen → Allgemein** wieder
einschalten.

**Kann ich Tags oder Titelangaben bearbeiten?**
Nein. sCollectPlay ist ein Abspieler und verändert keine Metadaten.

**Wie bringe ich eine Auswahl nach Apple Music?**
Über das Kontextmenü **Als Playlist an Apple Music senden** oder über **Ablage → Playlist an
Apple Music senden…**. Beim ersten Mal fragt macOS, ob die App Apple Music steuern darf.

**Was kann sCollectPlay, was die Lite-Ausgabe nicht kann?**
sCollectPlay bietet zusätzlich den Spaltenbrowser, eigene und intelligente
Wiedergabelisten, das Zusammenführen mehrerer Ordner, die Listen der zuletzt benutzten
Quellen und das Wiederherstellen der letzten Quelle beim Start. sCollectPlay Lite spielt je
Sitzung eine Quelle.

**Kann ich eine Löschung widerrufen?**
Ja, mit ⌘Z, solange die Datei noch im Papierkorb liegt. Auf Laufwerken ohne Papierkorb
fragt die App vorher, ob endgültig gelöscht werden soll — das lässt sich nicht widerrufen.

## Kontakt

SwiftAppsBavaria · SwiftAppsBavaria@gmx.net

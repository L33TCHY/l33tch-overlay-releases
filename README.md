# L33TCH Overlay – Downloads

Hier liegen die Installationsdateien für das **L33TCH Overlay**, ein Chat-Overlay für Twitch und YouTube Live. Das Repository enthält nur die fertigen Programme, keinen Quellcode.

## Was kann das Overlay?

- Twitch- und YouTube-Chat als transparentes Fenster oder als Browserquelle in OBS
- Emotes von BetterTTV, FrankerFaceZ und 7TV sowie Twitch-Badges
- Sprachausgabe (TTS) mit frei wählbarer Stimme
- Zuschauerzahlen, Filter und Darstellung (Farben, Schriftgröße, Deckkraft) einstellbar
- Automatische Erkennung des YouTube-Livestreams nach der Anmeldung
- Automatische Update-Prüfung

## Installation

1. Unter [**Releases**](../../releases) die neueste Version öffnen und die Datei `L33TCH Overlay Setup x.y.z.exe` herunterladen.
2. Die Datei starten und den Installationsordner auswählen.
3. Beim ersten Start meldest du dich im Manager bei Twitch und/oder YouTube an.

Deinstallieren kannst du das Programm über die Windows-Einstellungen unter **Apps**.

### Hinweis zu Windows SmartScreen

Beim ersten Start zeigt Windows eventuell „Der Computer wurde durch Windows geschützt“. Das Programm ist nicht digital signiert, deshalb warnt Windows vor jeder unbekannten Datei. Klicke auf **Weitere Informationen** und dann auf **Trotzdem ausführen**.

## Chat in OBS einbinden

1. In OBS unter **Quellen** auf **+** klicken und **Browser** hinzufügen.
2. Die Adresse aus dem Manager (Bereich *OBS-Quelle*) als URL einfügen.
3. Die Option **„Audio über OBS steuern“** ausgeschaltet lassen, sonst bleibt die Sprachausgabe stumm.

## Updates

Das Programm prüft beim Start und danach alle paar Stunden, ob eine neuere Version vorliegt. Gefundene Updates werden nur nach deiner Bestätigung heruntergeladen. Du kannst im Manager auch selbst auf **Nach Updates suchen** klicken.

## Probleme melden

Wenn etwas nicht funktioniert, exportiere im Manager die Diagnose-Datei und schicke sie mit einer kurzen Beschreibung an den Entwickler. Darin sind Zugangsdaten geschwärzt und Chat-Nachrichten nicht enthalten.

---

© L33TCH

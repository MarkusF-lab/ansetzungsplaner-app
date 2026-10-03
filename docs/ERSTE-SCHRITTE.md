# Ansetzungsplaner – Erste Schritte

## Wozu die App da ist

Der Ansetzungsplaner besetzt die Schiedsrichter- und Kampfgerichtsplätze eurer Heimspiele und schickt
das Ergebnis als Text und Bild in die WhatsApp-Gruppen. Er läuft auf Android-Handys und unter Windows.

Der Ablauf an jedem Wochenende:

1. Spielplan von handball.net abrufen.
2. Plätze auf dem Board mit Personen besetzen; die App prüft dabei Lizenz, Altersklasse und
   Terminkonflikte.
3. Ansetzungen in die Gruppen schicken.
4. Zusagen abhaken und Änderungen am Spielplan klären.

Vorab lässt sich mit der Verfügbarkeitsabfrage fragen, wer an den kommenden Wochenenden kann.

## Installation und Einrichtung

Nach der Installation fragt die App einmal nach dem Verein; danach geht es direkt los.

**Windows installieren**

1. `Ansetzungsplaner-Setup-<Version>.exe` unter
   [Releases](https://github.com/MarkusF-lab/ansetzungsplaner-app/releases/latest) herunterladen
   und doppelklicken. Administratorrechte sind nicht nötig.
2. Warnt Windows mit „Der Computer wurde durch Windows geschützt“: „Weitere Informationen“ →
   „Trotzdem ausführen“. Die Warnung kommt, weil das Setup nicht signiert ist.
3. Den Schritten folgen; auf Wunsch entsteht eine Verknüpfung auf dem Desktop.

Eine neuere Version wird genauso über die alte installiert; die Daten bleiben erhalten, auch beim
Deinstallieren.

Offen: Wie die Android-App zu euch kommt, steht hier noch nicht.

**Neu einrichten**

1. App starten. Es erscheint „Verein einrichten“.
2. Vereinsname, Kurzname und „Kürzel ohne Logo“ eintragen (etwa TSV Lichtentanne e.V.,
   TSV Lichtentanne, TSV).
3. Bei „Verein auf handball.net“ über die Lupe den Verein suchen und auswählen. Ohne diesen Eintrag
   lässt sich kein Spielplan abrufen.
4. „Speichern und loslegen“ tippen. Logo, Farben und Regeln lassen sich später in den Einstellungen
   ändern.

**Einen vorhandenen Stand übernehmen**

Wer schon geplant hat, gibt seinen Stand per Sicherung weiter:

1. Beim bisherigen Gerät: Einstellungen (Zahnrad) → Daten sichern → „Sicherung erstellen“, Datei
   speichern.
2. Die Datei direkt weitergeben, etwa per Einzelnachricht oder USB-Stick. Sie enthält Namen und
   Lizenzdaten, gehört also nicht in eine Gruppe.
3. Beim neuen Gerät: die Einrichtung oben einmal durchlaufen, Angaben egal.
4. Einstellungen → Daten sichern → „Sicherung laden“, Datei wählen, „Laden“ bestätigen.

Laden ersetzt alles auf dem neuen Gerät. Die App des Empfängers darf nicht älter sein als die des
Absenders, sonst meldet sie „Sicherung stammt aus einer neueren App“. Geräte gleichen sich nicht ab:
Nach der Übergabe trägt nur noch einer ein.

## Personen anlegen

Jede Person, die pfeift oder am Kampfgericht sitzt, wird einmal unter „Personen“ angelegt; daraus
prüft die App später jeden Vorschlag.

1. Personen öffnen, „Person hinzufügen“ tippen.
2. Name eintragen.
3. Unter „Lizenzen“ die SR- und/oder KG-Lizenz mit „gültig bis“ setzen. Ohne Lizenz schlägt die App
   die Person für diese Plätze nicht vor.
4. Unter „Einsetzbar in Altersklassen“ festlegen, wofür die Person freigegeben ist, oder „Alle
   Altersklassen“ lassen.
5. Eintragen, in welchen Mannschaften sie spielt oder welche sie trainiert. Rund um diese Spiele ist
   sie dann gesperrt.
6. Speichern.

Wer eine Weile nicht kann, wird auf inaktiv gestellt statt gelöscht. Inaktive Personen erscheinen
nicht in der Auswahl. Löschen geht nur, solange eine Person keine Einsätze hat.

Mannschaften entstehen beim ersten Abruf des Spielplans. Deren Kürzel (etwa F1 für die Frauen)
lassen sich in den Einstellungen umbenennen.

## Ein Wochenende besetzen

Das Board zeigt alle Heimspiele eines Wochenendes mit ihren Plätzen; oben steht, wie viele schon
besetzt sind.

1. Mit den Pfeilen das Wochenende wählen.
2. „Spielplan aktualisieren“ (Kreispfeile) tippen. Die App holt die Spiele von handball.net und legt
   beim ersten Mal die Mannschaften an.
3. Einen freien Platz antippen, etwa „SR 1“. Die Auswahl zeigt die Personen in drei Gruppen:
   „Verfügbar“, „Mit Hinweis“ und „Nicht möglich“, jeweils mit Begründung und der Zahl bisheriger
   Einsätze in der Saison.
4. Person wählen. Übernimmt ein anderer Verein den Platz, unten „Anderer Verein“ eintragen.

Der Punkt vor dem Namen zeigt das Ergebnis der Prüfung:

| Farbe | Bedeutung | Beispiele |
| --- | --- | --- |
| Grün | passt | – |
| Orange | geht, aber mit Hinweis | Lizenz läuft bald ab, weiterer Einsatz am selben Tag, knapper Hallenwechsel |
| Rot | gesperrt | keine oder abgelaufene Lizenz, Altersklasse nicht freigegeben, spielt oder trainiert selbst, zeitgleich eingeteilt, Fremdansetzung |

**Weitere Handgriffe**

- Platz wieder freigeben: Platz antippen → „Platz leeren“.
- Turnier: „Besetzung von Spiel 1 auf alle übernehmen“ spart das Einzeleintragen.
- Bemerkung zu einem Spiel (Stift-Symbol), etwa „KG bitte 30 Minuten vor Anwurf da sein“. Sie steht
  später mit im WhatsApp-Text.
- Spiel fehlt im Spielplan, etwa ein Freundschaftsspiel: „+“ → „Spiel erfassen“.
- „SR neutral (Verband)“ unter einem Spiel heißt: Der Verband stellt die Schiedsrichter, zu besetzen
  ist nur das Kampfgericht.

## Zusagen und Änderungen

Jede Platzkarte trägt rechts einen Haken für die Zusage; geänderte Spiele meldet die App beim
nächsten Abruf selbst.

**Zusage abhaken**

- Hat jemand zugesagt: Haken auf seiner Platzkarte antippen. Er wird grün, im WhatsApp-Text steht
  dann ✅ hinter dem Namen, im Bild ein Häkchen.
- Nochmal antippen nimmt die Zusage zurück.
- Wird eine andere Person eingeteilt, beginnt der Platz wieder ohne Zusage.

**Geänderte Spiele klären**

Nach „Spielplan aktualisieren“ markiert die App Spiele, die sich auf handball.net geändert haben:

| Hinweis am Spiel | Was passiert ist | Was zu tun ist |
| --- | --- | --- |
| verlegt | Termin oder Halle haben sich geändert | Eingeteilte informieren, dann Hinweis antippen → „Geprüft“ |
| Status unklar | handball.net meldet einen unbekannten Status | Prüfen, dann „Geprüft“ |
| nicht mehr im Spielplan | Spiel ist auf handball.net verschwunden | „Behalten“ (wird manuelles Spiel) oder „Löschen“ |

Betroffene Plätze zeigen bis dahin ein Uhr-Symbol. Einzelne Plätze lassen sich damit als geklärt
markieren; „Geprüft“ am Spiel klärt alle auf einmal. Eine Zusage verfällt bei einer Änderung, sie
muss neu abgehakt werden.

## Veröffentlichen und abfragen

Unter „Veröffentlichen“ (am Handy „Teilen“) entsteht der Text für die WhatsApp-Gruppe, oben
umschaltbar zwischen „Ansetzungen“ und „Abfrage“ sowie zwischen Schiedsrichter und Kampfgericht.

**Ansetzungen eines Wochenendes**

1. „Ansetzungen“ wählen, mit den Pfeilen das Wochenende einstellen.
2. Gruppe wählen: Schiedsrichter oder Kampfgericht. Fremdansetzungen stehen nur im
   Schiedsrichter-Text.
3. Am Handy „Text und Bild teilen“ und in WhatsApp die Gruppe wählen. Am Laptop „Text kopieren“ bzw.
   „Bild kopieren“ und in WhatsApp Desktop einfügen.
4. Danach die andere Gruppe genauso.

Offene Plätze erscheinen als „offen“. Ab elf Spielen teilt die App das Bild in eines pro Tag.
Überschrift und Schlusszeile kommen aus den Einstellungen.

**Verfügbarkeit abfragen**

1. „Abfrage“ wählen.
2. Zeitraum wählen: 2, 4, 6 oder 8 Wochen ab dem kommenden Wochenende. Die App merkt sich die Wahl.
3. Gruppe wählen und den Text teilen bzw. kopieren.

Die Abfrage listet alle Spiele des Zeitraums mit den schon eingeteilten Namen und den offenen
Plätzen. So sieht jeder, wo noch jemand fehlt. Die Abfrage gibt es nur als Text, ohne Bild.

## Fremdansetzungen

Pfeift jemand von euch für den Verband ein fremdes Spiel, wird das unter „Fremdansetzungen“ (am Handy
„Fremd“) eingetragen, damit die App ihn rund um diesen Termin sperrt.

1. „Fremdansetzung erfassen“ tippen.
2. Schiedsrichter, Datum und Uhrzeit wählen.
3. Dauer in Minuten, Spiel (etwa Regionsliga Männer) und Ort eintragen.
4. Speichern.

Die Liste zeigt die anstehenden Fremdansetzungen; erledigte oder abgesagte über das
Papierkorb-Symbol löschen. Wie viel Puffer vor und nach einer Fremdansetzung gilt, steht in den
Einstellungen unter „Regelwerte“.

## Einstellungen und Datensicherung

Das Zahnrad oben führt zu den Einstellungen; Änderungen gelten erst nach „Speichern“, und die App
fragt nach, bevor ungespeicherte Änderungen verloren gehen.

| Bereich | Was sich einstellen lässt |
| --- | --- |
| Profil | Vereinsname, Kurzname, Kürzel, Verein auf handball.net |
| Logo und Farben | Vereinslogo (PNG oder JPG bis 1 MB), Haupt- und Akzentfarbe; Vorschau des WhatsApp-Bilds mit Kontrastwarnung |
| Regelwerte | Puffer vor und nach Heimspielen und Fremdansetzungen, Hinweis bei knappem Hallenwechsel, Zuschlag auf die Spielzeit, Vorwarnung vor Lizenzablauf, eigene SR-Plätze je Altersklasse |
| Textbausteine für WhatsApp | Überschriften für Schiedsrichter und Kampfgericht, Schlusszeile; {Datum} wird durch das Wochenende ersetzt |
| Kürzel für neue Mannschaften | Vorlagen wie mC oder F1 |
| Daten sichern | Sicherung erstellen und laden |
| Mannschaften | Kürzel bestehender Mannschaften umbenennen |
| Problem melden | Fehlerbericht an den Entwickler schicken |

**Regelmäßig sichern.** Die Daten liegen nur auf dem Gerät. Geht das Handy verloren, ist ohne
Sicherung alles weg. Eine Sicherung nach jedem Planungsabend ist eine gute Gewohnheit; die Datei
gehört an einen Ort, auf den nur ihr Zugriff habt.

## Problem melden

Läuft etwas schief, geht der Bericht über Einstellungen → Problem melden → „Bericht senden“ an den
Entwickler.

- Am Handy öffnet sich das Teilen-Menü mit Bericht und Protokolldatei; dort WhatsApp oder Mail wählen.
- Unter Windows kopiert die App den Bericht in die Zwischenablage und öffnet das Mailprogramm. Den
  Bericht in die Mail einfügen.

Bitte dazuschreiben, was passiert ist und was du gerade gemacht hast; ein Screenshot hilft. Der
Bericht enthält App-Version, System und ein technisches Protokoll ohne Namen.

## Häufige Fragen

**Der Spielplan lässt sich nicht abrufen.** In den Einstellungen fehlt der Verein auf handball.net,
oder es gibt keine Internetverbindung.

**Eine Person fehlt in der Auswahl.** Inaktive Personen erscheinen gar nicht. Steht sie unter „Nicht
möglich“, nennt die App den Grund, etwa fehlende Lizenz oder nicht freigegebene Altersklasse.

**Ein Spiel taucht nicht auf.** Das Board zeigt nur Heimspiele, für die ihr zuständig seid. Fehlt
eines trotzdem: „Spiel erfassen“.

**Im Bild fehlen die Emojis der Überschrift.** Das ist gewollt; im Bild sehen Emojis je nach Gerät
unterschiedlich aus. Im Text bleiben sie.

**Zwei Leute planen auf zwei Geräten.** Das geht schief: Die Geräte gleichen sich nicht ab, eine
geladene Sicherung überschreibt alles. Es plant immer nur einer.

# Telekom Datennutzung Widget (iOS 14) 

### Funktionen:
- aktuell verfügbares Datenvolumen
- bereits verbrauchtes Datenvolumen mit entsprechender Färbung (grün, gelb, orange, rot) je nachdem wie viel bereits verbraucht wurde (+ Prozentanzeige)
- Datum, bis zu dem das aktuelle Datenvolumen noch verfügbar ist (+ Anzahl Tage und Studen bis zu diesem Datum)
- Widget öffnet bei Berührung automatisch die Telekom Website um noch mehr Infos zur Datennutzung anzuzeigen
- angepasstest Design für medium und kleine Widgets
- automatisches Synchronisieren über iCloud (Datenvolumen auch an anderen iCloud Geräten ablesbar)
- (auch lokale Speicherung der Daten möglich)

### Setup:
1. App <a href="https://scriptable.app/">Scriptable</a> herunterladen.
2. Das Telekom Datennutzung Widget <a href="https://github.com/marcjulianschwarz/tmobile-data-usage-widget/blob/main/telekom-data-usage.js">Skript</a> kopieren.
3. Scriptable App öffnen, neues Skript erstellen, zuvor kopiertes Skript einfügen.
4. Auf den Homescreen wechseln, Scriptable Widget hinzufügen.
5. In den Widget Einstellungen beim Punkt "Script" das eben erstellte Skript auswählen.
6. (Für die erste Verwendung des Widgets muss das WLAN **deaktiviert** sein und eine Verbindung mit dem Mobilfunknetz vorhanden sein.)

**Für lokale Speicherung:**
Damit die Daten nur lokal gespeichert werden, muss bei Schritt 5 im Feld "Parameter" der Bergriff "local" angegeben werden.
Nun sollte das Widget auch ohne iCloud Anmeldung funktionieren.


### Fragen?
Gerne beantworte ich alle Fragen und freue mich über Feedback, Anregungen und Ideen, die zur Verbesserung des Widgets beitragen können.
Meine Kontaktmöglichkeiten:
- Twitter <a href="https://twitter.com/marcjulian_DS">@marcjulian_DS</a>
- Email/Website <a href="https://www.marc-julian.de/">marc-julian.de</a>

### Bilder:

<div>
<img src = "https://github.com/marcjulianschwarz/tmobile-data-usage-widget/blob/main/images/IMG_0547.png" width=240px>
<img src = "https://github.com/marcjulianschwarz/tmobile-data-usage-widget/blob/main/images/IMG_0544.jpeg" width=240px>
<img src = "https://github.com/marcjulianschwarz/tmobile-data-usage-widget/blob/main/images/IMG_0545.jpeg" width=240px>
<img src = "https://github.com/marcjulianschwarz/telekom-data-usage-widget/blob/main/images/E10F0CF9-83A4-4628-8949-442AC0281524.jpeg" width=240px>  
</div>


### Zukünftige Funktionen:
- Option zur Darstellung des Verbrauchs als Diagramm (in medium und großem Widget)
- Benutzerdefinierte Hintergründe

#### Updates:
30.10.2020: 
- lokale Speicherung möglich
- verbessertes Design des Medium-Size Widgets.

31.10.2020: 
- Schriftgröße in kleinem Widget wurde vergrößert.
- Tage und Stunden bis zu dem Datum, an dem das aktuelle Datenvolumen noch verfügbar ist.

### Bekannte Probleme:
- Eingeschränkter Darkmdoe Support für SFSymbols (WLAN Zeichen)
- Widget funktioniert nur mit deutschen Telekom Verträgen


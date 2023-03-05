# Sitzungsprotokolle

[toc]


***

## 2023-02-28 Binningen - Probespielen

- [x] [Spiel](https://de.wikipedia.org/wiki/Robo_Rally) ausprobiert

Zu besprechen:

-    Wo Protokoll aufschreiben/Tagebuch aufschreiben?
~~ownCloud~~ **[HackMD](https://hackmd.io)** wird genutzt, Pascal gibt Einführung

- Tools für
  - Tagebuch (HackMD ~~ownCloud~~)
  - Tasks (Gantt & Discord)
  - Zeitplan (Wie oben)
  - Code sharing (Git-Lab)
  - netzwerk tool ([Hamachi](https://vpn.net/))
- Teamname: U-turners, Game "Robo Rally"
- Meilensteine Besprechen
- Susan macht Projektplan mit Gantt
- Pascal setzt Tagebuch auf
- Cielle schreibt ersten Eintrag


### Analyse
Problem/Fragestellung
Implementierung des Brettspiels "Robo Rally" in Java

### Anforderungen
- Toby


### Spielregeln
- Toby

### Aufgaben verteilung
- Cielle: Written concept
- Susan: Game-Mockup
- Pascal: Power point
- **Alle**: sich überall einloggen & Software herunterladen

- Nächste Sitzung planen
- Samstag morgen: 10:00 Binningen

- wöchentlicher Termin planen
Zischtig 12:00-14:00

### Anmerkungen
**Susan**
- Anmerkungen müssen konsequent aufgenommen werden, **beim Thema bleiben**!

**Toby**
- Buch bestellt.

**Cielle**
- Offene Kommunikation wichtig, immer bescheid geben wenn was zu viel/zu wenig.

## 2023-03-04 Dornach - Masterplan erstellen

Zu besprechen:

- Was wurde erledigt
- Vortrag/Planung
- Server Client Protokoll/Beziehungen
- Wo machen wir unsere Dokumentation
- Tagebuch und Sitzungsprotokoll, HackMD okay?
- OwnCloud aufsetzen

### Was wurde erledigt
**Mockup - Susan**
- Mockup fertig und aufgesetzt
- Problem: Kein Platz für mehr als 4 Spieler, evt 5.
- Spieler evt. auf 4-5 beschränken
- Spieler evt. oben in einer Reihe anstelle von Seite, Spielfeld in der Mitte
- **Design simpel halten**
- Evt Spielfeld etwas vergrössern und Spieler kompakter gestalten
- Ein Chat-Fenster muss inbegriffen sein

**Recherche/Spielregeln - Toby**
- Richard Garfield, same guy as MtG, erstes Spiel
- Verschiedene Versionen, Spielfeld hat grösste Änderung
- App für Spiel existiert
- Regelwerk existiert online -> Siehe [Notizen Toby](insert link) für Ausführliche Beschreibung

    **Anmerkung Pascal**
    - Wiki erstellung muss übernommen werden, zu Erklärung von Begriffen
    - Kurze Erklärung von Wiki von Begriffen und Klassen
    - evt. Folien zusammenfassung auf Wiki oder HackMD speichern?
    - Pascal macht Zusammenfassung
- Anforderungen:
    - Host muss Spielplan auswählen
    - Spieler Roboter/Farbe auswählen?

**Gantt - Susan**
- Sehr wenige Funktionen
- Wochenende augeblendet -> kann Abgabetermine nicht auf Wochenende verlegen!
- Nur als Zeitplan geeignet, nicht als Taskmanager
- Cloud muss in Browser aktiviert werden und dann im Programm editiert werden, sehr umständlich.
- **Susan fragt Tutor wieso Gantt**

    **Anmerkung Pascal**
        - Hub für Fragen?
        - Discord als Lösung
- Für nächstes Treffen: Neues Programm finden!
- Susan sucht nach neuen Methoden -> HackMD?

**Protokoll - Cielle**
- Sitzungsprotokoll funktioniert, Mark-Down klappt
- Kann auch von anderen übernommen werden
### Vortrag/Planung
- Vortrag wurde auf HackMD erstellt
- Bei Bilder muss Hintergrund vorhanden sein
- HackMD nicht besonders geeignet, PPP oder LateX
- Susan und Pascal zusammen Latex aufsetzen, Montag 06.03.2023 16:00 im ZG
#### Aufteilung Vortrag
- Susan
Gantt und Tools vorstellen
- Toby
Spielregeln
- Pascal
Server - Client
- Cielle
Begrüssung und Einführung

Anmerkung
Was bedeutet Requirment Analysis?
-> Am Montag nachfragen
### Server Client Protokoll/Beziehungen

#### Client elemente
- Spielbretter werden dargestellt
- Generieren von GUI
- Auswahl von Zugkarten
- Auwahl von Power-Down
- Chat Input
- Chat Output darstellen

#### Server elemente
- Zustand des Spielbretts (Position und Orientierung, Brett-Elemente)
- Spezifisches Brett wird gewählt
- Spielregeln
- Win/Loose Conditions
- Spielerreihenfolge
- Führt Bewegungen/Spielbrett aus
- Leben und Schaden und Zustände von Spielern
- Verteilt Zugkarten
- Chatlog
### Wo Speichern wir unsere Daten
ownCloud wird als Speicher benutzt
WhatsApp Chat für Notfälle
### Tagebuch und Sitzungsprotokoll, HackMD okay?
Okay
### Owncloud einführung

# Migriert zu https://github.com/HauthyPiyces/HPMultitool


Dies ist ein kleines Projekt geteilet unter kollegen was die "wichtigsten" bzw. nützlichsten tools die man so vielleicht brauchen könnte an seinem PC einbinden soll, im selben Moment dient es als training für mich.

# Momentan beinhaltet das Projekt:

Youtube Web Downloader

Text Speicher mit lokaler Verschlüsselung (Titel (genutzt zum laden) + Inhalt (welcher gespeichert werden soll))

Integrierter Festplatten/Ordner Scanner (WinDirStats https://windirstat.net/)

Ein Basic Autoklicker,

~~RAM- und CPU limiter für Neugestartete anwendungen (zu niedrige limits = meist absturz),~~ auskommentiert, kommt vielleicht wieder (7.11.2025) 

Ressourcen nutzungs Overlay (minimal umfärbbar)

KeyOverlay

Automatisches Rejoinen nach Internetausfall/Lag/AFK kick und alles was ähnnlich aussieht wie diese fehler meldungen (Roblox)

Weitere Vorschläge werden von Freunden und Kollegen über diverse platformen gegeben, hier können auch vorschläge hinterlassen werden alle sind willkommen.

Momentan sieht das Programm so aus und zukünftig werden Bilder bei veränderungen im Verlauf mit geschickt wenn sie passieren.
<img width="813" height="418" alt="image" src="https://github.com/user-attachments/assets/e1f01392-0f7f-484b-8cbc-16a0d39f4b96" />







## Verlauf des Projekts

### 9.11.2025

Migrations vorbereitungen.

### 8.11.2025

~~WINRATE!~~
~~Für Limbus Company eine Automatisierung die Winrate drückt und dann wieder zurück tabt~~

### 7.11.2025
Ganze RAM/CPU limiter sektion "entfernt" alles wurde auskommentiert und kommt vielleicht später wieder,
Code Einlöse System, gedacht um große mengen von codes nach einander einzulösen, kann rein theoretisch auch für was anderes verwendet werden.

Nochmal ein bisschen die DLL verarbeitung überarbeitet um sicher zu stellen das alle Funktionen funktionieren werden,


<img width="814" height="424" alt="image" src="https://github.com/user-attachments/assets/a9413ae2-1385-4886-a6ea-724a4a9fca94" />

### 6.11.2025

Die ganzen Dll's eingebettet in die .exe da tatsächlich nur native DLL's automatisch eingebaut werden, somit hatte das meiste einfach nicht funktioniert,
Ich wusste dies leider davor nicht es ist mir grade beim testen aufgefallen.

### 5.11.2025

Datei Ent- und Verschlüsselung hinzugefügt, bitte beachte aber das dies nur bei Datein erstellt vom Programm selbst funktioniert, es nutzt ein ähnliches System wie beim Text Speicher,
jedoch wird die Datei mit einem Password geschutzt das nicht vergessen werden sollte, wenn es vergessen wird kannst du nicht an die Datei rann,
ebendso überprüft das Programm nicht ob es das richtige Password ist sondern entschlüsselt die datei einfach und wenn das Password falsch war funktioniert die Datei nicht.

<img width="233" height="279" alt="image" src="https://github.com/user-attachments/assets/cf95248d-6d6a-4364-b8a5-e81ea89ad334" />

### 28.10.2025

Geplannte Updates vom UI ersetzt mit dem Projekt Verlauf,
DPI Stufen "gefixed" die Anwendung wird immer mit 100% Skalierung öffnen was in Unschärfe endet war im moment die einfachste möglichkeit welche überarbeitet wird sobald wirklich nötig.

<img width="815" height="424" alt="image" src="https://github.com/user-attachments/assets/03f553c9-706f-4e6b-8a7e-292095cd0543" />

### 27.10.2025

Möglichkeit das Haupt Fenster mit einem Hintergrund Bild/Video zu versehen hinzugefügt,

Lautstärke einstellung hinzugefügt,
libvlc wird nichtmehr im ordner mit geliefert da es nun verschoben wird aus der exe selbst in den Appdata ordner.

<img width="797" height="203" alt="image" src="https://github.com/user-attachments/assets/b33e5ef8-5b34-4008-a3ca-2dfe89940e40" />

### 22.10.2025

Bennenungen von Fenstern korrigiert,
Option zum Minimieren hinzugefügt,
Cream aus der .exe entfernt.

### 20.10.2025

Leichte UI änderungen,

Roblox Auto-Rejoin überarbeitet damit es auch WIRKLICH drückt wenn das Roblox Fester sichtbar aber nicht im Fokus ist bzw ausgewählt.

### 19.10.2025

Die Einstellungs datei wurde jetzt in den "Appdata" Ordner verlegt um einen Zentralen Ort zu haben,
das selbe gilt für Ordner benötigt für Image recognition, für die Roblox Auto Rejoin Funktion als Beispiel. 

Die Datei die deine Gespeicherten Texte speichert werden lokal verschlüsselt, 
kann nur vom selben Nutzer über die Anwendung entschlüsselt werden.

<img width="366" height="350" alt="image" src="https://github.com/user-attachments/assets/d742280f-c595-4f34-bf71-001a21019743" />

### 18.10.2025

Multi Download für den Youtube Web Downloader hinzugefügt.

<img width="400" height="451" alt="image" src="https://github.com/user-attachments/assets/54e2f412-d9ea-4551-b747-8b535f269292" />

### 17.10.2025

Langes Laden von der Website ist nun kein Problem mehr.

~~Temporär einfach einen cooldown von 30 sekunden für die YT Downloader web integration eingefügt, da ich offensichtlich es nicht hinbekomme richtig die lade phase der website zu tracken.~~

### 15.10.2025

Youtube Downloader hinzugefügt,
Lädt ein einzelnes Video über eine Website herrunter mit Höchst möglicher Qualität voll automatisch und sichtbar,
Playlists funktionieren über die website anscheinend nicht,
eigentlich wollte ich eine Anwendung dafür machen und diese integrieren jedoch sind die Libarys dafür momentan outdated und funktionieren somit nicht,

### 13.10.2025

Text Speicher hinzugefügt, 
Titel (genutzt zum laden) + Inhalt (welcher gespeichert werden soll)

Bennenungsfehler behoben der nach update am selben tag vergessen wurde,
Einstellungen etwas sortiert,

Kleine Ui überarbeitungen,
Ein Paar Einstellungsmöglichkeiten hinzugefügt für die Overlays (Andere Funktionen->Diverse Einstellungen)

### 12.10.2025

(Roblox) Automatisches Rejoinen nach Lag/Internetausfall/AFK kick/ oder meldungen die ähnnlich aussehen.

### 10.10.2025

Eigendes Ordner scanner system gelöscht, 
WinDirStat integriert,
~~Cream teilweise übersetzt und integriert (DLC-Unlocker).~~


### 08.10.2025

~~Liste zum Hellmodus hinzugefügt (konnte dunkel werden aber nicht andersrum)~~
~~Löschen von Ordnern und Dateien in der Liste (TreeView) mit löschen button.~~
~~Fortschrittsbalken zum anzeigen des ungefähren Fortschritts.~~
~~Automatische Formatierung zu B,KB,MB,GB,TB.~~

### 07.10.2025

~~Speicher scan, scannt den angegebenen Ordner und listet den verbrauchten Speicher in MB.~~

### 14.9.2025

Besseres downloaden von updates, wen exe im download order (weil du sie von da warscheinlich verwendest)
Dann erstelle einen ordner und packe sie da rein (denn du kannst keine aktiven anwendungen löschen)
Bessere Fenster bennenung.
Temporäres icon hinzugefügt.


### 13.9.2025

Simples KeyOverlay (Zeigt die letzten gedrückten tasten an)


### 9.9.2025

Farb wähler hinzugefügt für das Ressourcen Overlay. 


### 11.8.2025

Planetside UserOptions.ini editor entfernt,
da dies zu spezifisch war.


Vor Erstellung der Datei hinzugefügt:

Autoklicker,
Ressoucen nutzung,
Ram/CPU limiter.

# Agency Theme

Vorbereitet für Github-Hosting

## Installation

### Webseite "Forken"

- VORHER: Wenn du es noch nicht getan hast: Lege dir ein Github-Konto an und logge dich ein.
		Du musst **kein** Projekt anlegen, wenn du gefragt wirst.
- SCHRITT 1: Rufe das Repository unter der Adresse [https://github.com/invisible-university/agency-website](https://github.com/invisible-university/agency-website) auf und klicke rechts oben auf „Fork“. Das kann eine Weile dauern ...
- GRATULATION: Du hast eine Webseite übernommen. Sie gehört jetzt dir.
- SCHRITT 2: Gib der Webseite einen Namen, indem du auf „Settings“ klickst, den Repository-Namen änderst (z.B. auf meine-webseite) und dann auf „Rename“ klickst.
- ACHTUNG: Schaue dir die URL (Webadresse in der Browser-Zeile) an. Sie besteht aus der Adresse von Github, dann deinem Namen und dann dem Namen des Repositories. 
		Darüber ist dein Projekt für jeden erreichbar.
- SCHRITT 3: Klicke wieder auf „Setting“ und scrolle nach unten bis zum Eintrag „Github Pages“.
  	Dort wähle statt „None“ „master branch /docs folder“ aus und klicke „Save“. Scrolle dann zurück an die gleiche Stelle. Dort steht jetzt „Your site is ready to be published at“ und eine Webadresse. Lade die Webseite neu, bis dort „Your site is published at https://[dein name].github.io/meine-webseite/“ erscheint.
- GRATULATION (2): Du hast jetzt eine eigene Webseite, die frei im Internet erreichbar ist. Klicke auf den Link.

### Text auf der Startseite ändern

- VORHER: Rufe die Startseite deines Repositories auf. (Wenn du schon in deinem Repository bist, muss du dafür nur oben links unter dem Suchfeld auf den Repository-Namen klicken). Du siehst eine Liste mit Dateien. Einen „docs“-Ordner, die "README.md"-Datei, die du gerade liest und eine ".gitignore-Datei, die wir jetzt nicht brauchen."
- SCHRITT 1: Klicke auf den „docs“-Ordner, um die Dateien im Ordner anzuzeigen.
- SCHRITT 2: Klicke auf die Datei „index.html“ und dann auf das Edit-Symbol rechts oben (ein kleiner Stift).
- Nicht erschrecken! Das sieht ziemlich unübersichtlich aus und wir werden demnächst eine schönere Methode zum Ändern von Dateien kennenlernen.
- SCHRITT 3: Suche nach „Welcome“ (klicke in den Edit-Bereich und drücke STRG-f ). Du findest eine Zeile, die etwa so aussieht:

```
<div class="intro-lead-in">Welcome To Our Studio!</div>`
```
- SCHRITT 4: Sei vorsichtig, ändern nur das „Welcome To Our Studio!“ nicht die übrigen Bereiche der Zeile. Du kannst auch gefahrlos in der Zeile darunter das „It's Nice To Meet You“ und darunter das „Tell Me More“ ändern. Dann scrolle die Webseite nach unten schreibe unter „Commit Changes“: „Titel und Untertitel geändert.“. Dann klicke auf „Commit changes“.
- GRATULATION (3): Du hast deine eigene Webseite zum ersten Mal geändert. Warte einige Sekunden und rufe sie dann auf (den Link findest du unter Settings).
- Auf diese Weise kannst du alle reinen Texte auf der Seite ändern. Du musst nur herausfinden, welches die reinen Texte sind. 

### Das Hintergrund-Bild auf der Startseite ändern
- SCHRITTE 1 Suche ein Bild, am besten eines, das etwa 1600 x 1000 pixel groß ist. Zum Beispiel kannst du dafür die Google-Bildersuche verwenden und dort bei Settings/Nutzungsrechte „frei zu nutzen oder weiterzugeben“ auswählen. Ansonsten erschwischt du vielleicht ein Bild mit Rechten. Du kannst auch eines von folgenden Bildern nehmen (rechte Maustaste / Bild speichern):

	[http://c2064.in-berlin.de/kpu/img/aepfel.jpg](http://c2064.in-berlin.de/kpu/img/aepfel.jpg)  
	[http://c2064.in-berlin.de/kpu/img/aepfel.jpg](http://c2064.in-berlin.de/kpu/img/aepfel.jpg)  
	[http://c2064.in-berlin.de/kpu/img/blume.jpg](http://c2064.in-berlin.de/kpu/img/blume.jpg)  
	[http://c2064.in-berlin.de/kpu/img/dahab1.jpg](http://c2064.in-berlin.de/kpu/img/dahab1.jpg)  
	[http://c2064.in-berlin.de/kpu/img/dahab2.jpg](http://c2064.in-berlin.de/kpu/img/dahab2.jpg)  
	[http://c2064.in-berlin.de/kpu/img/farben.jpg](http://c2064.in-berlin.de/kpu/img/farben.jpg)  
	[http://c2064.in-berlin.de/kpu/img/see.jpg](http://c2064.in-berlin.de/kpu/img/see.jpg)  
	[http://c2064.in-berlin.de/kpu/img/strand.jpg](http://c2064.in-berlin.de/kpu/img/strand.jpg)  
	[http://c2064.in-berlin.de/kpu/img/teich.jpg](http://c2064.in-berlin.de/kpu/img/teich.jpg)  
	[http://c2064.in-berlin.de/kpu/img/wald.jpg](http://c2064.in-berlin.de/kpu/img/wald.jpg)  

- SCHRITT 2: Benenne das Bild um in „header-bg.jpg“
- SCHRITT 3: In GitHub gehe von der Startseite deines Repositories zum /docs/img Ordner
- SCHRITT 4: Klicke auf „Upload files“ und lade das Bild hoch.
- SCHRITT 5: Schreibe eine „Commit Message“, z.B. „Neues Hintergrundbild auf Startseite“ und klicke auf „Commit Changes“
- FERTIG! Nach ein paar Sekunden kannst du die Webseite aufrufen und hast einen neuen Hintergrund. Auf auf dem Smartphone ;-)


## Bearbeiten der Webseite auf dem eigenen Rechner

Das Verändern der Webseite ist unter GitHub etwas umständlich. Um das zu vereinfachen laden wir die Webseite jetzt herunter.

### Webseite auf dem eigenen Rechner speichern

Rufe dein Repository in GitHub auf. In der Eingabezeile des Browsers findest du eine Webadresse. Das ist die Webadresse deines Repositories. Kopiere sie.

Rufe die Kommando-Zeile auf. Wechsle zum Schreibtisch-Verzeichnis.

```
cd Schreibtisch
```

Lade dein Repository hierher

```
git clone [deine Repository-Adresse]
```

### Die Webseite verändern

Rufe den Sublime-Editor mit dem docs-Verzeichnis auf. In diesem Verzeichnis ist deine gesamte Webseite enthalten.
Dann öffne die Seite im Firefox.

```
sublime_text docs &
firefox docs/index.html &
```

Mit dem Editor kannst du die Webseite ändern. Öffne dazu zunächst nur die Datei "index.html".
Mit Firefox kannst du die Webseite anschauen. Firefox holt sich die Seite jetzt nicht aus dem Internet, sondern "lokal" von deiner Festplatte.
Das heißt, du kannst ändern, was du willst, zunächst hat das keine Auswirkungen auf die Seite im Internet.

### Die Webseite veröffentlichen

Um eine Webseite mit Git zu veröffentlichen, muss man drei Dinge tun:
- Man muss Git sagen, welche von den geänderten Dateien man hochladen will (meistens alle)
- Dann erzeugt man eine neue Version und gibt ihr eine Überschrift
- Als drittes "schiebt" man die Version in Internet hoch

Die drei Befehle sehen so aus:
- git add .
- git commit -m "Neue Version"
- git push

Der Punkt hinter add bedeuted: alle geänderten Dateien. Aber du musst die Befehle nicht einzeln eingeben.

Der Befehl "publish" kombiniert diese drei Befehle. Es reicht also, einfach

```
./publish "Neue Version"
```

zu schreiben. Nach einigen Sekunden, manchmal einigen Minuten, ist die Webseite im Internet verfügbar.


## Glossar

- B

### Browser / Internet-Browser

Zugangssoftware für WWW-Seiten, wie Google Chrome, Firefox, Edge, Opera


- F

### Freie Software

Freie Software ist Open Source-Software, die man sich frei kopieren und dann verändern kann.

- G

### Github

Github ist der zentrale Ort für Open-Source-Software-Projekte, quasi ein Facebook für Programmierer.

- H

### Hosting

Hosting ist das Unterbringen von Webseiten auf Webservern, so dass sie vom Internet aus zugänglich sind. Auch Google und Apple "hosten" ihre Webseiten.

- O

### OpenSource

Offene Software ist Software, bei der der Quellcode offen sichtbar ist. Man kann quasi "nachlesen", was das Programm macht. Freie Software (Free Software) erlaubt darüber hinaus noch, das freie Kopieren und Weiterbearbeiteten des Quellcodes.

### Repository

Ein Projekt oder Programm bei Github wird Repository genannt, ein Aufbewahrungsort für den Quelltext des Projekts oder Programms. 

### URL

Uniform Resource Locator, eine Web-Adresse. Beginnt mit http:// oder https://

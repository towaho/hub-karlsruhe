# Herstellung der Gestelle - vom Druck bis zur Anlieferung
Vielen Dank, dass ihr uns mit dem Druck von Gestellen unterstützen wollt. Ihr findet hier alle wichtigen Informationen zum Ablauf im Hub Karlsruhe.
Alle weiteren Informationen zur Orga sowie ein FAQ findet ihr in unserem Doc [Organisation HUB Karlsruhe](https://docs.google.com/spreadsheets/d/1wsZU-VTYREOStcnClETrNQFkIYqHXFwlxU8IcKh8BXk)

Die Koordinierung für den Großraum Karlsruhe erfolg im Kanal [#hub-karlsruhe](https://app.slack.com/client/T010HM3B6BS/C010VSH5RD5). Dort helfen wir euch gerne bei Fragen und Problemen und ihr bekommt Infos zum aktuellen Stand.

In Karlsruhe wird aktuell ausschließlich das Modell Prusa rc3 bzw. die dazu lochkompatiblen Versionen V10 und V18 gedruckt.
Dieses Modell wird am meisten gewünscht und ist vor allem mit anderen Hubs kompatibel. Wir möchten euch daher bitten, nur dieses zu drucken und anzuliefern. Achtet bitte darauf, dass ihr **NICHT** aus versehen die slim Variante druckt. Die STL-Dateien sowie Hinweise zum Drucken findet ihr weiter unten.

Der Zusammenbau erfolgt in den beiden FabLabs. Ihr müsst also keine fertigen Schilde anliefern, sondern nur die gedruckten Gestelle und Stabis. Falls ihr passende Folien oder Loch-Gummiband beschaffen könnt, meldet euch aber gerne im slack Kanal bei uns oder direkt beim [Orga-Team](https://docs.google.com/spreadsheets/d/1wsZU-VTYREOStcnClETrNQFkIYqHXFwlxU8IcKh8BXk/edit#gid=139873882) per direct message.

![Faceshield][shield]

## Eintrag als Drucker
Tragt euch bitte im [doc in der Tabelle "Kapazitäten Gestelle"](https://docs.google.com/spreadsheets/d/1wsZU-VTYREOStcnClETrNQFkIYqHXFwlxU8IcKh8BXk/edit#gid=0) ein und gebt bitte eure Slack ID mit an. An eure Slack-ID kommt ihr wie folgt:
* In Slack in deinem Fenster oben Links auf das Feld "MakerVSVirus" klicken
* auf Profil Anzeigen / View Profile klicken
* Der Link wird dann im Browser in der URL-Leiste angezeigt

Die beiden geliefert Spalten sind schreibgeschützt und werden von den beiden Hubs verwaltet.

Spalte | Hinweise
------------ | -------------
Anzahl gedruckt | Hier bitte die Summe aller bereits gedruckten Gestelle eintragen (inklusive der bereits ans HUB gelieferten)
Anzahl in Arbeit | Hier könnt ihr eintragen, wie viele Gestelle ihr zur Zeit gleichzeitig im Druck habt. Wenn ihr gerade nicht drucken könnt, bitte auf 0 ändern.
mögliche Anzahl pro 24h | Tragt hier bitte nur ganze Zahlen ein und nicht "5-10" oder ähnliches.

## Material
PETG sowie PLA gehen. Bevorzugt wird PETG, da besser reinigbar. Die Farbe ist grundsätzlich egal. Sie sollte natürlich nicht ganz so peinlich sein. 

## STL Dateien
### Gestell
Unsere Empfehlung: [Covid-19 Shield v18.stl von Yannic Schröder](https://github.com/yschroeder/face-shield/raw/master/stl/Covid-19%20Shield%20v18.stl)

Wenn ihr Probleme mit der Haftung auf dem Druckbett habt, könnt ihr auch die [Version mit Lily Pads](https://github.com/yschroeder/face-shield/raw/master/stl/Covid-19%20Shield%20v18%20Lily.stl) nutzen. Das erhöht jedoch den Aufwand bei der Nachbearbeitung. Bei einem Drucker mit beheiztem Druckbett, richtig eingestellter Temperatur und korrekt justierter Z-Achse, solltet ihr aber auch ohne Pads keine Haftungsprobleme bekommen.

Für den Prusa i3 mit der Standard 0.4er nozzle findet ihr [hier eine fertige Projektdatei](https://github.com/towaho/hub-karlsruhe/raw/master/stl/Covid-19_Shield_v18_twin.3mf) mit zwei Oberteilen. Der [PrusaSlicer 2.2](https://www.prusa3d.de/prusaslicer/) unterstützt auch out of the box den Ender 3.

#### Alternativen (Bitte NICHT die slim Variante drucken)
* [Prusa rc3 ohne Text](https://media.prusaprinters.org/media/prints/25857/stls/270587_b59f75d0-4b8a-4999-8417-e5e75874ff98/covid19_headband_rc3.stl)
* [Covid-19 Shield v10](https://github.com/yschroeder/face-shield/raw/master/stl/Covid-19%20Shield%20v10.stl)


Wenn euer Druckbett für die Gestelle zu klein ist, dann wäre es klasse, wenn ihr uns mit dem Druck der Stabis unterstützt. Es gibt zwar von Prusa auch eine Vorlage für kleinere Druckbette, diese müssen aber zusammen geklebt werden. Wir haben jedoch das Feedback erhalten, dass bei diesen der Tragekomfort nicht so gut ist. Daher diese Version bitte nicht mehr drucken.

### Stabi (Unterteil)
Bei den aktuell verfügbaren Folien wird im Normalfall kein Stabi benötigt. Wir geben diese daher zur Zeit nur auf Nachfrage aus. Sie werden aber von uns angenommen. Unsere Empfehlung: zu 50 bis max 75 Prozent mit drucken.

Auch hier gibt es eine Version von Yannic, die sich mit den gleichen Einstellungen wie die V18 in wenigen Minuten drucken lässt. Diese lässt sich sehr leicht befestigen und passt für alle Folienstärken

* [Bottom Reinforcement light v10.stl](https://github.com/yschroeder/face-shield/raw/master/stl/Bottom%20Reinforcement%20light%20v10.stl)

## Druck
Mit den Standardeinstellungen beträgt die Druckdauer eines Gestells in PETG ca. 2:30h. Die V18 ist von Yannic für den schnellen Druck optimiert worden. Bevor ihr diese nutzt, lest euch bitte vorher die [Doku von Yannic](https://github.com/yschroeder/face-shield) durch und stellt eueren Drucker entsprechend ein. Mit Yannics Einstellungen könnt ihr ein Oberteil mit einem prusa i3 in PETG in ca. **1:18h** drucken. Zwei Gestelle gleichzeitig in 2:32h. Mit PLA geht es sogar noch schneller (1:38h für zwei Gestelle).

Beachtet bitte auch die Hinweise unter "Advanced Parameter Tuning" sowie Holes:

**Extrusion width / Extrusionsbreite**
* External perimeters / Außenkontouren: 1.00mm
* solid infill / Massives Infill: 0.55mm
* top solid infill / oberes massives Infill: 0.55mm

Hier zum Vergleich eine Detailaufnahme mit 0.87mm. Es sind an den T-Kreuzungen deutlich kleinere Löcher zu erkennen:
![0.87mm external perimeters][0.87mmperimeters]

Mit 1.00mm sind zwar noch kleine Rillen vorhanden, aber die Löcher sind zu:
![1.00mm external perimeters][1mmperimeters]

Alternativ könnt ihr auch wie von Yannic beschrieben den "Extrusion multiplier" erhöhen.

### Hinweise

Das Drucken der Gestelle ist kein Wettbewerb wer am meisten druckt. Wenn ihr nicht die von Yannic empfohlenen Einstellungen nutzt, dann am besten mit 3 Perimeter (Wände) drucken. Vor dem ersten Druck sollte auch in der Vorschau überprüft werden, ob keine Lücken entstehen.

Aktuell raten wir davon ab, die Gestelle übereinander als Stacks zu drucken. Die bisherigen Erfahrungen haben gezeigt, dass gut 80% der Stacks nicht verwendbar sind (kleben zu stark aneinander, Boden schlecht verklebt, Probleme beim Desinfizieren).

## Qualitätskontrolle
Die hier beschriebenen Tests gelten nur für die V18. Die anderen Modelle sind nicht so flexibel und könnten brechen obwohl sie für den Bau der Schilde nutzbar sind.

Viel wichtiger als die Druckzeit ist, dass die Qualität am Schluss stimmt. Prüft bitte insbesondere beim Druck der V18 mit nur zwei Perimeter, ob diese sauber miteinander kleben. 

So sollte es **nicht** aussehen (Delamination)
![Delamination][delamination]


Führt am besten nach eurem ersten Druck den [hier beschriebenen Test](https://github.com/yschroeder/face-shield/blob/master/quality_control.md) durch. Meldet euch bitte im #hub-karlsruhe wenn ihr Qualitätsprobleme habt. **Vor der Abgabe/Abholung bitte alle Teile entsprechend prüfen.**

## Abgabe/Abholung
Abgeben könnt die fertig gedruckten Teile in einem der beiden FabLabs:

**FabLab Karlsruhe e.V.**
```
Alter Schlachthof 13a (gegenüber Substage / Alte Hackerei)
76131 Karlsruhe
Tel.:  +49 721 60906012	
```

**FabLab Bruchsal e.V. i.G.**
```
Werner-von-Siemens-Straße 2-6
Gebäude 5137c
76646 Bruchsal
Tel.: +49 151 25351131
```

Im Google Docs gibt es eine Ampel, ob das Lab besetzt ist. Fragt bitte vorher zur Sicherheit noch einmal telefonisch nach, damit ihr euch nicht umsonst auf den Weg macht.

Für alle die keine Möglichkeit haben, die Teile in Karlsruhe oder Bruchsal abzugeben, gibt auch ca. 2 mal die Woche eine Abholtour, bei der ihr eure Teile kontaktlos abholen lassen könnt. 

Bitte schnürt die Gestelle in 5er Paketen mit Schnur oder Draht zusammen und hängt einen Anhänger mit slack-ID/e-Mail Adresse an. So können wir euch Feedback geben, wenn wir beim Zusammenbau auf Probleme stossen. Hier gibt es Vorlagen zum Lochen oder für Klebelabel:

* [Label für Libreoffice](https://github.com/towaho/hub-karlsruhe/raw/master/doc/label.odt)
* [Label für MS Office](https://github.com/towaho/hub-karlsruhe/raw/master/doc/label.docx)

![Fertig zur Abgabe][package]


Das Desinfizieren der Teile ist nicht notwendig. Die Empfänger werden die Schilde sowieso desinfizieren und Desinfektionsmittel ist zur Zeit ebenfalls knapp.

Falls wir die gelieferten Teile nicht im Sheet eingetragen haben, meldet euch bitte noch einmal bei uns.

[shield]: images/shield.jpg "Faceshield"
[1mmperimeters]: images/1.00.jpg "1.00mm external perimeters"
[0.87mmperimeters]: images/0.87.jpg "0.87mm external perimeters"
[delamination]: images/delamination.jpg "Delamination"
[package]: images/package.jpg "Fertig zur Abgabe"


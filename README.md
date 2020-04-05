# Herstellung der 3d Gestelle - vom Druck bis zur Anlieferung
Vielen Dank, dass ihr uns mit dem Druck von Gestellen unterstützen wollt. Ihr findet hier alle wichtigen Informationen zum Ablauf im Hub Karlsruhe.
Alle weiteren Informationen zur Orga sowie ein FAQ findet ihr in unserem Doc [Organisation HUB Karlsruhe](https://docs.google.com/spreadsheets/d/1wsZU-VTYREOStcnClETrNQFkIYqHXFwlxU8IcKh8BXk)

Die Koordinierung für den Großraum Karlsruhe erfolg im Kanal [#hub-karlsruhe](https://app.slack.com/client/T010HM3B6BS/C010VSH5RD5). Dort helfen wir euch gerne bei Fragen und Problemen und ihr bekommt Infos zum aktuellen Stand.

In Karlsruhe wird aktuell ausschließlich das Modell Prusa rc3 bzw. die dazu lochkompatiblen Versionen V10 und V18 gedruckt.
Dieses Modell wird am meisten gewünscht und ist vor allem mit anderen Hubs kompatibel. Wir möchten euch daher bitten, nur dieses zu drucken und anzuliefern. Achtet bitte darauf, dass ihr **NICHT** aus versehen die slim Variante druckt. Die STL-Dateien sowie Hinweise zum Drucken findet ihr weiter unten.

Der Zusammenbau erfolgt in den beiden FabLabs. Ihr müsst also keine fertigen Schilde anliefern, sondern nur die gedruckten Gestelle. Falls ihr passende Folien oder Loch-Gummiband beschaffen könnt, meldet euch aber gerne im slack Kanal bei uns.

## Eintrag als Drucker
Tragt euch bitte im [doc in der Tabelle "Kapazitäten Gestelle"](https://docs.google.com/spreadsheets/d/1wsZU-VTYREOStcnClETrNQFkIYqHXFwlxU8IcKh8BXk/edit#gid=0) ein und gebt bitte eure Slack ID mit an. Die beiden geliefert Spalten sind schreibgeschützt und werden von den beiden Hubs verwaltet.

Spalte | Hinweise
------------ | -------------
Anzahl gedruckt | Hier bitte die Summe alle bereits gedruckten Gestelle eintragen (inklusive der bereits ans HUB gelieferten)
Anzahl in Arbeit | Hier könnt ihr eintragen, wie viele Gestelle ihr zur Zeit gleichzeitig im Druck habt. Wenn ihr gerade nicht drucken könnt, bitte auf 0 ändern.
mögliche Anzahl pro 24h | Tragt hier bitte nur ganze Zahlen ein und nicht "5-10" oder ähnliches.

## Material
PETG sowie PLA gehen. Bevorzugt wird PETG, da besser reinigbar.

## STL Dateien
### Gestell
Unsere Empfehlung: [Covid-19 Shield v18.stl von Yannic Schröder](https://github.com/yschroeder/face-shield/raw/master/stl/Covid-19%20Shield%20v18.stl)

Wenn ihr Probleme mit der Haftung auf dem Druckbett habt, könnt ihr auch die [https://github.com/yschroeder/face-shield/raw/master/stl/Covid-19%20Shield%20v18%20Lily.stl](Version mit Lil Pads) nutzen. Das erhöht jedoch den Aufwand bei der Nachbearbeitung. Bei einem Drucker mit beheiztem Druckbett, richtig eingestellter Temperatur und korrekt justierter Z-Achse, solltet ihr aber auch ohne Pads keine Haftungsprobleme bekommen.

Für den Prusa i3 mit der Standard 0.4er nozzle findet ihr hier eine fertige Projektdatei mit zwei Oberteilen.

#### Alternativen
* [Prusa rc3 ohne Text](https://media.prusaprinters.org/media/prints/25857/stls/270587_b59f75d0-4b8a-4999-8417-e5e75874ff98/covid19_headband_rc3.stl)
* [Covid-19 Shield v10](https://github.com/yschroeder/face-shield/raw/master/stl/Covid-19%20Shield%20v10.stl)

**Bitte nicht die Slim Variante drucken**

### Stabi (Unterteil)
Bei den aktuell verfügbaren Folien wird im Normalfall kein Stabi benötigt. Wir geben diese daher zur Zeit nur auf Nachfrage aus. Sie werden aber von uns angenommen. Unsere Empfehlung: zu 50 bis max 75 Prozent mit drucken.

Auch hier gibt es eine Version von Yannic, die sich mit den gleichen Einstellungen wie die V18 in wenigen Minuten drucken lässt. Diese lässt sich sehr leicht befestigen und passt für alle Folienstärken

* [Bottom Reinforcement light v10.stl](https://github.com/yschroeder/face-shield/raw/master/stl/Bottom%20Reinforcement%20light%20v10.stl)

## Druck
Mit den Standardeinstellungen beträgt die Druckdauer eines Gestells ca. 2:30h. Die V18 ist von Yannic für den schnellen Druck optimiert worden. Bevor ihr diese nutzt, lest euch bitte vorher die [Doku von Yannic](https://github.com/yschroeder/face-shield) durch und stellt eueren Drucker entsprechend ein. Mit Yannics Einstellungen könnt ihr ein Oberteil mit einem prusa i3 in PETG in ca. 1:18h drucken. Zwei Schilde gleichzeitig in 2:32h. 

Beachtet bitte auch die Hinweise unter "Advanced Parameter Tuning" sowie Holes:
* External perimeters: 1.00mm
* solid infill: 0.55mm
* top solid infill: 0.55mm

Eine fertige Projektdatei für den PrusaSlicer mit passenden Einstellungen für den Prusa i3 findet ihr hier.

## Qualitätskontrolle
Die hier beschriebenen Tests gelten nur für die V18

Viel wichtiger als die Druckzeit ist, dass die Qualität am Schluss stimmt. Prüft bitte insbesondere beim Druck der V18 mit nur zwei Perimeter, ob diese sauber miteinander kleben.
Führt am besten nach eurem ersten Druck den hier beschriebenen Test durch. Meldet euch bitte im #hub-karlsruhe wenn ihr Qualitätsprobleme habt. Vor der Abgabe/Abholung bitte alle Teile entsprechend prüfen

## Abgabe/Abholung
Abgeben kann man die fertig gedruckten Teile in einem der beiden FabLabs. Meistens wird hier im channel #hub-karlsruhe geschrieben, wenn jemand vor Ort ist. Im Google Docs gibt es aber auch eine Ampel, ob das Lab besetzt ist. Am besten stimmt ihr euch vorher ab, damit ihr euch nicht umsonst auf den Weg macht.

Für alle die keine Möglichkeit haben, die Teile in Karlsruhe oder Bruchsal abzugeben, gibt auch ca. 2 mal die Woche eine Abholtour, bei der ihr eure Teile kontaktlos abholen lassen könnt. 

Bitte schnürt die Gestelle in 5er Paketen mit Schnur oder Draht zusammen und hängt einen Anhänger mit slack-ID/e-Mail Adresse an. So können wir euch Feedback geben, wenn wir beim Zusammenbau auf Probleme stossen.

Das Desinfizieren der Teile ist nicht notwendig. Die Empfänger werden die Schilde sowieso desinfizieren und Desinfektionsmittel ist zur Zeit ebenfalls knapp.

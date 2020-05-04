# Herstellung Ohrenentlastung
Hier findet ihr alle wichtigen Informationen zum Druck der Ohrenentlaster. Es gibt im Netz sehr viele Versionen und Varianten. Wir haben uns in Karlsruhe für die light Version von Yannic entschieden. Wir drucken bis auf weiteres erst einmal nur die Lang-Version.

![Ohrenentlastung][strap]

## Material
Bitte nur PET,PETG oder ABS verwenden. Wenn ihr nur PLA drucken könnt, dann bitte vorab mit uns abklären. Farbe ist auch hier grundsätzlich egal. Häufig gewünscht werden helle Farben (weiß, gelb, grün). Grundsätzlich könnt ihr alle Farben drucken, die eurer Meinung nach Ärzte und Pfleger gerne tragen.

## STL Dateien
### Gestell
Long Version [Surgical_Mask_Strap_light_long_v5.stl von Yannic Schröder](https://github.com/towaho/hub-karlsruhe/raw/master/stl/Surgical_Mask_Strap_light_long_v5.stl)

Für den Prusa i3 mit der Standard 0.4er nozzle findet ihr [hier eine fertige Projektdatei](https://github.com/towaho/hub-karlsruhe/raw/master/stl/surgical-mask-strap-light_long-table-v5.3mf) mit 7 Stück auf einem Druckbett.

## Druck
Mit den Einstellungen aus der Projektdatei könnt ihr 7 Stück in ca. 24 (PETG) - 30 (PET) Minuten drucken. Für den Prusa i3 mk3 haben wir eine fertige Projektdatei. Für andere Drucker findet ihr [hier die Hinweise von Yannic](https://www.prusaprinters.org/prints/30406-surgical-mask-strap-light). **HINWEIS:** In dieser Projektdatei ist die Standardversion enthalten. Wir drucken aktuell die Long Version 5. 

Wenn ihr [unsere Projektdatei](https://github.com/towaho/hub-karlsruhe/raw/master/stl/surgical-mask-strap-light_long-table-v5.3mf) nutzt, sind die von Yannic beschriebenen Einstellungen schon alle mit drin. Um die angebenenen Druckzeiten zu erreichen, müsst ihr aber auch noch wie von Yannic beschrieben die Werte für "Max volumetric speed" unter "Filament Settings" -> Advanced -> "Print speed override" anpassen. Das BASF PET kann man beim Prusa i3 mk3 auf ca. 10-12 mm³/s setzen. PETG könnt ihr mit 15-17 mm³/s drucken. Wenn ihr Lücken im Druck habt, dann müsst ihr den Wert verringern. 

### Empfehlungen für das BASF PET Fillament
Beachtet bitte, dass es sich hierbei um PET und nicht um PETG handelt. Der Schmelzpunkt ist niedriger und somit auch die Drucktemperatur. Wenn ihr ein PEI beschichtetes Druckbett nutzt, dann solltet ihr beim ersten Druck die z-Achse 0.1mm höher (weiter Weg vom Druckbett) einstellen und euch in 0.01er Schritten an 0 annähern. ZU NAH AM BETT = RISIKO dass die Beschichtung beim Ablösen am Druckteil statt am Druckbett klebt! Löst die Teile am besten, bevor das Druckbett vollständig abgekühlt ist (sie müssen aber kurz abkühlen, damit sie sich beim Ablösen nicht verziehen). Im Gegensatz zu den Gestellen, haften diese Teile aufgrund der größeren Fläche deutlich besser. Ihr könnt somit in den meisten Fällen die Temperatur des Druckbetts reduzieren. 

Als Ausgangswerte für eigene Tests eignen sich:
* Druckbett ca. 60°C (wenn die Haftung zu stark ist, senkt die Temperatur ein wenig; Prusa i3 mk3 druckt mit powded bed bei 55°C wunderbar)
* Nozzle: 230°C 
* Lüfter: min 30%, max 50%, durchgängig an, bis auf die ersten 3 Schichten
* Geschwindigkeit: max 200mm/s (wird durch Max volumetric speed reduziert)

## Qualitätskontrolle
Viel wichtiger als die Druckzeit ist, dass die Qualität stimmt. Reduziert im Zweifelsfall lieber die Geschwindigkeit. Ausschus bitte separat sammeln und als Ausschuss im FabLab abgeben. 

Hier seht ihr, wie die fertigen Teile aussehen sollen:
![So sollten die Teile aussehen][strap_ok]

Prüft bitte, bei jeder Charge, ob sich die Teile gut biegen lassen:
![Qualitätstest1][quali1]
![Qualitätstest2][quali2] 
![Qualitätstest3][quali2] 


Hier seht ihr ein paar typische Probleme und Hinweise, was zu tun ist:

**Druck mit Infill**
Wenn eure Ösen keine Löcher haben, habt ihr mit Infill gedruckt. Das erhöht die Druckzeit und ist meist nicht verwendbar. Hier verfangen sich leicht die Haare:
![mit Infill gedruckt][strap_nok]

**Volumenstrom zu hoch**
Wenn ihr solche Unterbrechungen im Druck habt, schafft der Drucker den Volumenstrom nicht. Ihr müsst "Max volumetric speed" reduzieren.
![zu hoher Volumenstrom][strap_nok2]

Wenn ihr Probleme mit dem Druck habt, meldet euch bitte im channel und schickt bitte ein Foto des Drucks mit.

**Wenn ihr auch mit Unterstützung und Nachjustierung die hier beschriebene Qualität mit eurem Drucker nicht erreichen könnt, dann macht es leider wenig Sinn, die Teile weiter zu drucken.**




**Entfernt bitte stringing (auch dünne Fäden) vor der Abgabe** 

## Abgabe/Abholung
**Bündelt bitte immer 10 Teile mit Kabelbinder oder Draht und packt sie am besten in einen Gefriebeuten. Bitte nicht lose abgeben.**

Wir haben in der Orga Tabelle einen Tab für die Ohrenentlastung angelegt. Tragt eure Drucke bitte dort genau so ein, wie bisher bei den Gestellen. Abgeben könnt die fertig gedruckten Teile in einem der beiden FabLabs:

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


Damit wir euch bei Problemen direkt ansprechen können, bitte folgenden Infos dazu legen:
* Name
* Slack ID
* Material
* Druckdatum/Zeitraum


Falls wir die gelieferten Teile nicht im Sheet eingetragen haben, meldet euch bitte noch einmal bei uns.

[strap]: images/strap.jpg "Ohrenentlastung"
[strap_ok]: images/strap_ok.jpg "Ohrenentlastung ok"
[strap_nok]: images/strap_nok.jpg "Ohrenentlastung Infill"
[strap_nok2]: images/strap_nok2.jpg "Ohrenentlastung Volumenstrom"
[quali1]: https://media.prusaprinters.org/thumbs/cover/640x480/media/prints/30406/images/302146_9f2713b5-90f6-4e76-930d-09c3edcbd2a6/img_7446.jpg "Qualitätstest1"
[quali2]: https://media.prusaprinters.org/thumbs/cover/640x480/media/prints/30406/images/302147_2a2984e1-f2fe-46d2-af92-ccdb00599e71/img_7440.jpg "Qualitätstest2"
[quali2]: https://media.prusaprinters.org/thumbs/cover/640x480/media/prints/30406/images/302148_9b7cb500-3687-43e3-9823-841517991fbf/img_7447.jpg "Qualitätstest3"


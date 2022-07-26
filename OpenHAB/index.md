# OpenHAB Corner

### [zurück zum Index](../index.md)

## Wie alles begann
In diesem Blog möchte ich meine Erfahrungen und Projekte vorstellen, die ich in den vergangenen Jahren gesammelt habe.
Angefangen hat alles mit der Idee , doch einige Funktionen im Haus zu automatisieren.
Der Klassiker ist hierbei natürlich der Betrieb der Jalousien.
Nachdem dann die Jalousien funktionierten, kamen mit der Zeit immer mehr Sensoren dazu, zB Licht, Türsensoren usw.

## Die Smarthome Zentrale
Für all diese Sensoren bedarf es natürlich irgendwann einer Smarthome Zentrale.
Da ich möglichst viel Freiheiten bei der Gestaltung und bei den Steuerungselementen möchte,
habe ich mich für das frei verfügbare openhab Framework entschieden. 
[OpenHAB](https://www.openhab.org/)

## Der Smarthome „Server“
Da der Bedarf an Rechenpower bei einem Smarthome überschaubar ist, braucht es keinen vollständigen PC im Dauerbetrieb,
sondern diese Arbeit kann relativ günstig zB ein raspberry erledigen. Openhab ist ein sehr mächtiges Framework,
das eine Vielzahl von Kommunikationsprotokollen unterstützt und eine umfangreiche Bibliothek von Adaptern für die verschiedenen Sensorenhersteller
mitliefert,
bzw kontinuierlich weiterentwickelt wird.

Meine Auswahl orientierte sich dabei vorallem an dem unterstützten Kommunikationsprotokoll - zwave.

### [LED Lichterkette mit Arduino ESP8266 und OpenHAB steuern](../LEDstripe/LED-stripe.md)

### [Halloween LED-Ring mit Arduino ESP8266 und OpenHAB steuern](../projects/Halloween/Halloween.md)

### [ESP8266 Schaltsteckdose vs FritzDECT!200](../projects/Tasmota/Tasmota.md)

### [IR Lesekopf für Stromzähler am ESP8266 mit Tasmota](../projects/ESP-Stromzaehler/esp-volkszaehler.md)

### [RaspberryPi als Überwachungskamera](../projects/Aussenkamera/Aussenkamera.md)



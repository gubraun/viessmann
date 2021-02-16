# Codieradressen
Adresse (letzte Spalte) ist die Adresse über die der Datenpunkt mit vcontrol ansprechbar ist.

Quelle: [Serviceanleitung Vitodens 200-W, Typ WB2C, 8/2011](https://www.viessmann.com/vires/product_documents/5604579VSA00001_1.PDF)

* [Allgemein/Gruppe "1"](#allgemeingruppe-1)
* [Kessel/Gruppe "2"](#kesselgruppe-2)
* [Warmwasser/Gruppe "3"](#warmwassergruppe-3)
* [Solar/Gruppe "4"](#solargruppe-4)
* [Heizkreis 1, Heizkreis 2, Heizkreis 3/Gruppe „5“](#heizkreis-1-heizkreis-2-heizkreis-3gruppe-5)


## Allgemein/Gruppe "1"
||Adresse|Werkseinst.|Aktueller Wert|Adresse*|
|---|---|---|---|---|
|Anlagenschema|`00`|`1`|`2`|`0x7700`|
|Zugang Codieradressen Verbrennungsregelung|`11`|`!=9`|`0`|||
|Außentemp.-Sensor vorhanden|`25`|`0`||||
||`32`|`0`|`0`|||
||`33`|`1`||||
||`34`|`0`||||
||`35`|`0`|`0`|||
||`36`|`0`||||
||`3A`|`0`||||
||`3b`|`0`||||
||`3C`|`0`||||
||`3d`|`5`||||
||`3E`|`0`|`0`|||
||`3F`|`0`|`0`|||
|Funktion interne Umwälzpumpe|`51`|`0`||||
|Einstellung interne Umwälzpumpe|`52`|`0`|`0`|||
||`53`|`1`|`1`|||
|Solaranlage vorhanden|`54`|`0`|`0`|||
||`6E`|`50`|`50`|||
||`76`|`0`|`0`|||
|Teilnehmer-Nr.|`77`|`1`||||
||`79`|`1`||||
||`7b`|`1`||||
|Einfamilienhaus/Mehrfamilienhaus|`7F`|`1`|`1`|||
||`80`|`6`|`6`|||
|Automatische Sommer-/Winterzeitumstellung|`81`|`1`|`1`|||
|Gasart (Erd-/Flüssiggas)|`82`|`0`||||
||`86`|`0`||||
||`87`|`0`||||
||`88`|`0`|`0`|||
||`8A`|`175`|`175`|||
|Bedienung sperren|`8F`|`0`|`0`|||
||`90`|`128`|`128`|||
||`94`|`0`|`0`|||
|Vitocom 100 vorhanden?|`95`|`0`|`0`|||
||`97`|`0`||||
||`98`|`1`||||
||`99`|`0`|`0`|||
||`9A`|`0`|`0`|||
|Vorlauftemperatur Sollwert bei externer Anforderung|`9b`|`70`||||
||`9C`|`20`||||
||`9F`|`8`||||

## Kessel/Gruppe "2"
||Adresse|Werkseinst.|Aktueller Wert|Adresse*|
|---|---|---|---|---|
|Ein-/Mehrkesselanlage|`01`|`1`||||
|Brenner-Mindestpausezeit (voreingestellt durch Codierstecker)|`04`|`1`|`0`|||
|Maximalbegrenzung Kesselwassertemp.|`06`|`-`|`82`|||
||`0d`|`0`|`0`|||
||`0E`|`0`|`0`|||
||`13`|`1`|`1`|||
||`14`|`1`|`1`|||
||`15`|`1`|`1`|||
|Wartung Brenner Betriebsstunden in 100|`21`|`0`|`0`|||
|Wartung Zeitintervall in Monaten|`23`|`0`|`0`|||
|Status Wartung|`24`|`0`|`0`|||
||`28`|`0`||||
||`2E`|`0`|`0`|||
|Befüllung/Entlüftung|`2F`|`0`|`0`|||
|Interne Umwälzpumpe drehzahlgeregelt?|`30`|`1`|`0`|||
|Solldrehzahl (%) interne Umwälzpumpe|`31`|`-`||||
||`38`|`0`|`0`|||

## Warmwasser/Gruppe "3"
||Adresse|Werkseinst.|Aktueller Wert|Adresse*|
|---|---|---|---|---|
||`56`|`0`|`0`|||
||`58`|`0`|`0`|||
|Speicherbeheizung: Einschaltpunkt|`59`|`0`|`0`|||
||`5b`|`0`||||
||`5E`|`0`|`0`|||
||`5F`|`0`|`0`|||
||`60`|`20`|`20`|||
||`62`|`2`|`2`|||
||`63`|`0`||||
|Bauart Umschaltventil|`65`|`-`|`3` (Grundfos)|||
|Warmwassertemp. Soll Nachheizunterdrückung|`67`|`40`||||
||`6C`|`100`||||
||`6d`|`0`||||
|Max. Wärmeleistung Trinkwassererwärmung|`6F`|`-`|`100` (%)|||
||`71`|`0`|`0`|||
||`72`|`0`|`0`|||
|Freigabe Zirkulationspumpe|`73`|`0`|`0`|||

## Solar/Gruppe "4"
||Adresse|Werkseinst.|Aktueller Wert|Adresse*|
|---|---|---|---|---|
||`00`|`8`||||
||`01`|`4`||||
|Drehzahlsteuerung-Solarkreispumpe|`02`|`0`||||
||`03`|`10`||||
||`04`|`4`||||
||`05`|`10`||||
||`06`|`75`||||
||`07`|`0`||||
|Speichermaximaltemperatur|`08`|`60`||||
||`09`|`130`||||
|Stagnationszeit-Reduzierung|`0A`|`5`||||
||`0b`|`0`||||
||`0C`|`1`||||
||`0d`|`1`||||
||`0E`|`1`||||
|Volumenstrom Solarkreis|`0F`|`70`||||
||`10`|`0`||||
|Speicher-Solltemperatur solar|`11`|`50`||||
||`12`|`20`||||
|Erweiterte Solar-Regelungsfunktionen|`20`|`0`||||
||`22`|`8`||||
||`23`|`4`||||
||`24`|`40`||||
||`25`|`50`||||
||`26`|`1`||||
||`27`|`15`||||
||`28`|`3`||||

## Heizkreis 1, Heizkreis 2, Heizkreis 3/Gruppe „5“
||Adresse|Werkseinst.|Aktueller Wert|Adresse*|
|---|---|---|---|---|
|Fernbedienung|`A0`|`0`|`1`|||
||`A1`|`0`|`0`|||
|Außentemp. Heizkreispumpe ein/aus|`A3`|`2`|`2`|||
|Frostschutz|`A4`|`0`||||
|Sparfunktion Außentemperatur|`A5`|`5`|`5`|||
|Erweiterte Sparfunktion gedämpfte Außentemperatur|`A6`|`36`|`36`|||
|Erweiterte Sparfunktion Mischer|`A7`|`0`||||
||`A8`|`1`||||
|Pumpenstillstandzeit Übergang reduziert. Betrieb|`A9`|`7`|`7`|||
|Witterungsgeführt/Raumtemperaturaufschaltung|`b0`|`0`|`0`|||
||`b2`|`8`||||
|Sparfunktion Raumtemperatur|`b5`|`0`|`0`|||
|Min. Vorlauftemperatur Heizkreis|`C5`|`20`|`20`|||
|Max. Vorlauftemperatur Heizkreis|`C6`|`74`|`74`|||
|Neigung Heizkennlinie|`d3`|`14`|`7`|||
|Niveau Heizkennlinie|`d4`|`0`|`1`|||
|Betriebsprogramm-Umschaltung|`d5`|`0`||||
||`d6`|`0`|`0`|||
||`d7`|`0`|`0`|||
|Ext. Betriebsprogramm-Umschaltung auf Heizkreis|`d8`|`0`||||
||`E1`|`1`|`1`|||
||`E2`|`50`|`50`|||
|Externe Heizkreispumpe?|`E5`|`0`|`0`|||
|Max. Pumpendrehzahl im Normalbetrieb|`E6`|`-`||||
|Min. Pumpendrehzahl|`E7`|`30`||||
||`E8`|`1`||||
||`E9`|`45`||||
|Estrichfunktion|`F1`|`0`|`0`|||
|Partybetrieb Zeitbegrenzung|`F2`|`8`|`8`|||
|Nachlaufzeit interne Umwälzpumpe (angehobener Betrieb)|`F5`|`12`||||
|Pumpenschaltung bei “Nur Warmwasser”|`F6`|`25`||||
|Pumpenschaltung bei “Abschaltbetrieb”|`F7`|`25`||||
|Beginn Temperaturanhebung|`F8`|`-5`|`-5`|||
|Ende Temperaturanhebung|`F9`|`-14`|`-14`|||
|Erhöhung Vorlauftemperatur Sollwert|`FA`|`20`|`0`|||
|Zeitdauer Erhöhung Vorlauftemperatur-Sollwert|`Fb`|`30`|`1`|||


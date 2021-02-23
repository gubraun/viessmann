# Meine Heizung

## Geräte
- Vitodens 200-W WB2C 19kW 
- Vitotronic 200 Type HO1B
- Vitocell 100-W Warmwasserspeicher

## Konfiguration
Master-Konfigurationsdateien für Vitotronic (HO1B) ("20CB") hier:
* https://github.com/openv/openv/wiki/files/vito.xml
* https://github.com/openv/openv/wiki/files/vcontrold.xml

## Hinweise zu meiner Heizung

* Es gibt einen Heizkreis
* Keine Zirkulationsleitung und -pumpe vorhanden
* Keine Speicherladepumpe vorhanden
* Kein Mischer vorhanden
* Nur eine (Umwälz-)Pumpe vorhanden
  * Es gibt aber zwei Datenpunkte: Interne Pumpe und Heizkreispumpe. Dabei handelt es sich um dieselbe Pumpe, beim zweiten Datenpunkt (Heizkreispumpe) wird der Status aber nur als "an" angezeigt, wenn die Pumpe den Heizkreis (und nicht den WW-Kreislauf) bedient.
* Kein RL-Temperatursensor vorhanden.
* Kein separater VL-Temperatursensor (VL-Temperatur entspricht Kesseltemperatur)
* Der Brenner is modulierend (d.h. es gibt keine Stufen)
* Die Befüllung ist an den Zirkulationsanschluss der WW-Speichers angeschlossen (da dieser ja nicht anderweitig genutzt wird)

## Interessante Datenpunkte zum Loggen
- Aussentemp
- Raumtemp ist/soll 0896/
- Raumtemp red. soll
- Kesseltemp (Vorlauftemp) ist/soll
- Warmwassertemp ist/soll
- Brennerstunden
- Brennerstarts
- Brennerleistung (%) A38F
    - oder Kesselleistung (%) A305
    - Brennerstufe gibt es nicht da moduliert!
- HK Niveau
- HK Steigung
- Abgastemp 0808 - Mass fuer Energiebedarf
- HK-Pumpe?
    - Zirku gibt es nicht
    - Speicherlade gibt es nicht
- Betriebsart (WW/H)
- Sparbetrieb an/aus
- Partybetrieb an/aus
- Anlagenschema (A1 + WW)

# Meine Heizung

## Geräte
- Vitodens 200-W WB2C 19kW 
- Vitotronic 200 Type HO1B
- Vitocell 100-W Warmwasserspeicher

## Besonderheiten/Hinweise
* Es gibt einen Heizkreis
* Keine Zirkulationsleitung und -pumpe vorhanden
* Keine Speicherladepumpe vorhanden
* Kein Mischer vorhanden
* Nur eine (Umwälz-)Pumpe vorhanden
  * Es gibt aber zwei Datenpunkte: Interne Pumpe und Heizkreispumpe. Dabei handelt es sich um dieselbe Pumpe, beim zweiten Datenpunkt (Heizkreispumpe) wird der Status aber nur als "an" angezeigt, wenn die Pumpe den Heizkreis (und nicht den WW-Kreislauf) bedient.
* Pumpe ist nicht drehzahlgesteuert (erst ab 2012)
  * Ist aber OK, da eh besser wenn Pumpe mit hoher Leistung läuft, insbesondere bei kleinem Kessel
* Kein RL-Temperatursensor vorhanden
* Kein separater VL-Temperatursensor (VL-Temperatur entspricht Kesseltemperatur)
* Der Brenner is modulierend (d.h. es gibt keine Stufen)
* Die Befüllung und das Ausgleichsgefäß ist an den Zirkulationsanschluss angeschlossen (da der Anschluss im WW-Kreislauf liegt und nicht anderweitig genutzt wird)
* Lt. Heizungsbauer hat in Belgien jede WW-Zapfstelle hat eigenen Anschluß 
* WW und Heizung sind separate Kreisläufe, über das Umschaltventil wird umgeschaltet

## Thermostate/Takten

#### Takten:
- Wenn Rücklaufwasser zu heiß, schaltet Brenner ab (eine Art Notabschaltung)
- Da aber weiterhin Heizanfrage vom Stellglied besteht, springt Brenner dann direkt wieder an
- Ursache: Temperatur des Wassers kann nicht abgegeben werden 

#### Thermostate an Heizkörpern:
- Drosseln den Wasserdurchfluss wenn Temperatur erreicht
- Kann man bei AT-Regelung auf gewünschte Temperatur stellen, d.h. einige Räume ggf. kälter machen

#### Wenn Thermostate immer offen:
- Erster (näherer) Heizkörper hat immer max. Durchfluss und heizt den Raum ständig weiter auf
- Andere Räume bekommen ggf. nicht genug Wärme
- Nicht gut, da dann der hydraulische Abgleich nicht funktioniert

#### Thermostate immer zu:
- Nicht gut, da Brenner dann taktet

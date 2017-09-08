# Schritte

1. Bestandsmatrizen
   wo sind sie? was gibt es? welche Granularität haben sie? (Typ, Zweck, Alter)

2. Listen der Veränderungen in den VBs im Prognosejahr:
    * Wohnbevölkerung
    * Arbeitsplätze
    * Freizeiteinrichtungen
    * Schulen und Uniplätze
    * Einkauf, Arzt, Amt, usw...

3. Modal-Split aller VBs
    wieder Frage nach Granularität? (Zweck, Alter)
    abhängig von Netzveränderung
    
4. 3 Modellierungstypen für Prognose 
    * Hochrechnung
    * Gravitationsmodell (nur gm kann veränderte Reisezeiten berücksichtigen)
    * Furness (Gravitation mittels beobachteter Verkehrsbewegungen)
    
5. Zusammenrechnen aller Ergebnismatrizen und Aggregation

6. Schönen Output generieren

# Codierungstabelle

### Verkehrstypen

* _E_ Öffentlicher Verkehr
* _M_ Motorisierter Individualverkehr (inkl. Zweirad)
* _R_ Fahrrad
* _G_ Fußgänger


### Verkehrszwecke

* _A_ Arbeit (hin- und zurück)
* _C_ Schüler
* _S_ Studenten
* _K_ Einkauf/Arzt/Amt/weitere Dienstleistungen
* _W_ Personenwirtschaftsverkehr (PWiV)
* _F_ Freizeitverkehr


### Modellierungstypen

* __hr__ Hochrechnung
* __gm__ Gravitationsmodell
* __fr__ Furness-Modell

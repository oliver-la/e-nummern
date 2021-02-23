# E-Nummern in maschinen-lesbarer Form.

## JSON Datei

Es stehen 2 Varianten bereit:

- "Pretty" JSON (de.json)
- Minified JSON (de.min.json)

## XML Datei

Es steht 1 Variante bereit:

- XML (de.xml)

## Datenstruktur

- number: string E-Nummer ohne "E"-Präfix
- name: string Bezeichnung des Stoffs
- classification: array:string Kategorisierung des Stoffes, es können mehrere zugewiesen werden.
- is_azo_dye: trinary Handelt es sich um einen Azofarbstoff?
- is_causing_allergies: trinary Sind üblicherweise nicht im Umlauf oder nur in Non-Food enthalten
- is_animal_derived: trinary Ist der Stoff von tierischem Ursprung? (> 0 = nicht vegan)

=> trinary: 0 = Nein; 1 = Ja; 2 = Möglicherweise

## Am Projekt mitwirken

Alle Dateien im Hauptverzeichnis sind mit Ausnahme von XLSX-Dateien generiert.

Hierfür wird das PHP-Skript im build-Ordner verwendet.

## Datenquellen

- [Coop](https://www.coop.ch/content/dam/gesund-essen/_pdf/e-nummern-de.pdf)

## Haftungsausschluss

Die Daten in diesem Repository sind nicht von einer qualifizierten Stelle verifiziert. Auf die Richtigkeit und Vollständigkeit der Daten wird keine Gewähr geleistet.

## Lizenz

This work is licensed under CC BY 4.0. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/
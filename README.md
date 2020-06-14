# Project Title

This is a legal citations style (CSL) based on the Austrian Neue Zitierregeln (NZR).
Please note that this is work in progress and 

## Getting Started

CSL files can be used by various bibliography software, eg. Zotero or Mandelay

### Prerequisites

You need to have a bibliography and word processing software up and running.

### Installing

Example for importing CSL to Zotero, using Word on Mac

First install to CSL to your intstallation of Zotero

```
Zotero -> Settings -> Zitation -> "+" -> Choose the nzr.cls file downloaded
```

** Irnore the warning, it is caused by the parameter words-affix-variables-on="true" on line 159 **

Now choose the correct style in Word

```
Select Zotero in the menu bar -> Document Preferences -> Choose "NZR - Neue Zitierregeln (German - Austrian Legal)
```

Now feel free to cite away...

## Special Literature

* WICHTIG: "Kommentarliteratur" untrscheidet sich von "Beiträgen in Sammelwerken" durch die Seitenzahl, ist diese leer wird von einem Kommentar ausgegangen

* "Kommentarlitatur": Wichtig - Das Feld "Seiten" leer lassen, sonst wird es als "Beiträge in Sammelwerken" betrachtet
  * Hauptwerk als "Book" (zB ABGB-ON) hinzufügen, duplizieren, Autor in "Autor" des Beitrages eintragen, Eintragsart "Buchteil" auswählen
  * "Titel" leer lassen, "Auflage", "Datum" und "Kurztitel" eintragen
  * Der letzte Stand kann in "Extra" eingetragen werden
  * Onlinekommentare: leere "Auflage", volle Information in "Extra" einfügen (zB "Version 1.04 Stand 01.08.2019")
  * §§ und Rz können als locator, also als Seitenangabe eingefügt werden
* "Beiträge in Sammelwerken": Hauptwerk als "Buch" hinzufügen, dann Eintrag duplizieren, "Titel" des Abschnittes eintragen und Eintragsart auf "Buchteil" ändern 
* "Zeitschriftenartikel" müssen eine "Anzahl der Seiten" haben
* Entscheidungen: Unter "Name des Falls" (Title) das Zitat inkl Glossen einfügen, Gericht, Beschlussdatum und Aktenzeichen für Folgezitat eintragen


## Abweichungen von den NZR2

* Für Webseiten wird, soweit verfügbar, anstatt des Abrufzeitpunktes das Jahr des Dokumentes angegeben

## Authors

* **Günter Omer** - *Adapdation to NZR* - [Orikk](https://github.com/Orikk)


## License

This project is licensed under the Creative Commons 4.0 License

## Acknowledgments

* **ao. Univ.-Prof. Dr. Dietmar Jahnel (Universität Salzburg)+* - *Author of NZR* - (https://www.ridaonline.at/zitiermaster/)
* **Andreas Geyrecker** - *Initial work (based on AZR)* - (https://lexisnexis.at)
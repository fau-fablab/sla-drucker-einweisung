SLA-Drucker Einweisung
======================

Einweisung des [FAU FabLab](https://fablab.fau.de) für den SLA-Drucker UniFormation GKtwo mit Lychee Slicer und dem Harz Phrozen Water-Washable Rapid Black.

Inhalt
------

- Regeln, Gefahren und Schutzausrüstung, Betriebsanweisungen für Drucker und Harz (Gefahrstoff)
- 3D-Modell vorbereiten: Druckbarkeit (Ausrichtung, Saugnapf-Effekt, Hohlkörper), Richtwerte für die Konstruktion
- Lychee Slicer: Drucker und Harz, Layout, Stützen, Raft, Aushöhlen, Export
- Drucken, Nachbearbeitung (Form Wash mit Wasser, Form Cure), Bezahlen
- Infos für Betreuer: Harz, Waschwasser, nFEP-Folie, typische Fehler, Wartung

Die Betriebsanweisungen stehen in `betriebsanweisung/ba_gktwo.tex` und `betriebsanweisung/ba_resin.tex`; Layout und Symbole kommen aus `fablab-document` (siehe `fablab-document/README_betriebsanweisung.md`).

Download
--------

Die neueste Version aus [GitHub](https://github.com/fau-fablab/sla-drucker-einweisung) ist als PDF abrufbar:

- [Einweisung](https://brain.fablab.fau.de/build/sla-drucker-einweisung/SLA_Drucker_Einweisung.pdf)
- [Einweisungsliste](https://brain.fablab.fau.de/build/sla-drucker-einweisung/SLA_Drucker_Einweisungsliste.pdf)
- [Betriebsanweisung Drucker](https://brain.fablab.fau.de/build/sla-drucker-einweisung/Betriebsanweisung_SLA_Drucker.pdf) (Aushang)
- [Betriebsanweisung Harz](https://brain.fablab.fau.de/build/sla-drucker-einweisung/Betriebsanweisung_Resin.pdf) (Aushang, Gefahrstoff)

Außerdem baut eine GitHub Action die PDFs bei jedem Push. Auf dem Hauptbranch entsteht dabei ein
[Release](https://github.com/fau-fablab/sla-drucker-einweisung/releases) mit Datums-Version (`vJJJJ.MM.TT`) und den PDFs.

Auschecken und bauen
--------------------

```bash
git clone --recursive git@github.com:fau-fablab/sla-drucker-einweisung.git
cd sla-drucker-einweisung
make
```

Die PDFs landen in `output/`. Layout, Kopf- und Fußzeile und das Logo des FAU FabLab (mit
FAU-Schriftzug) kommen aus dem Untermodul [fablab-document](https://github.com/fau-fablab/fablab-document),
das Logo wiederum aus dessen Untermodul [logo](https://github.com/fau-fablab/logo). Bei einem bestehenden
Klon die Untermodule mit `git submodule update --init --recursive` laden.

Technische Details zum Buildserver: [fau-fablab/buildserver](https://github.com/fau-fablab/buildserver)

[![Build Status](https://brain.fablab.fau.de/build/sla-drucker-einweisung/status.svg)](https://brain.fablab.fau.de/build/sla-drucker-einweisung/)
[![TODOs](https://brain.fablab.fau.de/build/sla-drucker-einweisung/status-todos.svg)](https://brain.fablab.fau.de/build/sla-drucker-einweisung/)
[![PDF bauen](https://github.com/fau-fablab/sla-drucker-einweisung/actions/workflows/pdf.yml/badge.svg)](https://github.com/fau-fablab/sla-drucker-einweisung/actions/workflows/pdf.yml)

Lizenz
------

[![Lizenz: CC BY-SA 3.0](https://licensebuttons.net/l/by-sa/3.0/de/88x31.png)</br>CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/)

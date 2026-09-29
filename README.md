SLA Drucker Einweisung
=========================

Einweisung des [FAU FabLab](https://fablab.fau.de) für den SLA-Drucker UniFormation GKtwo mit Lychee Slicer und dem Harz Phrozen Water-Washable Rapid Black.

Die Einweisung enthält die Betriebsanweisungen für den Drucker (`betriebsanweisung/ba_gktwo.tex`) und für das Harz als Gefahrstoff (`betriebsanweisung/ba_resin.tex`). Beide gibt es zusätzlich als eigenes PDF zum Aushang. Layout und Symbole kommen aus `fablab-document` (siehe `fablab-document/README_betriebsanweisung.md`).

Die neueste Version gibt es hier zum Download als PDF:
* [Einweisung](https://brain.fablab.fau.de/build/sla-drucker-einweisung/SLA_Drucker_Einweisung.pdf)
* [Einweisungsliste](https://brain.fablab.fau.de/build/sla-drucker-einweisung/SLA_Drucker_Einweisungsliste.pdf)
* [Betriebsanweisung Drucker](https://brain.fablab.fau.de/build/sla-drucker-einweisung/Betriebsanweisung_SLA_Drucker.pdf) (Aushang)
* [Betriebsanweisung Harz](https://brain.fablab.fau.de/build/sla-drucker-einweisung/Betriebsanweisung_Resin.pdf) (Aushang, Gefahrstoff)

Zusätzlich baut eine GitHub Action bei jedem Push auf `master` ein Release mit Datums-Version (`vJJJJ.MM.TT`) und den PDFs:
* [Releases auf GitHub](https://github.com/fau-fablab/sla-drucker-einweisung/releases)

auschecken
----------

```bash
git clone --recursive git@github.com:fau-fablab/sla-drucker-einweisung.git
```

Technische Details zum Buildserver siehe auf macgyver `/home/buildserver/README`

[![Build Status](https://brain.fablab.fau.de/build/sla-drucker-einweisung/status.svg)](https://brain.fablab.fau.de/build/sla-drucker-einweisung/)
[![TODOs](https://brain.fablab.fau.de/build/sla-drucker-einweisung/status-todos.svg)](https://brain.fablab.fau.de/build/sla-drucker-einweisung/)
[![PDF bauen](https://github.com/fau-fablab/sla-drucker-einweisung/actions/workflows/pdf.yml/badge.svg)](https://github.com/fau-fablab/sla-drucker-einweisung/actions/workflows/pdf.yml)


Lizenz
------

[![Lizenz: 3.0](https://licensebuttons.net/l/by-sa/3.0/de/88x31.png)</br>CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/)

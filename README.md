# FabLab Zürich Laser Einführung
Eine kurze, einfache Einführung zum Laser im [FabLab Zürich](https://zurich.fablab.ch/).

## Was ist ein FabLab?
Ein FabLab ist eine offene Werkstatt für digitale Fabrikation.

Hier eine kurze [Präsentation](http://www.tamberg.org/fablabzurich/2017/WasIstEinFabLab.pdf) der Idee dahinter.

## Was ist ein Laser?
Ein Laser oder Laser-Cutter schneidet Sperrholz, Karton, Leder, usw. (aber [kein PVC](https://lasergods.com/can-i-cut-vinyl-pvc-in-a-laser/)) mit Licht.

Dazu gibt's eine [Software](https://lightburnsoftware.com/) um Geschwindigkeit und Stärke des Lasers zu konfigurieren.

Wir haben einen [blauen AKJ AKJ_6090](http://wiki.zurich.fablab.ch/AKJ_6090) und einen [roten TT900](http://wiki.zurich.fablab.ch/TT900) Laser.

Beide schneiden Platten von 600 x 900 mm, < 10 mm.

## Was ist ein Design?
Ein Design (für den Laser) ist eine Vektor-basierte zweidimensionale Zeichnung.

Der Laser-Cutter kann eine Linie entweder schneiden oder gravieren.

Falls Du beides brauchst, verwende verschiedene Farben.

## Der einfache Weg
Dieser Weg sollte etwa 15 Minuten dauern, falls ein Laser frei ist.

### Lade ein Design runter
Lade ein Design runter, z.B. von https://www.thingiverse.com/tag:laser

Oder nutze einen Design Generator, z.B. für [Schachteln](https://ddg.co/?q=box+generator) (in _mm_).

Unsere Laser Software versteht Dateien im DXF, SVG oder PDF Format.

### Cut the design
Ask the lab manager for help with the laser cutter.

## The hard way
This takes more than 30 minutes, but it's worth your time.

### Install 2D design software
[Download Inkscape](https://inkscape.org/), a free 2D design software.

No laptop? Use one of our computers.

### Set up Inkscape
Set _File > Document properties >_ [display units](https://inkscape-manuals.readthedocs.io/en/latest/managing-workspace.html?#document-properties-dialog) to _mm_.

Set _Object > Fill and stroke >_ [stroke width](https://inkscape-manuals.readthedocs.io/en/latest/fill-and-stroke-dialog.html) to _0.01 mm_.

Enable _View > Display mode > [x] Visible hairlines_.

### Create your design
Draw some [squares](https://inkscape-manuals.readthedocs.io/en/latest/squares-and-rectangles.html) and [circles](https://inkscape-manuals.readthedocs.io/en/latest/circles-ellipses-and-arcs.html).

[Align and distribute](https://inkscape-manuals.readthedocs.io/en/latest/align-and-distribute.html) them.

[Save as SVG](https://inkscape-manuals.readthedocs.io/en/latest/saving.html) or [PDF](https://inkscape-manuals.readthedocs.io/en/latest/export-pdf.html).

### Cut your design
Ask the lab manager for help with the laser cutter.

Take notes and try it yourself next time.

Configure laser speed and power.

Set laser focus and origin.

### Stay safe
Make sure the [air filter](http://wiki.zurich.fablab.ch/BOFA_AD2000_iQ) is switched on.

Always close the lid before cutting.

Never leave the laser unattended.

### Iterate...
Adapt your design and your settings, try again.

Keep going, you will get there :)

## Resources
* [Inkscape 2D design software docs](https://inkscape-manuals.readthedocs.io/en/latest/)
* [LightBurn laser software docs](https://github.com/LightBurnSoftware/Documentation/blob/master/README.md)
* [AKJ6090 laser tutorial](http://wiki.zurich.fablab.ch/images/9/97/Anleitung_AKJ6090.pdf)
* [FabLab Zürich Wiki](http://wiki.zurich.fablab.ch/)

biblatex-iest
=============

Bibliografiestil für das IEST
-----------------------------
Der biblatex-Bibliografiestil iest verhält sich wie der Standardstil numeric-comp mit folgenden Abweichungen:

- Autoren- Herausgeber- und Übersetzerangabe als Nachname, Vorname
- durchgehende Angabe der Vornamen als Initialen
- Doppelpunkt nach dem letzten Autoren- Herausgeber- und Übersetzernamen

Damit wird eine Vorgabe des Instituts für Eisen- und Stahltechnologie der TU Bergakademie Freiberg umgesetzt.

Ein Artikel über den Stil findet sich unter http://texwelt.de/blog/modifizieren-eines-biblatex-stils/

Installation in TeX Live
------------------------
- Kopieren der Datei <tt>iest.cbx</tt> nach <tt>~/texmf/tex/latex/biblatex/cbx</tt>
- Kopieren der Datei <tt>iest.bbx</tt> nach <tt>~/texmf/tex/latex/biblatex/bbx</tt>

Installation in MacTeX
----------------------
- Kopieren der Datei <tt>iest.cbx</tt> nach <tt>~/Library/texmf/tex/latex/biblatex/cbx</tt>
- Kopieren der Datei <tt>iest.bbx</tt> nach <tt>~/Library/texmf/tex/latex/biblatex/bbx</tt>

Installation in MikTeX
----------------------
1. Anlegen eines privaten Baumes, z. B. unter ~/texmf (muss außerhalb des Verzeichnisses der MikTeX-Installation liegen)
2. Kopieren der Datei iest.cbx nach ~/texmf/tex/latex/biblatex/cbx
3. Kopieren der Datei iest.bbx nach ~/texmf/tex/latex/biblatex/bbx
4. Registrieren des privaten Baumes als „Root“
	a. MikTeX Settings starten
	b. Reiter „Roots“
	c. Schaltfläche „Add..“
	d. obigen Ordner auswählen
	e. ggf. Suchreihenfolge anpassen
	f. Schaltfläche „Übernehmen“

Systeme
=======
plattformunabhängig

Gestestet mit Texlive 2013 unter Ubuntu 14.04 LTS mit dem Paket tubaf-base.





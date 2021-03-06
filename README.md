biblatex-iest
=============

Bibliografiestil für das IEST
-----------------------------
Der Biblatex-Stil `iest` verhält sich wie der Standardstil `numeric-comp` mit folgenden Abweichungen:

- Autoren- Herausgeber- und Übersetzerangabe als Nachname, Vorname
- durchgehende Angabe der Vornamen als Initialen
- Abkürzen der Autorenliste mit "et al." statt "u. a." bei mehr als drei Autoren
- Doppelpunkt nach dem letzten Autoren- Herausgeber- und Übersetzernamen
- Verlagsangabe als Verlag, Ort, Datum
- Sortierung der Bibliografie nach Zitationsreihenfolge
- Flattersatz in der Bibliografie

Damit wird eine Vorgabe des Instituts für Eisen- und Stahltechnologie der TU Bergakademie Freiberg (IEST) umgesetzt.

Ein Artikel über den Stil findet sich unter http://texwelt.de/blog/modifizieren-eines-biblatex-stils/.
Eine laufend aktualisierte druckoptimierte PDF-Version des Artikels ist unter http://github.com/Ekkehardt/dok-biblatex-iest gehostet.
Im August 2015 wurde eine aktualisierte Fassung des Artikels in freiesMagazin veröffentlicht: http://www.freiesmagazin.de/ftp/2015/freiesMagazin-2015-08.pdf.
Am 27.08.2015 wurde diese Fassung von pro-Linux aufgegriffen: http://www.pro-linux.de/artikel/2/1787/modifizieren-eines-biblatex-stils.html.

Installation in TeX Live
------------------------
- Kopieren der Dateien <tt>iest.cbx</tt> und <tt>iest.bbx</tt>nach <tt>~/texmf/tex/latex/biblatex-iest/</tt>
  Der Verzeichnisbaum muss gegebenenfalls (für den Benutzer lesbar) angelegt werden.

Installation in MacTeX
----------------------
- Kopieren der Dateien <tt>iest.cbx</tt> und <tt>iest.bbx</tt> nach <tt>~/Library/texmf/tex/latex/biblatex-iest/</tt>
  Der Verzeichnisbaum muss gegebenenfalls (für den Benutzer lesbar) angelegt werden.

Installation in MikTeX
----------------------
<ol>
<li>Anlegen eines privaten Baumes, z. B. unter <tt>~/texmf</tt> (muss außerhalb des Verzeichnisses der MikTeX-Installation liegen)
<li>Kopieren der Dateien <tt>iest.cbx</tt> und <tt>iest.bbx</tt> nach <tt>~/texmf/tex/latex/biblatex-iest/</tt>
<li>Registrieren des privaten Baumes als „Root“
	<ol>
		<li>MikTeX Settings starten
		<li>Reiter „Roots“
		<li>Schaltfläche „Add..“
		<li>obigen Ordner auswählen
		<li>ggf. Suchreihenfolge anpassen
		<li>Schaltfläche „Übernehmen“
	</ol>
</ol>

Systeme
-------
plattformunabhängig

Getestet mit TeX Live 2014 und 2015 unter Ubuntu 14.04 LTS mit dem Paket tubaf-base (Corporate Design der TU Bergakademie Freiberg) sowie scrbook und scrartcl.

Referenzen
----------
Über das IEST hinaus wurde der Stil `iest` für den Tagungsband des XXII. International Students' Day of Metallurgy (ISDM) 2015 verwendet. Der ISDM 2015 fand im Mai 2015 an der RWTH Aachen University statt.

Lizenz
------
Der biblatex-Stil `iest` steht unter der LPPL 1.3.

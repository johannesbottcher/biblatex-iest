biblatex-iest
=============

Bibliografiestil für das IEST
-----------------------------
Der biblatex-Bibliografiestil iest verhält sich wie der Standardstil numeric-comp mit folgenden Abweichungen:

- Autoren- Herausgeber- und Übersetzerangabe als Nachname, Vorname
- durchgehende Angabe der Vornamen als Initialen
- Doppelpunkt nach dem letzten Autoren- Herausgeber- und Übersetzernamen
- Abkürzen der Autorenliste mit "et al." statt "u. a." bei mehr als drei Autoren

Damit wird eine Vorgabe des Instituts für Eisen- und Stahltechnologie der TU Bergakademie Freiberg umgesetzt.

Ein Artikel über den Stil findet sich unter http://texwelt.de/blog/modifizieren-eines-biblatex-stils/
Eine laufend aktualisiserte druckbare PDF-Version des Artikels ist unter http://github.com/Ekkehardt/dok-biblatex-iest gehostet.

Installation in TeX Live
------------------------
- Kopieren der Dateien <tt>iest.cbx</tt> und <tt>iest.bbx</tt>nach <tt>~/texmf/tex/latex/biblatex-iest/</tt>


Installation in MacTeX
----------------------
- Kopieren der Dateien <tt>iest.cbx</tt> und <tt>iest.bbx</tt> nach <tt>~/Library/texmf/tex/latex/biblatex-iest/</tt>

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
=======
plattformunabhängig

Gestestet mit Texlive 2013 unter Ubuntu 14.04 LTS mit dem Paket tubaf-base.





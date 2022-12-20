# LaTeX-Unterlagen

> In diesem Repository befinden sich die LaTeX-Unterlagen zum Modul.

## Inhalt

- Der Inhalt entspricht dem Text der Aufgabe 2 des Modul.

- Es kann sinnvoll sein, sich die PDF zur Aufgabe zwei noch einmal
anzusehen


## PDF erstellen

> Das geht ganz schnell und einfach:

1. Zuerst installieren wir LaTeX (tug.org/texlive/)
2. Dann nutzen wir PDFLaTeX zum Erstellen des PDF
	"pdflatex ./task.tex" (Das muessen wir mehrfach machen, damit die PDF auch fertig wird)
3. Alternativ koennen wir auch einfach LaTeX Mk nutzen 
	"latexmk -pdf ./task.tex"


## !!Achtung!!

> LaTeX erstelle einige nervige Dateien (.aux, .log) diese muss man loeschen bevor
man einen Commit mit seinen Aenderungen macht!

# Meine Homepage – Version mit Lorem ipsum

Die Homepage bleibt bewusst einfach: weißer Hintergrund, Times, blaue Links und wenig CSS. Der Name oben lautet Anton Steinfadt; „Notizen usw.“ heißt jetzt „Adversaria“.

## Neue Beiträge in Adversaria, Mathematik oder Philosophie

Die Website ist eine statische GitHub-Pages-Seite. Neue Beiträge veröffentlichst du, indem du die passende HTML-Datei im GitHub-Repository bearbeitest. Die Änderungen werden nach dem Speichern automatisch veröffentlicht. Das geht direkt im Browser, nachdem du dich bei GitHub angemeldet hast.

1. Öffne im Repository die Datei `notizen.html`, `mathematik.html` oder `philosophie.html` und klicke auf das Stift-Symbol („Edit this file“).
2. Suche nach `<!-- Neue Beiträge hier ergänzen; eine Vorlage steht in README.md. -->`.
3. Füge an dieser Stelle einen Beitrag ein. Kopiere die Vorlage unten und ersetze Titel, Datum und Text. Beim ersten Beitrag entferne zusätzlich den Hinweis „Noch keine eigenen Beiträge.“.
4. Klicke auf „Commit changes“. GitHub Pages veröffentlicht die Änderung automatisch.

```html
<article>
  <h3>Titel des Beitrags</h3>
  <p class="small">TT.MM.JJJJ</p>
  <p>Hier steht der kurze Beitrag.</p>
  <p><a href="pdfs/dateiname.pdf">PDF zum Beitrag (PDF)</a></p>
</article>
```

Die letzte Zeile mit dem PDF-Link kannst du weglassen, wenn es keinen Anhang gibt. Lade PDFs in den Ordner `pdfs` im Repository. Wenn er noch nicht existiert: Über „Add file“ → „Create new file“ den Namen `pdfs/.gitkeep` eingeben und speichern; dadurch wird der Ordner angelegt. Danach kannst du ihn öffnen und deine PDF-Dateien über „Add file“ → „Upload files“ hochladen. Verwende im Beitrag exakt denselben Dateinamen wie beim Upload, zum Beispiel `pdfs/satz-vom-25-10-2026.pdf`. Dateien im öffentlichen Repository sind öffentlich abrufbar; lade dort nur PDFs hoch, die öffentlich sein dürfen.

## Website lokal ansehen

Öffne `index.html` per Doppelklick im Browser. Zum Ändern kannst du die HTML-Dateien mit einem Texteditor öffnen. `style.css` enthält die Abstände und Schriftregeln.

## Veröffentlichung und Rechtliches

Die Website ist unter https://antonsteinfadt.github.io/ erreichbar. GitHub Pages veröffentlicht die Dateien aus dem öffentlichen Repository; alle hochgeladenen Inhalte, auch PDFs, sind öffentlich. `impressum.html` enthält weiterhin Blindtext und ist rechtlich nicht veröffentlichungsreif.

# Anton Steinfadt — Homepage

Eine schlichte persönliche Website mit weißem Hintergrund, Times-Schrift und blauen Links. Sie enthält die Bereiche Mathematik, Philosophie und Adversaria.

## Einen Beitrag ergänzen

Die Website ist statisch. Neue Beiträge veröffentlichst du im jeweiligen Bereich über GitHub:

1. Öffne `notizen.html`, `mathematik.html` oder `philosophie.html` im Repository und wähle „Edit this file“.
2. Suche nach dem Kommentar `<!-- Neue Beiträge hier ergänzen; eine Vorlage steht in README.md. -->` und füge dort einen Beitrag ein.
3. Verwende diese Vorlage und ändere Überschrift, Datum und Text:

```html
<article>
  <h3>Titel des Beitrags</h3>
  <p class="small">TT.MM.JJJJ</p>
  <p>Hier steht der kurze Beitrag.</p>
  <p><a href="pdfs/dateiname.pdf">PDF zum Beitrag (PDF)</a></p>
</article>
```

Die letzte Zeile ist optional. Entferne beim ersten eigenen Beitrag auch den Hinweis „Neue Beiträge folgen nach und nach.“. Speichere den Eintrag mit „Commit changes“; GitHub Pages aktualisiert die Website automatisch.

## PDF-Dateien anhängen

Lade PDFs in den Ordner `pdfs` im Repository. Wenn er noch nicht existiert, erstelle über „Add file“ → „Create new file“ die Datei `pdfs/.gitkeep`; damit wird der Ordner angelegt. Öffne anschließend den Ordner und lade dort die PDF-Datei über „Add file“ → „Upload files“ hoch. Verwende im Link exakt denselben Dateinamen, zum Beispiel `pdfs/arbeit.pdf`.

Das Repository ist öffentlich. Beiträge und PDFs sind deshalb für alle zugänglich; lade nur Dateien hoch, die öffentlich sein dürfen.

## Lokal ansehen

Öffne `index.html` im Browser. Die Seite funktioniert ohne Installation oder externe Bibliotheken. `style.css` enthält die wenigen Stilregeln.

## Datenschutz

Die Seite ist als private, nicht kommerzielle Homepage gedacht. Es gibt keine Kontaktformulare, Analyse- oder Werbedienste. Hinweise zur Verarbeitung durch den Hosting-Anbieter stehen auf der Seite „Kontakt und Datenschutz“.

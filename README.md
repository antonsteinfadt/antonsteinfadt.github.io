# Meine Homepage – Version mit Lorem ipsum

Das ist die ursprüngliche, bewusst einfache HTML-Homepage, jetzt mit **Blindtext**. Das Aussehen wurde beibehalten: Times New Roman, blaue Links, eine ASCII-Skizze, keine externen Bibliotheken und kein JavaScript. Die Navigation bleibt deutsch und benutzbar; fast alle übrigen sichtbaren Texte sind „Lorem ipsum“.

## 1. Auf dem eigenen Computer ansehen

1. `homepage-lorem-ipsum.zip` herunterladen und **entpacken** (Rechtsklick → Alle extrahieren).
2. Den entpackten Ordner öffnen.
3. Auf `index.html` doppelklicken. Die Homepage öffnet sich im Standardbrowser – auch ohne Internet.
4. Auf „Mathematik“, „Philosophie“ und „Notizen“ klicken, um die anderen Seiten zu testen.

## 2. Texte später ändern

- Die Dateien `index.html`, `mathematik.html`, `philosophie.html` und `notizen.html` kann man in einem Texteditor wie dem Windows-Editor oder Visual Studio Code öffnen. Dazu Rechtsklick → „Öffnen mit“ → Editor.
- Den Text zwischen HTML-Tags überschreiben. Beispiel: `<p>Lorem ipsum dolor sit amet.</p>` → `<p>Hier stelle ich meine Arbeit vor.</p>`.
- `index.html` ist die Startseite. In `style.css` stehen die Farben, Schriftgrößen und Abstände.
- Nach dem Speichern Browser neu laden (Strg+R).
- `impressum.html` enthält derzeit **nur Blindtext** und ist **rechtlich nicht veröffentlichungsreif**. Vor Veröffentlichung rechtliche Pflichtangaben und Datenschutzthemen klären und ersetzen.

## 3. Kostenlos veröffentlichen mit GitHub Pages

Du brauchst nur ein kostenloses GitHub-Konto und einen Browser; keine Programmierung und kein eigener Server.

1. Gehe zu https://github.com und melde dich an oder registriere dich.
2. Klicke auf „New repository“ (alternativ https://github.com/new).
3. Benenne das Repository **GENAU** `<DEIN-GITHUB-NAME>.github.io` (statt `<DEIN-GITHUB-NAME>` den GitHub-Nutzernamen in Kleinbuchstaben einsetzen).
4. Wähle **Public** und erstelle das Repository (`Create repository`). Wenn GitHub eine Initialisierung mit README anbietet, ist das möglich, aber nicht erforderlich.
5. Öffne das Repository. Unter „Add file“ → „Upload files“ wählst du **alle entpackten Dateien aus dem Ordner** aus, nicht die ZIP-Datei. Wichtig: `index.html` und `style.css` müssen sich im Hauptverzeichnis des Repositorys befinden, nicht in einem Unterordner.
6. Bestätige unten mit „Commit changes“.
7. Öffne `Settings` → links `Pages`. Unter `Build and deployment` → `Source` wähle `Deploy from a branch`, danach `main` und `/(root)`. Auf `Save` klicken.
8. Die Website ist schließlich unter `https://DEIN-GITHUB-NAME.github.io/` zu sehen. Es kann laut GitHub bis zu zehn Minuten dauern.

Wenn die Seite zunächst 404 zeigt: Einstellungen unter `Pages` erneut prüfen (main / root), warten und sicherstellen, dass `index.html` direkt im Hauptverzeichnis liegt. Im Repository auf `Actions` prüfen, ob der Pages-Workflow erfolgreich war.

## 4. Eigene Domain (freiwillig)

Du kannst später z. B. `vorname-nachname.de` kaufen und unter `Settings` → `Pages` → `Custom domain` hinzufügen. Anschließend sind DNS-Einträge beim Domain-Anbieter erforderlich. GitHub bietet dazu eine Anleitung: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

## 5. Kosten & Datenschutz

GitHub Pages ist für eine öffentliche Website aus einem öffentlichen GitHub-Free-Repository kostenlos. **Die Website und alle hochgeladenen Dateien sind dann öffentlich.** Keine privaten Dokumente oder Passwörter hochladen. Die Dateien enthalten keine Tracker oder Cookiebanner; der Hosting-Anbieter verarbeitet aber technisch Verbindungsdaten. Vor der Veröffentlichung deutsche Impressums- und Datenschutzpflichten prüfen.

Hilfen von GitHub:
- https://docs.github.com/en/pages/quickstart
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository

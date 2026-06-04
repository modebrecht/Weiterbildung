Rolle: Du bist ein kreativer Frontend-Entwickler und UI/UX-Experte. 
Aufgabe: Erstelle eine interaktive, visuell beeindruckende Single-Page Web-App (HTML, CSS, JS in einer einzigen Datei) namens "Aha-Effekt: 10 Schätzfragen".

Kernelement & Mechanik (Der Aha-Effekt):
Der Nutzer sieht eine Schätzfrage und wählt über einen Slider einen Wert. Nach Klick auf "Auflösen" wird die tatsächliche Zahl groß eingeblendet. Der eigentliche "Aha-Effekt" entsteht danach: Die abstrakte Zahl wird visuell übersetzt, indem sich ein Raster mit dutzenden kleinen Icons füllt (z.B. 8000 Liter = 50 Badewannen, die nacheinander animiert aufpoppen).

Design & UI/UX (Stunning Graphics):
1. Premium Dark Mode: Nutze dunkle Blautöne (z.B. Tailwind slate-900) als Basis.
2. Glassmorphism: Die Haupt-Cards sollen halbtransparent sein mit einem Backdrop-Blur.
3. Dynamische Thematisierung: Jede Frage hat eine eigene Akzentfarbe (Hex-Code). Ändere über CSS-Variablen dynamisch leuchtende Hintergrund-Orbs (Glow-Effekte) und die Farbe von Slider, Texten und Icons, passend zur aktuellen Frage.
4. Custom Slider: Baue einen stark stilisierten Range-Slider (kein Standard-Browser-Design), dessen Daumen (Thumb) bei Interaktion größer wird.
5. Typografie: Modern, serifenlos, große Kontraste (z.B. sehr fette Zahlen, feine Beschriftungen).
6. Zahlenformat: Verwende das Schweizer Format mit Apostroph für Tausender (z.B. 20'000).

Grafiken & Animationen (NUR Inline-SVGs, KEINE externen Bilder):
Jede Frage benötigt ZWEI Arten von SVGs:
1. Hero-Grafik: Eine große, thematisch passende SVG-Grafik, die unter der Frage schwebt. Sie muss eine Endlosschleifen-Animation haben (z.B. sanftes Schweben, Pulsieren oder Rotieren) und einen leichten Drop-Shadow in der jeweiligen Themenfarbe besitzen.
2. Icon-Grafik: Ein kleines SVG für das Raster der Auflösung (z.B. kleine Badewanne, Baum, Kreditkarte).
Wenn die Frage aufgelöst wird, muss die Hero-Grafik weich verschwinden und das Raster mit den Icon-Grafiken muss mit einem Stagger-Effekt (verzögertes Einblenden, z.B. Pop-In und Fill-Animation) nacheinander erscheinen.

Technische Anforderungen:
- Frameworks: Nutze Tailwind CSS via CDN (<script src="https://cdn.tailwindcss.com"></script>).
- Vanilla JavaScript für die Logik.
- Alles MUSS zwingend in einer einzigen .html Datei liegen.
- Responsiv: Perfekt bedienbar auf Mobile und Desktop (kein horizontales Scrollen).
- Mobile first dynamisches Design.
- Feedback-Logik: Gib dem Nutzer Feedback zu seiner Schätzung (Perfekt, sehr nah dran [<15% Abweichung], zu hoch, zu niedrig).

Inhalt (Die 10 Fragen):
Integriere folgende 10 Fragen als Array in JS mit jeweils passendem Min/Max/Step für den Slider:
1. Liter Wasser für 1 Jeans (Antwort: 8000L. Visualisierung: 50 Badewannen à 160L. Farbe: Blau).
2. Mikroplastik gegessen pro Jahr (Antwort: 260g. Visualisierung: 52 Kreditkarten à 5g. Farbe: Violett).
3. CO2 Flug Zürich-New York retour (Antwort: 2000kg. Visualisierung: 200 Bäume à 10kg. Farbe: Grün).
4. Food Waste pro Kopf/Jahr Schweiz (Antwort: 120kg. Visualisierung: 24 Abfallsäcke à 5kg. Farbe: Bernstein).
5. Reines Gold in Olympia-Goldmedaille (Antwort: 6g. Visualisierung: 6 Gramm-Stücke à 1g. Farbe: Gold).
6. Stunden YouTube Uploads pro Minute (Antwort: 500h. Visualisierung: 250 Spielfilme à 2h. Farbe: Rot).
7. Herzschläge pro Tag (Antwort: 100'000. Visualisierung: 100 Icons à 1000 Schläge. Farbe: Pink).
8. Papierverbrauch pro Person/Jahr CH (Antwort: 110kg. Visualisierung: 22 Papiertaschen à 5kg. Farbe: Grau).
9. Schokolade gegessen pro Jahr CH (Antwort: 11kg. Visualisierung: 110 Tafeln à 100g. Farbe: Schokobraun).
10. Länge Blutgefäße Mensch (Antwort: 100'000km. Visualisierung: 2.5 Erdumrundungen à 40'000km. Farbe: Hellblau).

Ablauf-Logik:
Nach dem Laden startet Frage 1. Slider bewegen -> Klick "Auflösen" -> Berechnung & Feedback -> Stagger-Animation des Rasters -> "Nächste Frage" Button erscheint -> Bei Klick Fade-Transition zur nächsten Frage mit Farbwechsel der App-Umgebung. Nach Frage 10 ein "Quiz beendet" Screen.

Erstelle eine interaktive HTML-Demo für den Unterricht zum Thema Photosynthese.

## Thema
Fach: Biologie / NMG  
Zielgruppe: 7. Klasse  
Lernziel: Die Lernenden verstehen, welche Stoffe bei der Photosynthese benötigt werden, welche Produkte entstehen, wo diese Stoffe in der Pflanze vorkommen und warum Sauerstoff entsteht.

## Grundidee
Baue ein interaktives Photosynthese-Labor als hochwertige Single-Page-Web-App.

Die App darf nicht als lange Scrollseite wirken. Sie soll in mehrere separate Ansichten innerhalb derselben HTML-Datei aufgeteilt sein:

1. Startansicht mit Station 1 und Station 2 auf einem Screen
2. Eigene Ansicht: Wie entsteht Sauerstoff?
3. Eigene Ansicht: Sortier-Duell
4. Eigene Ansicht: Wissens-Rallye

Zwischen den Ansichten gibt es klare Weiter- und Zurück-Buttons.

## Technische Anforderungen
- Alles in einer einzigen HTML-Datei
- HTML, CSS und JavaScript direkt in derselben Datei
- Tailwind CSS per CDN verwenden
- Vanilla JavaScript für die gesamte Logik
- Keine Build-Tools
- Mobile-first und responsive
- Touch-optimiert
- Drag-and-drop und zusätzlich Click-to-place für Tablets/Smartphones
- Fortschritt global zählen
- Am Ende ein Erfolgserlebnis mit Modal, Sound und Konfetti

## Design
- Moderner Dark Mode
- Glasartige Panels mit leichter Transparenz und Blur
- Farben: Dunkles Slate/Navy als Basis, Akzente in Emerald, Sky, Teal und Amber
- Grosse klickbare Elemente
- Gute Lesbarkeit auf Mobile und Desktop
- Klare Stationen, keine überladene Dauer-Scrollseite
- Runde Zielpunkte im Diagramm
- Kleine Animationen für korrekt/falsch, z. B. Shake bei Fehlern und Glow bei Erfolg

## Header
Oben steht ein kompakter Header:
- Titel: PHOTOSYNTHESE PRO
- Untertitel: Interaktives NMG-Labor • Level-Up Edition
- Globaler Fortschritt: "0 / 15 Aufgaben gelöst"
- Fortschrittsbalken

Der Gesamtfortschritt zählt:
- 5 Diagramm-Zuordnungen
- 6 Sortierkarten
- 4 Multiple-Choice-Fragen

## Ansicht 1: Station 1 und 2
Diese Ansicht ist der Startscreen.

### Station 1: Die Labor-Bausteine
Links gibt es Karten zum Zuordnen:

Edukte / Eingangsstoffe:
- Wasser, H₂O, aus dem Boden
- Kohlenstoffdioxid, CO₂, aus der Luft
- Lichtenergie, Sonne, Motor der Reaktion

Produkte:
- Sauerstoff, O₂, wird abgegeben
- Glucose, Traubenzucker, Energie für die Pflanze

Die Karten sollen per Drag-and-drop und per Klick auswählbar sein.

Zusätzlich gibt es einen Formel-Spickzettel:
6 H₂O + 6 CO₂ + Licht -> C₆H₁₂O₆ + 6 O₂

### Station 2: Modell-Zuordnung
Rechts gibt es ein interaktives Pflanzenmodell als Inline-SVG:
- Sonne
- Boden
- Wurzeln
- Stängel
- Blätter
- Pfeile für Wasseraufnahme, CO₂-Eingang und O₂-Ausgang

Es gibt 5 Zielpunkte:
- Sonne akzeptiert Lichtenergie
- Wurzeln akzeptieren Wasser
- Blatt-Eingang akzeptiert Kohlenstoffdioxid
- Blatt-Ausgang akzeptiert Sauerstoff
- Speicher akzeptiert Glucose

Bei richtiger Zuordnung:
- Zielpunkt wird ausgefüllt
- Karte wird ausgegraut
- Fortschritt steigt
- positives Feedback

Bei falscher Zuordnung:
- rotes Feedback
- Shake-Animation

Unten gibt es einen Button:
"Weiter: Wie entsteht Sauerstoff?"

## Ansicht 2: Wie entsteht Sauerstoff?
Diese Ansicht zeigt das Chemie-Mikroskop.

Titel:
"Das Chemie-Mikroskop: Wie entsteht Sauerstoff?"

Baue eine schrittweise Visualisierung mit drei Buttons:

1. Rohstoffe strömen ein
   - Zeige Wasser (H₂O) und Kohlenstoffdioxid (CO₂)
   - Erklärung: Wasser steigt aus den Wurzeln herauf. CO₂ dringt durch die Spaltöffnungen des Blattes in den Chloroplasten ein.

2. Wasserspaltung durch Licht
   - Zeige Wasserstoff (H) und Sauerstoff (O₂)
   - Erklärung: Lichtstrahlen knacken das stabile Wassermolekül. Sauerstoff ist für die Pflanze in diesem Moment ein Abfallprodukt und strömt aus.

3. Synthese von Glucose
   - Zeige einen vereinfachten Glucose-Baustein C₆H₁₂O₆
   - Erklärung: Aus Wasserstoff und Kohlenstoff aus CO₂ synthetisiert die Pflanze energiereiche Glucose.

Wichtig:
- Verwende echte Unicode-Formeln wie CO₂, O₂, H₂O und C₆H₁₂O₆.
- Verwende keine Markdown- oder LaTeX-Reste wie `$CO_2$`, `$O_2$` oder `**Glucose**`.

Navigation:
- Zurück zu 1 & 2
- Weiter: Sortier-Duell

## Ansicht 3: Sortier-Duell
Die Lernenden sortieren Begriffe in zwei Zonen.

Karten:
- Kohlenstoffdioxid
- Wasser
- Lichtenergie
- Sauerstoff
- Glucose
- Stärke (Speicherstoff)

Zonen:
- Edukte / Ausgangsstoffe
- Produkte / Endstoffe

Richtige Zuordnung:
- Karte wird in die Zone verschoben
- Karte wird grün markiert
- Zähler steigt
- Fortschritt steigt

Falsche Zuordnung:
- rotes Feedback
- Shake-Animation

Navigation:
- Zurück: Sauerstoff
- Weiter: Wissens-Rallye

## Ansicht 4: Wissens-Rallye
Baue vier Multiple-Choice-Fragen.

Frage 1:
Woher holt sich eine Pflanze das unsichtbare Kohlenstoffdioxid (CO₂)?
- A) Sie saugt es flüssig über die Wurzeln aus der Erde auf.
- B) Über winzige Poren (Spaltöffnungen) an der Unterseite ihrer Blätter. RICHTIG
- C) Sie stellt das Gas im Stängel selbst her.

Frage 2:
Welcher spezielle Farbstoff fängt in den Blättern die Sonnenenergie ein?
- A) Carotin, das die Blätter im Herbst rot färbt.
- B) Hämoglobin, das den Sauerstoff im Blut transportiert.
- C) Chlorophyll, das auch für die grüne Farbe verantwortlich ist. RICHTIG

Frage 3:
Warum ist die Photosynthese für uns Menschen und Tiere überlebenswichtig?
- A) Weil Pflanzen dabei Sauerstoff (O₂) herstellen, den wir einatmen müssen. RICHTIG
- B) Weil sie giftiges Wasser aus dem Erdboden in reines Quellwasser filtert.
- C) Weil dadurch nachts die Temperatur auf der Erde sinkt.

Frage 4:
Was macht die Pflanze mit der hergestellten Glucose?
- A) Sie schwitzt sie komplett über die Blütenblätter wieder aus.
- B) Sie lagert sie als Stärke, z. B. in Kartoffeln oder Blättern, als Energievorrat ein. RICHTIG
- C) Sie verdampft sie im Licht, um sich vor Überhitzung zu schützen.

Bei richtiger Antwort:
- Button grün markieren
- Badge auf "Richtig!" setzen
- andere Optionen deaktivieren
- Fortschritt steigt

Bei falscher Antwort:
- Button rot markieren
- kurzer Shake
- Frage bleibt lösbar

Navigation:
- Zurück: Sortier-Duell

## Erfolg
Wenn alle 15 Aufgaben gelöst sind:
- Erfolgmodal anzeigen
- Titel: Photosynthese-Superstar!
- Kurze Zusammenfassung der Leistung:
  - Diagramm-Positionierung: 5 / 5 richtig
  - Stoffklassen-Einteilung: 6 / 6 richtig
  - Theoriewissen: 4 / 4 richtig
- Konfetti auslösen
- Kurzer Erfolgssound mit Web Audio API
- Button: Labor zurücksetzen & erneut starten

## Didaktischer Fokus
Die App soll die Photosynthese nicht nur abfragen, sondern modellhaft sichtbar machen:
- Was geht in die Pflanze hinein?
- Was entsteht?
- Wo passiert es?
- Warum entsteht Sauerstoff?
- Was macht die Pflanze mit Glucose?

Das Endprodukt soll wie ein kleines, hochwertiges Lernlabor wirken, nicht wie ein Arbeitsblatt.

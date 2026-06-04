Erstelle eine **HTML-Demo mit Three.js** als interaktives Minispiel für die Schule.

## Thema
Fach: Englisch  
Lernziel: Lebensmittel-Vokabular im Supermarkt lernen  
Zielgruppe: SuS, die spielerisch neue englische Begriffe üben sollen.

## Grundidee
Baue einen kleinen, liebevoll gestalteten **3D-Supermarkt** mit Three.js.  
Kleine Charaktere kommen als Kundinnen und Kunden in den Laden und kaufen Lebensmittel ein.

Der Spieler sieht jeweils ein Lebensmittel als **3D-Objekt, Emoji oder SVG-Illustration** und muss aus **4 Antwort-Buttons** den richtigen englischen Begriff auswählen.

Beispiel:
Ein Apfel erscheint → richtige Antwort: **apple**

## Design
- Mobile-first
- Dynamische Anpassung an verschiedene Bildschirmgrössen
- Stunning, modernes Design
- Freundliche Farben
- Grosse Buttons
- Klare Lesbarkeit
- Weiche Animationen
- Emoji- oder SVG-Grafiken für Lebensmittel
- Kleine 3D-Supermarkt-Szene mit Regalen, Kasse, Einkaufswagen und Charakteren
- Kein langweiliges Idle-Gameplay, sondern lebendige Mini-Szene

## Gameplay
- Pro Stufe gibt es **5 Begriffe**
- Insgesamt werden **30 Begriffe** benötigt
- Es gibt also **6 Stufen**
- Die Begriffe werden nach Schwierigkeit sortiert:
  - Stufe 1: sehr einfache Lebensmittel
  - Stufe 2: einfache Lebensmittel
  - Stufe 3: mittel
  - Stufe 4: mittel bis schwierig
  - Stufe 5: schwierig
  - Stufe 6: Wiederholung / Challenge

## Freischalten der Stufen
Eine neue Stufe wird freigeschaltet, wenn der Spieler die vorherige Stufe abgeschlossen hat.

Bewertung pro Stufe:
- Bronze: Stufe abgeschlossen
- Silber: mindestens 4 von 5 richtig
- Gold: alle 5 richtig

Im Hauptmenü soll sichtbar sein, welche Stufen abgeschlossen sind und welches Abzeichen erreicht wurde.

## Spielablauf
1. Spieler wählt eine freigeschaltete Stufe.
2. Ein Kunde betritt den Supermarkt.
3. Der Kunde legt ein Lebensmittel auf das Kassenband.
4. Der Spieler wählt den passenden englischen Begriff aus 4 Buttons.
5. Bei richtiger Antwort:
   - positives Feedback
   - Lebensmittel wandert in die Einkaufstasche
   - Geld-Animation an der Kasse
   - Score erhöht sich
6. Bei falscher Antwort:
   - freundliches Feedback
   - richtige Lösung anzeigen
   - nächste Aufgabe startet
7. Nach 5 Begriffen ist die Stufe beendet.
8. Ergebnis-Screen mit Abzeichen, Punkten und Button zurück zum Hauptmenü.

## Wortschatz
Erstelle insgesamt **30 Lebensmittel-Begriffe** und sortiere sie passend nach Schwierigkeit.

Beispiele für einfache Begriffe:
- apple
- banana
- milk
- bread
- cheese

Mittel:
- carrot
- potato
- chicken
- rice
- juice

Schwieriger:
- cucumber
- strawberry
- yoghurt
- cereal
- flour

## Technische Anforderungen
- Alles in **einer einzigen HTML-Datei**
- Enthält HTML, CSS und JavaScript
- Nutze Three.js für die 3D-Szene
- Keine externen Build-Tools
- Mobile-first Layout
- Touch-optimiert
- Grosse klickbare Buttons
- Animationen für:
  - Kunde kommt rein
  - Produkt erscheint
  - richtige Antwort
  - Geld wird kassiert
  - Level abgeschlossen
- Speichere Fortschritt mit localStorage:
  - freigeschaltete Stufen
  - Highscore pro Stufe
  - erreichtes Abzeichen pro Stufe
  - beste Serie / bestStreak
- Beim erneuten Spielen wird ein gespeichertes Abzeichen nur überschrieben, wenn das neue Ergebnis besser ist.
- Baue eine kleine Reset-Funktion ein, die nur den gespeicherten Fortschritt dieses Spiels löscht.

## Ziel
Die Demo soll wie ein kleines, hochwertiges Lernspiel wirken, das SuS motiviert, englische Lebensmittel-Vokabeln im Kontext Supermarkt zu üben.

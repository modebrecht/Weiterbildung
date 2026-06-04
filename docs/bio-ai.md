HTML DEMO: Ökosystem-Simulator (Fach: Biologie / NMG)

Erstelle eine interaktive Single-Page-Demo zur Räuber-Beute-Beziehung zwischen Luchsen und Rehen.

Ziel:
Die Lernenden sollen dynamische Zusammenhänge im Ökosystem live erforschen, statt nur Begriffe abzufragen.

Mechanik:
Die Simulation läuft automatisch. Es gibt keinen Start-Button. Sobald die Seite geöffnet ist, bewegen sich Populationen, Diagramm oder visuelle Punkte weiter. Änderungen an den Reglern wirken sofort sichtbar auf die Simulation.

Regler:
1. Luchse (Raubtiere)
   - verändert den Druck auf die Rehpopulation
   - mehr Luchse führen zu stärkerem Rückgang der Rehe

2. Waldfläche (Lebensraum)
   - beschreibt verfügbare Fläche, Schutz und ökologische Bedingungen
   - mehr Lebensraum stabilisiert oder erhöht die Rehpopulation

3. Nachwuchs (Kitze pro Wurf)
   - steuert, wie stark Rehe sich vermehren
   - höherer Wert lässt die Rehpopulation schneller wachsen

4. Jagd-Erfolg (Energie pro konsumiertem Reh)
   - steuert, wie viel Energie ein Luchs aus einem gefressenen Reh gewinnt
   - höherer Wert erhöht den Druck auf die Rehpopulation und kann die Luchspopulation stabilisieren

Wintermodus:
Baue einen Toggle für Wintermodus ein.
Wenn Winter aktiv ist, erscheint ein kleines Infofenster mit der Erklärung:
"Tiere bewegen sich langsamer. Luchse verlieren mehr Energie und bekommen pro gefressenem Reh weniger Energie. Dadurch treffen sie weniger Beute und verhungern schneller."

Zusätzlich gibt es einen Regler "Winterstärke" mit drei Stufen:
1. Stufe 1 = milder Winter
2. Stufe 2 = starker Winter
3. Stufe 3 = extremer Winter

Die Winterstärke soll die Effekte sichtbar verstärken:
- Tiere bewegen sich langsamer
- Rehe vermehren sich langsamer
- Waldfläche / Lebensraum wirkt weniger stark
- Luchse verlieren mehr Energie
- Luchse gewinnen pro konsumiertem Reh weniger Energie
- Schneeflocken erscheinen in der Simulation und werden bei stärkerem Winter dichter

Visualisierung:
Zeige die Entwicklung mit einer klaren Live-Grafik, z. B.:
- wachsende und schrumpfende Punkte für Luchse und Rehe
- ein einfaches Liniendiagramm mit zwei Kurven
- farbige Zähler für aktuelle Populationswerte

Interaktion:
Wenn ein Regler bewegt wird, soll man sofort sehen:
- Rehe nehmen ab, wenn es viele Luchse gibt
- Rehe erholen sich, wenn mehr Waldfläche vorhanden ist
- Rehe wachsen schneller, wenn der Nachwuchs-Wert steigt
- Rehe geraten stärker unter Druck, wenn der Jagd-Erfolg-Wert steigt
- Im Winter brechen Populationen schneller ein, besonders bei hoher Winterstufe

Design:
Modernes, klares Unterrichtsinterface mit grossen Labels, gut sichtbaren Slidern und ruhiger Farbgebung. Im Wintermodus soll die Visualisierung kälter wirken, z. B. mit bläulichem Hintergrund und fallenden Schneeflocken.

Didaktischer Effekt:
Die Demo soll zeigen, dass Ökosysteme dynamisch sind. Kleine Veränderungen an einem Parameter können grosse Auswirkungen auf das ganze System haben.

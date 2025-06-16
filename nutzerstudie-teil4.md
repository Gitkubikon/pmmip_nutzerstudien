# Teil 4: Auswertung der Nutzerstudie

## 4.1 UEQ Auswertung

### Rohdaten-Tabelle (Beispiel für 7 Teilnehmer)

| Item | P001 | P002 | P003 | P004 | P005 | P006 | P007 | Mittelwert | Std.Abw. |
|------|------|------|------|------|------|------|------|------------|----------|
| unerfreulich/erfreulich | +2 | +1 | +2 | 0 | +1 | +2 | +1 | 1.29 | 0.76 |
| unverständlich/verständlich | +1 | 0 | -1 | +1 | +2 | +1 | 0 | 0.57 | 0.98 |
| kreativ/phantasielos* | -1 | -2 | 0 | -1 | -1 | 0 | -2 | -1.00 | 0.82 |
| leicht zu lernen/schwer zu lernen* | +2 | +1 | +2 | +1 | +2 | +3 | +1 | 1.71 | 0.76 |
| wertvoll/minderwertig* | +2 | +1 | +1 | 0 | +2 | +1 | +1 | 1.14 | 0.69 |
| ... | ... | ... | ... | ... | ... | ... | ... | ... | ... |

*Invertierte Items (Werte müssen umgekehrt werden)

### UEQ Skalen-Berechnung

| Skala | Items | P001 | P002 | P003 | P004 | P005 | P006 | P007 | MW | SD |
|-------|-------|------|------|------|------|------|------|------|-----|-----|
| **Attraktivität** | 6 Items | 1.67 | 0.83 | 1.33 | 0.50 | 1.50 | 1.67 | 0.83 | **1.19** | 0.49 |
| **Durchschaubarkeit** | 4 Items | 1.50 | 0.75 | 1.00 | 0.50 | 1.75 | 2.00 | 0.75 | **1.18** | 0.58 |
| **Effizienz** | 4 Items | 1.25 | 1.00 | 0.75 | 0.25 | 1.50 | 1.25 | 1.00 | **1.00** | 0.41 |
| **Steuerbarkeit** | 4 Items | 1.75 | 1.25 | 1.50 | 0.75 | 1.75 | 1.50 | 1.00 | **1.36** | 0.38 |
| **Stimulation** | 4 Items | 0.75 | 0.50 | 1.00 | -0.25 | 1.25 | 0.75 | 0.25 | **0.61** | 0.50 |
| **Originalität** | 4 Items | 0.50 | 0.25 | 0.75 | 0.00 | 0.50 | 0.25 | -0.25 | **0.29** | 0.35 |

### UEQ Benchmark-Vergleich

| Skala | Ihre App | Benchmark | Bewertung |
|-------|----------|-----------|-----------|
| Attraktivität | 1.19 | 1.17 | 🟢 Gut |
| Durchschaubarkeit | 1.18 | 1.47 | 🟡 Durchschnitt |
| Effizienz | 1.00 | 1.35 | 🟡 Durchschnitt |
| Steuerbarkeit | 1.36 | 1.40 | 🟢 Gut |
| Stimulation | 0.61 | 1.03 | 🔴 Unterdurchschnitt |
| Originalität | 0.29 | 0.89 | 🔴 Unterdurchschnitt |

### UEQ Visualisierung

```
Attraktivität     ████████████████░░░░ 1.19
Durchschaubarkeit ████████████████░░░░ 1.18  
Effizienz         ██████████████░░░░░░ 1.00
Steuerbarkeit     ██████████████████░░ 1.36
Stimulation       ████████░░░░░░░░░░░░ 0.61
Originalität      ████░░░░░░░░░░░░░░░░ 0.29

-3 ←─────────────────→ +3
    Schlecht    Gut
```

## 4.2 NASA-TLX Auswertung

### Rohdaten (0-100 Skala)

| Dimension | P001 | P002 | P003 | P004 | P005 | P006 | P007 | MW | SD |
|-----------|------|------|------|------|------|------|------|-----|-----|
| Mentale Anforderung | 25 | 45 | 30 | 60 | 35 | 40 | 55 | **41.4** | 13.0 |
| Körperliche Anforderung | 10 | 15 | 5 | 20 | 10 | 15 | 10 | **12.1** | 5.1 |
| Zeitliche Anforderung | 20 | 30 | 25 | 45 | 30 | 35 | 40 | **32.1** | 8.8 |
| Leistung* | 85 | 70 | 80 | 60 | 75 | 70 | 65 | **72.1** | 8.6 |
| Anstrengung | 30 | 50 | 35 | 65 | 40 | 45 | 55 | **45.7** | 12.0 |
| Frustration | 15 | 35 | 20 | 50 | 25 | 30 | 45 | **31.4** | 13.0 |

*Leistung: niedrigere Werte = bessere Leistung

### NASA-TLX Gesamtworkload

**Berechnung:** (Alle Dimensionen addieren) / 6

| Teilnehmer | Gesamtworkload | Bewertung |
|------------|----------------|-----------|
| P001 | 28.3 | 🟢 Niedrig |
| P002 | 40.8 | 🟡 Mittel |
| P003 | 32.5 | 🟢 Niedrig |
| P004 | 50.0 | 🟡 Mittel |
| P005 | 36.7 | 🟡 Mittel |
| P006 | 39.2 | 🟡 Mittel |
| P007 | 45.0 | 🟡 Mittel |
| **Gesamt** | **38.9** | 🟡 **Mittel** |

### Task Load Profil

```
Mentale Anforderung    ████████░░░░░░░░ 41.4
Körperliche Anf.       ██░░░░░░░░░░░░░░ 12.1
Zeitliche Anf.         ██████░░░░░░░░░░ 32.1
Leistung              ██████████████░░ 72.1 ✓
Anstrengung           █████████░░░░░░░ 45.7
Frustration           ██████░░░░░░░░░░ 31.4

0 ←─────────────────→ 100
  Niedrig      Hoch
```

## 4.3 SUS Auswertung (Bonus)

### Rohdaten und Berechnung

| Frage | P001 | P002 | P003 | P004 | P005 | P006 | P007 | MW |
|-------|------|------|------|------|------|------|------|-----|
| Q1 (ungerade) | 4→3 | 3→2 | 4→3 | 2→1 | 4→3 | 3→2 | 3→2 | 2.3 |
| Q2 (gerade) | 2→3 | 3→2 | 2→3 | 4→1 | 2→3 | 3→2 | 3→2 | 2.3 |
| Q3 (ungerade) | 4→3 | 3→2 | 4→3 | 3→2 | 4→3 | 4→3 | 3→2 | 2.6 |
| ... | ... | ... | ... | ... | ... | ... | ... | ... |
| **Summe** | 32 | 26 | 30 | 20 | 32 | 28 | 24 | |
| **SUS-Score** | **80** | **65** | **75** | **50** | **80** | **70** | **60** | **68.6** |

### SUS Interpretation

| Teilnehmer | SUS-Score | Grade | Bewertung |
|------------|-----------|-------|-----------|
| P001 | 80 | B | Gut |
| P002 | 65 | C | OK |
| P003 | 75 | B | Gut |
| P004 | 50 | F | Schlecht |
| P005 | 80 | B | Gut |
| P006 | 70 | B | Gut |
| P007 | 60 | D | Grenzwertig |
| **Durchschnitt** | **68.6** | **B** | **Gut** |

## 4.4 Qualitative Analyse

### Häufigste Probleme (nach Aufgabe)

| Problem | Häufigkeit | Schweregrad | Priorität |
|---------|------------|-------------|-----------|
| Exercise-Icon nicht erkennbar | 5/7 | Hoch | 🔴 Kritisch |
| Start-Button schwer zu finden | 4/7 | Hoch | 🔴 Kritisch |
| Kategorie-Buttons zu klein | 3/7 | Mittel | 🟡 Wichtig |
| Fortschrittsanzeige unklar | 6/7 | Mittel | 🟡 Wichtig |
| Navigation zur Historie | 2/7 | Niedrig | 🟢 Nice-to-have |

### Positive Aspekte (Zitate)

- P001: *"Das Design ist sehr modern und ansprechend"*
- P003: *"Die Workout-Auswahl ist übersichtlich"*
- P005: *"Schöne Animationen beim Training"*
- P007: *"Die App läuft sehr flüssig"*

### Verbesserungsvorschläge (kategorisiert)

**Navigation:**
- Beschriftungen unter Icons ergänzen (5 Nennungen)
- Zurück-Button prominenter (3 Nennungen)
- Breadcrumb-Navigation (1 Nennung)

**Visuelles Feedback:**
- Klarere Hover-Effekte (4 Nennungen)
- Ladeanimationen hinzufügen (3 Nennungen)
- Erfolgs-Feedback nach Aktionen (6 Nennungen)

**Funktionalität:**
- Workout-Vorschau (4 Nennungen)
- Favoriten-Funktion (2 Nennungen)
- Trainingsplan-Generator (3 Nennungen)

## 4.5 Zusammenfassung und Empfehlungen

### Executive Summary

**Studienübersicht:**
- 7 Teilnehmer getestet
- Durchschnittsalter: 32 Jahre
- Mix aus Anfängern und Fortgeschrittenen
- 5 von 7 Aufgaben erfolgreich absolviert

### Haupterkenntnisse

**Stärken:**
- ✅ Attraktives Design (UEQ: 1.19)
- ✅ Gute Steuerbarkeit (UEQ: 1.36)
- ✅ Akzeptabler SUS-Score (68.6)
- ✅ Mittlere Arbeitsbelastung (NASA-TLX: 38.9)

**Schwächen:**
- ❌ Niedrige Stimulation (UEQ: 0.61)
- ❌ Geringe Originalität (UEQ: 0.29)
- ❌ Icon-Erkennbarkeit problematisch
- ❌ Fehlende Fortschritts-Visualisierung

### Handlungsempfehlungen

**Priorität 1 (Sofort umsetzen):**
1. Icons mit Text-Labels versehen
2. Start-Button prominent platzieren
3. Fortschrittsbalken bei allen Aktionen

**Priorität 2 (Kurzfristig):**
1. Hover-Effekte verstärken
2. Workout-Vorschau implementieren
3. Erfolgs-Animationen ergänzen

**Priorität 3 (Mittelfristig):**
1. Gamification-Elemente für höhere Stimulation
2. Innovative Features für mehr Originalität
3. Personalisierte Trainingspläne

### Erfolgsfaktoren

1. **Intuitive Grundstruktur:** App-Aufbau wird verstanden
2. **Ansprechendes Design:** Positive erste Eindrücke
3. **Stabile Performance:** Keine technischen Probleme
4. **Zielgruppen-Fit:** Erfüllt Basis-Erwartungen

### Problembereiche

1. **Onboarding:** Erstnutzer brauchen mehr Führung
2. **Feedback-System:** Nutzer unsicher über Aktionen
3. **Motivation:** Zu wenig Anreize für regelmäßige Nutzung
4. **Differenzierung:** Zu ähnlich zu Konkurrenz-Apps

## 4.6 Präsentations-Folien (5-7 Minuten)

### Folie 1: Titel
**Usability-Evaluation: FitLife Fitness-App**
- Team: [Namen]
- Datum: [Datum]
- 7 Testpersonen

### Folie 2: Methodik
- Cognitive Walkthrough (Vorstudie)
- 7 Usability-Tests
- 3 standardisierte Fragebögen
- Mixed-Methods Ansatz

### Folie 3: Hauptergebnisse UEQ
[Balkendiagramm der 6 Dimensionen]
- Stärken: Attraktivität, Steuerbarkeit
- Schwächen: Stimulation, Originalität

### Folie 4: Task-Performance
- 71% Task Completion Rate
- Ø 3.2 Klicks pro Aufgabe
- Hauptproblem: Icon-Erkennbarkeit

### Folie 5: NASA-TLX Profil
[Radar-Chart der 6 Dimensionen]
- Moderate Arbeitsbelastung (38.9/100)
- Höchste Last: Anstrengung (45.7)

### Folie 6: Top 3 Empfehlungen
1. **Icons beschriften** → +40% Erkennbarkeit
2. **Start-Button vergrößern** → -50% Suchzeit
3. **Progress-Feedback** → +60% Nutzerzufriedenheit

### Folie 7: Nächste Schritte
- Priorität 1 Fixes: 1 Woche
- Re-Test mit 5 Nutzern
- A/B Testing für neue Features
- Fragen?
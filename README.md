# 🎓 Academy Content Editor - Anleitung

## 📚 Übersicht

Der **Academy Content Editor** ist ein HTML-basierter Editor zum Erstellen und Verwalten der Unterrichtsinhalte für die FL Mastery App.

**Besonderheit:** Speichert Daten als **HTML-Datei** (nicht JSON) - genau wie die Gesetze-Datenbank. Dadurch gibt es **kein Größenlimit**!

---

## ✨ HAUPTFUNKTIONEN

### **1. HTML-basierte Speicherung**
```
✅ Unbegrenzte Größe (keine LocalStorage-Limits!)
✅ Speichert als academy-content.html auf GitHub
✅ App lädt HTML direkt (wie Rechtsbibliothek)
✅ Bewährtes System aus Gesetze-Datenbank
```

### **2. Druck-Funktion mit Auswahl**
```
✅ Drucke einzelne Lektionen oder ganze Module
✅ Wähle: Anwärter-Inhalte / Dozenten-Inhalte / Beides
✅ Professioneller Footer automatisch
✅ Optimiert für Ausdrucke
```

### **3. Dual-Perspektive**
```
✅ Anwärter-Ansicht: "Was muss ich lernen?"
✅ Dozenten-Ansicht: "Wie vermittle ich das?"
✅ Status-Tracking (Justin/Dozent geprüft)
```

---

## 🚀 SCHNELLSTART

### **SCHRITT 1: Datei öffnen**
```
1. Lade academy-editor.html herunter
2. Öffne mit Browser (Chrome, Firefox, Safari, Edge)
3. Fertig - kein Server nötig!
```

---

### **SCHRITT 2: GitHub einrichten**

#### **2.1 GitHub Personal Access Token erstellen**
```
1. Gehe zu: https://github.com/settings/tokens
2. Klicke: "Generate new token (classic)"
3. Name: "FL Academy Editor"
4. Berechtigungen:
   ☑️ repo (alle Unterpunkte)
5. Klicke: "Generate token"
6. WICHTIG: Token kopieren (wird nur 1x angezeigt!)
```

#### **2.2 Repository erstellen**
```
1. Gehe zu: https://github.com/new
2. Repository Name: FL-Academy-Content
3. Public oder Private (empfohlen: Private)
4. Initialize: ☑️ Add README
5. Klicke: "Create repository"
```

#### **2.3 Token im Editor eintragen**
```
1. Im Editor: Klicke "⚙️ GitHub Setup"
2. Trage ein:
   - GitHub Token: ghp_xxxxxxxxxxxxx
   - Repository Name: FL-Academy-Content
   - Dateiname: academy-content.html
3. Klicke: "✅ Einstellungen speichern"
```

---

## ✏️ LEKTIONEN ERSTELLEN

### **Neue Lektion erstellen:**

```
1. Wähle Modul in Sidebar (z.B. "🚗 Verkehrsverhalten")
2. Klicke: "+ Neue Lektion"
3. Editor öffnet sich rechts
4. Fülle Felder aus
5. WICHTIG: Regelmäßig auf GitHub speichern!
```

---

### **FELDER ERKLÄRT:**

#### **📝 BASIS-INFORMATIONEN**

**Titel der Lektion**
```
Beispiel: "Gefahrenlehre - Grundlagen der Verkehrswahrnehmung"

Tipps:
✅ Kurz und prägnant (max 80 Zeichen)
✅ Beschreibt Lerninhalt klar
✅ Keine Abkürzungen wenn möglich
```

**Dauer (Minuten)**
```
Standard: 90 Minuten
Andere: 45, 60, 120, 180

Richtwerte:
- Einführungsthemen: 45-60 Min
- Hauptthemen: 90 Min
- Vertiefungsthemen: 120-180 Min
```

**Checkboxen:**
```
☑️ Prüfungsrelevant
   → Wird in App mit rotem Badge "🔴" markiert
   → Für Anwärter sofort erkennbar

☑️ Von Justin geprüft
   → Interner Status (NICHT in App sichtbar!)
   → Setze Haken wenn Inhalt fachlich geprüft
   → Grüner Punkt in Sidebar

☑️ Von Dozent geprüft
   → Interner Status (NICHT in App sichtbar!)
   → Dozent setzt Haken nach Qualitätsprüfung
   → Zweiter grüner Punkt in Sidebar

STATUS-ANZEIGE IN SIDEBAR:
[●●] = Beide geprüft → Freigegeben
[●○] = Nur Justin → Wartet auf Dozent
[○○] = Noch nicht fertig
```

---

#### **🎯 LERNZIELE**

```
Was soll der Anwärter nach der Lektion können?

SMART-FORMEL:
S = Spezifisch (konkret, nicht allgemein)
M = Messbar (überprüfbar)
A = Attraktiv (motivierend formuliert)
R = Realistisch (in der Zeit erreichbar)
T = Terminiert (zum Lektionsende)

GUTE BEISPIELE:
✅ "Die vier Hauptkategorien von Verkehrsgefahren benennen können"
✅ "Gefahrensituationen in Videobeispielen erkennen und analysieren"
✅ "Gefahrenvermeidungsstrategien in der Praxis anwenden"

SCHLECHTE BEISPIELE:
❌ "Gefahrenlehre lernen" (zu unspezifisch)
❌ "Alles über Gefahren wissen" (nicht messbar)
❌ "Experte werden" (nicht realistisch für 90 Min)

ANZAHL:
- Minimum: 2 Lernziele
- Optimal: 3-5 Lernziele
- Maximum: 7 Lernziele

BUTTONS:
+ Lernziel hinzufügen → Neues Feld
× → Lernziel löschen
```

---

#### **🎓 INHALT FÜR ANWÄRTER**

```
Der Hauptlerninhalt für Fahrlehreranwärter.

STRUKTUR (Empfohlen):

1. EINLEITUNG (10-15% des Textes)
   - Was wird behandelt?
   - Warum ist es wichtig?
   - Was ist das Ziel?

2. HAUPTINHALT (70-80% des Textes)
   - Systematischer Aufbau
   - Vom Einfachen zum Komplexen
   - Mit Überschriften strukturieren

3. ZUSAMMENFASSUNG (10% des Textes)
   - Kernaussagen wiederholen
   - Ausblick auf Praxis

LÄNGE:
- Minimum: 500 Wörter
- Optimal: 800-1.500 Wörter
- Maximum: 3.000 Wörter (sonst aufteilen!)

TIPPS:
✅ Klare, verständliche Sprache (B1-B2 Niveau)
✅ Fachbegriffe beim ersten Mal erklären
✅ Absätze mit Leerzeilen trennen
✅ Überschriften nutzen (Groß schreiben oder mit "###")
✅ Aufzählungen mit • oder - oder 1., 2., 3.
✅ Praxisbezug herstellen
✅ Konkrete Beispiele einbauen

FORMATIERUNG IM TEXTFELD:
- Überschriften: Einfach in GROSSBUCHSTABEN
- Listen: Mit - oder • oder 1., 2., 3.
- Absätze: Mit Leerzeile trennen
- Hervorhebungen: Mit **text** (wird in App formatiert)

BEISPIEL:

"Die Gefahrenlehre ist ein zentraler Bestandteil der Fahrlehrerausbildung.
Sie vermittelt die Fähigkeit, Gefahren im Straßenverkehr frühzeitig zu 
erkennen und richtig zu reagieren.

WAS SIND GEFAHREN?

Gefahren im Straßenverkehr sind Situationen oder Umstände, die zu einem
Unfall führen können. Sie entstehen durch:

- Verkehrsteilnehmer (andere Fahrzeuge, Fußgänger, Radfahrer)
- Straßenzustand (Nässe, Glätte, Schlaglöcher)
- Witterung (Nebel, Regen, Schnee)
- Technische Defekte (Bremsversagen, Reifenplatzer)

ARTEN VON GEFAHREN

1. Latente Gefahren
Noch nicht akut, aber potenziell gefährlich.
Beispiel: Kind spielt am Straßenrand

2. Akute Gefahren
Unmittelbar gefährlich, sofortige Reaktion nötig.
Beispiel: Kind läuft auf die Straße

[HIER WÜRDE BILD ERSCHEINEN: gefahren_schema.png]

ZUSAMMENFASSUNG

Gefahren frühzeitig erkennen ist die wichtigste Fähigkeit eines guten
Fahrlehrers. Die systematische Schulung der Gefahrenwahrnehmung ist 
daher essenziell."
```

---

#### **💡 PRAXISBEISPIELE**

```
Konkrete Beispiele aus dem Fahrschulalltag.

STRUKTUR EINES GUTEN BEISPIELS:

1. SITUATION beschreiben (Was passiert?)
2. GEFAHR/PROBLEM aufzeigen (Was ist kritisch?)
3. LÖSUNG/HANDLUNG erklären (Wie reagiert man?)
4. LERNEFFEKT benennen (Was lernt man daraus?)

BEISPIEL 1:
"Situation: Ein Fahrschüler nähert sich einer Kreuzung mit 50 km/h. 
Ein Kind (ca. 6 Jahre) spielt mit einem Ball am Straßenrand, 20m vor 
der Kreuzung.

Gefahr: Das Kind könnte dem Ball hinterherlaufen ohne auf den Verkehr 
zu achten. Reaktionszeit + Bremsweg bei 50 km/h = ca. 40m.

Handlung: Der Fahrlehrer sollte den Fahrschüler frühzeitig auf das Kind 
hinweisen ('Achtung, Kind am Straßenrand!'). Geschwindigkeit reduzieren 
auf 30 km/h. Bremsbereitschaft erhöhen. Nach der Gefahrenstelle mit dem 
Fahrschüler die Situation besprechen.

Lerneffekt: Kinder haben kein Gefahrenbewusstsein. Bei spielenden 
Kindern IMMER bremsbereit sein und Geschwindigkeit anpassen."

BEISPIEL 2:
"Situation: Fahrstunde bei Nässe. Fahrschüler bremst mit 50 km/h wie 
gewohnt.

Problem: Bei Nässe verdoppelt sich der Bremsweg! 
Normal: 25m Bremsweg bei 50 km/h
Nass: 50m Bremsweg bei 50 km/h

Demonstration: Auf Übungsplatz Vollbremsung bei Trockenheit und Nässe 
durchführen. Bremsweg mit Hütchen markieren. Unterschied visualisieren.

Lerneffekt: Wetterbedingungen erfordern angepasste Fahrweise. 
Fahrschüler muss lernen, präventiv zu denken."

ANZAHL:
- Minimum: 1 Beispiel
- Optimal: 2-3 Beispiele
- Maximum: 5 Beispiele

BUTTONS:
+ Beispiel hinzufügen → Neues Textfeld
🗑️ Entfernen → Beispiel löschen
```

---

#### **👨‍🏫 INHALT FÜR DOZENTEN**

Diese Inhalte sehen **NUR Dozenten** - nicht die Anwärter!

---

**UNTERRICHTSENTWURF**

```
Detaillierter Plan für die Unterrichtseinheit.

STRUKTUR (Standardformat 90 Min):

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
EINSTIEG (10-15 Min)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Methode: [z.B. Frage, Video, Diskussion]
Sozialform: [Plenum, Einzelarbeit, Gruppenarbeit]

Konkret:
- Frage an die Klasse: "Was war eure gefährlichste 
  Situation im Straßenverkehr?"
- Antworten sammeln und an Tafel kategorisieren
- Überleitung: "Heute lernen wir systematische 
  Gefahrenerkennung"

Ziel:
- Interesse wecken
- Vorwissen aktivieren
- Lernziele transparent machen

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
HAUPTTEIL (60-65 Min)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Phase 1: Theorie-Input (20 Min)
- Vortrag mit PowerPoint
- Gefahrenkategorien systematisch erarbeiten
- Tafelbilder erstellen
- Fragen der Anwärter einbauen

Phase 2: Videoanalyse (15 Min)
- 3-4 kurze Verkehrssituationen zeigen
- Pausieren und Gefahren gemeinsam identifizieren
- Diskussion: Wie würdet ihr reagieren?

Phase 3: Gruppenarbeit (20 Min)
- 4er-Gruppen bilden
- Jede Gruppe bekommt 2 Fallbeispiele
- Gefahrenanalyse durchführen
- Handlungsempfehlungen erarbeiten

Phase 4: Präsentation (10 Min)
- Gruppen stellen Ergebnisse vor (je 2 Min)
- Feedback der anderen Gruppen
- Zusammenführung durch Dozent

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
SCHLUSS (10-15 Min)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Sicherung:
- Zusammenfassung durch Anwärter
- Offene Fragen klären
- Kernaussagen wiederholen

Ausblick:
- Nächste Stunde: Gefahrenvermeidungsstrategien
- Hausaufgabe: 5 Gefahrensituationen dokumentieren

Transfer:
- "Achtet in der nächsten Fahrstunde besonders auf..."

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MATERIALIEN & MEDIEN
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

- PowerPoint-Präsentation (20 Folien)
- 4 Videobeispiele (je 1-2 Min)
- Arbeitsblätter für Gruppenarbeit
- Tafel & Kreide
- Moderationskarten

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

LÄNGE: 500-1.000 Wörter
```

---

**DIDAKTISCHE HINWEISE**

```
Praktische Tipps für erfolgreichen Unterricht.

KATEGORIEN:

⚠️ HÄUFIGE FEHLER DER ANWÄRTER
- Was wird oft falsch verstanden?
- Typische Missverständnisse
- Wie kann man vorbeugen?

Beispiel:
"⚠️ Häufiger Fehler: Anwärter unterschätzen 
systematisch Reaktionszeiten. Sie rechnen oft nur 
mit 0,5 Sekunden statt realistischen 1 Sekunde. 

Abhilfe: Praktische Übung mit Stoppuhr. Anwärter 
sollen auf Signal reagieren. Durchschnitt liegt 
bei 0,8-1,2 Sekunden. Dies verdeutlicht, warum 
die Faustformel wichtig ist."

💡 UNTERRICHTSTIPPS
- Was funktioniert besonders gut?
- Welche Methoden sind effektiv?
- Tricks für besseres Verständnis

Beispiel:
"💡 Tipp: Nutze Papierstreifen auf dem Boden um 
Bremswege anschaulich darzustellen. 1m Papier = 1m 
Bremsweg. Bei 50 km/h = 25m Papier auslegen. 
Sehr eindrücklich für Anwärter!"

🎯 WORAUF BESONDERS ACHTEN
- Kritische Punkte
- Was darf nicht vergessen werden?
- Prüfungsrelevante Details

Beispiel:
"🎯 Fokus: Der Unterschied zwischen latenter und 
akuter Gefahr ist prüfungsrelevant! Immer mit 
konkreten Beispielen arbeiten, nicht nur Theorie."

⏱️ ZEITMANAGEMENT
- Wie Zeit einteilen?
- Was wenn Zeit knapp wird?
- Was kann man weglassen?

Beispiel:
"⏱️ Zeit: Gruppenarbeit max. 20 Min, sonst wird 
es langweilig. Lieber kürzere, aktivierende Phasen. 
Falls Zeit knapp: Phase 4 (Präsentation) auf 5 Min 
kürzen oder nur 2 Gruppen präsentieren lassen."

📚 ZUSATZMATERIAL
- Weiterführende Literatur
- Videos & Links
- Arbeitsblätter

Beispiel:
"📚 Material: 
- Beck-Kommentar zur StVO, Seite 142-156
- ADAC-Video 'Gefahrenbremsung' (YouTube)
- Arbeitsblatt 'Gefahrenanalyse' (siehe Anhang)"

LÄNGE: 300-800 Wörter
```

---

**TYPISCHE PRÜFUNGSFRAGEN**

```
Fragen, die in Fachkundeprüfung oder mündlicher 
Prüfung vorkommen können.

FORMAT:

Frage 1: [Konkrete Frage]
Antwort: [Ausführliche Musterlösung]

Frage 2: [Konkrete Frage]
Antwort: [Ausführliche Musterlösung]

BEISPIELE:

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Frage 1: Nennen Sie die vier Hauptkategorien von 
Verkehrsgefahren und geben Sie je ein Beispiel.

Antwort:
Die vier Hauptkategorien sind:

1. Verkehrsteilnehmer
   Beispiel: Ein Radfahrer fährt ohne Schulterblick 
   auf die Fahrbahn

2. Straßenzustand
   Beispiel: Schlaglöcher nach dem Winter führen zu 
   Ausweichmanövern

3. Witterung
   Beispiel: Plötzlicher Nebel reduziert die Sicht 
   auf unter 50m

4. Technische Defekte
   Beispiel: Reifenplatzer bei hoher Geschwindigkeit 
   auf der Autobahn

Bewertung: Alle 4 Kategorien müssen genannt werden. 
Je ein passendes Beispiel muss gegeben werden.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Frage 2: Wie vermitteln Sie einem Fahrschüler die 
Bedeutung des Sicherheitsabstands bei verschiedenen 
Witterungsbedingungen?

Antwort:
Ich würde dies in drei Schritten vermitteln:

1. Faustformel erklären
   - Grundregel: Halber Tacho = Sicherheitsabstand
   - Bei 50 km/h = 25m Abstand
   - Bei 100 km/h = 50m Abstand

2. Praktische Demonstration
   - Auf Übungsplatz Vollbremsung durchführen
   - Bei Trockenheit messen: ca. 25m bei 50 km/h
   - Bei Nässe messen: ca. 50m bei 50 km/h
   - Bremsweg mit Hütchen markieren
   - Unterschied visualisieren

3. Hinweis auf Bremsweg-Verlängerung
   - Nässe: Bremsweg x 2
   - Schnee/Eis: Bremsweg x 3-4
   - Laub: Bremsweg x 1,5

4. Risiken verdeutlichen
   - Zu geringer Abstand = Auffahrunfall
   - Bei Nässe keine Chance zu bremsen
   - Haftung bei Auffahrunfall
   - Video-Beispiele von Auffahrunfällen zeigen

Bewertung: Alle 4 Punkte sollten erwähnt werden. 
Besonders wichtig ist die praktische Demonstration 
und der Bezug zu verschiedenen Witterungsbedingungen.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

ANZAHL:
- Minimum: 2 Fragen
- Optimal: 3-5 Fragen
- Maximum: 8 Fragen

SCHWIERIGKEITSGRAD:
- Mix aus einfachen und schweren Fragen
- Reproduktion (Wissen wiedergeben)
- Transfer (Wissen anwenden)
- Problemlösung (Neues Situation bewerten)

LÄNGE: 400-1.000 Wörter
```

---

## 💾 SPEICHERN & LADEN

### **AUF GITHUB SPEICHERN**

```
1. Klicke oben rechts: "💾 Speichern"
2. Bestätige: "Wirklich auf GitHub speichern?"
3. Warte 2-3 Sekunden
4. Meldung: "✅ Erfolgreich auf GitHub gespeichert als HTML!"

WAS PASSIERT:
→ Editor generiert HTML-Datei
→ Lädt auf GitHub hoch als academy-content.html
→ FL Mastery App kann die Datei laden
→ Dozenten können die Datei herunterladen

WICHTIG:
⚠️ KEIN automatisches Speichern!
⚠️ Regelmäßig auf GitHub speichern!
⚠️ Mindestens nach jeder fertigen Lektion!

HÄUFIGKEIT (Empfohlen):
- Nach jeder fertigen Lektion
- Vor dem Schließen des Browsers
- Mindestens 1x pro Arbeitssitzung
- Vor größeren Änderungen (als Backup)
```

### **VON GITHUB LADEN**

```
1. Klicke oben rechts: "📥 Laden"
2. Bestätige: "Aktuelle Daten werden überschrieben"
3. Warte 2-3 Sekunden
4. Meldung: "✅ Erfolgreich von GitHub geladen!"

WANN NUTZEN:
- Arbeit auf anderem Computer fortsetzen
- Nach Änderungen von anderen (Dozenten)
- Nach Browser-Absturz
- Zum Synchronisieren mehrerer Geräte

⚠️ ACHTUNG:
Überschreibt lokale Änderungen!
Vorher speichern wenn nötig!
```

---

## 🖨️ DRUCK-FUNKTION

### **AUSDRUCK ERSTELLEN**

```
SCHRITT 1: Druckauswahl öffnen
→ Klicke oben rechts: "🖨️ Drucken"
→ Modal öffnet sich

SCHRITT 2: Inhalte auswählen
☑️ Anwärter-Inhalte drucken
   → Lernziele, Inhalt, Beispiele

☑️ Dozenten-Inhalte drucken
   → Unterrichtsentwurf, Didaktik, Prüfungsfragen

SCHRITT 3: Lektionen auswählen

OPTION A: Alles
☑️ Alles auswählen
→ Alle Module und Lektionen werden gedruckt

OPTION B: Einzelne Module
☑️ 🚗 Verkehrsverhalten (alle Lektionen)
☐ ⚖️ Recht
☐ 🔧 Technik
→ Nur ausgewählte Module werden gedruckt

OPTION C: Einzelne Lektionen
☑️ Gefahrenlehre - Grundlagen
☑️ Verkehrspsychologie - Wahrnehmung
☐ Fahrphysik - Kräfte
→ Nur ausgewählte Lektionen werden gedruckt

SCHRITT 4: Drucken
→ Klicke: "🖨️ Jetzt drucken"
→ Browser-Druckdialog öffnet sich
→ Wähle Drucker oder "Als PDF speichern"
→ Klicke: "Drucken"
```

---

### **DRUCK-FORMAT**

```
KOPFBEREICH (Erste Seite):
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🎓 FL MASTERY ACADEMY

Fahrlehrerausbildung - Unterrichtsinhalte
Gedruckt am: 02.01.2026, 23:45 Uhr
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

JEDE LEKTION:
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🚗 VERKEHRSVERHALTEN - GEFAHRENLEHRE

Dauer: 90 Minuten ● Prüfungsrelevant

🎯 Lernziele:
• Gefahren im Straßenverkehr erkennen können
• Die vier Gefahrenkategorien benennen
• Gefahrenvermeidungsstrategien anwenden

📖 Inhalt für Anwärter:
[Vollständiger Text...]

💡 Praxisbeispiele:
┌─────────────────────────────────┐
│ Beispiel 1: Kind am Straßenrand │
│ [Text in Box...]                │
└─────────────────────────────────┘

👨‍🏫 Dozenten-Inhalte:
(Nur wenn ausgewählt)

Unterrichtsentwurf:
[Text...]

Didaktische Hinweise:
[Text...]

Typische Prüfungsfragen:
[Text...]
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

FOOTER (Auf jeder Seite):
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
FL Mastery Pro - Academy | © 2026
Verkehrsinstitut Schielein Nürnberg
Fahrlehrerausbildung FL-BE_07/25
www.fl-mastery.app
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

---

### **DRUCK-TIPPS**

```
✅ Als PDF speichern (für Archiv)
✅ Duplex-Druck (beidseitig) spart Papier
✅ Schwarz-Weiß reicht meist aus
✅ 2 Seiten pro Blatt für Übersicht

VERWENDUNG:
- Handouts für Anwärter (nur Anwärter-Inhalte)
- Dozenten-Unterlagen (nur Dozenten-Inhalte)
- Komplett-Skript (beides zusammen)
- Einzelne Lektionen für Nachbereitung
```

---

## 🔄 WORKFLOW

### **FÜR JUSTIN (Inhalte erstellen):**

```
TÄGLICHER WORKFLOW:

1. Editor öffnen (academy-editor.html)

2. "📥 Laden" klicken
   → Neueste Version von GitHub holen

3. Lektionen erstellen/bearbeiten:
   - Neue Lektion anlegen
   - Titel & Basis eingeben
   - Lernziele definieren (SMART!)
   - Anwärter-Inhalt schreiben (800-1.500 Wörter)
   - 2-3 Praxisbeispiele hinzufügen
   - Dozenten-Inhalt (Entwurf oder Platzhalter)

4. Status setzen:
   ☑️ Von Justin geprüft (wenn fertig)
   ☐ Von Dozent geprüft (bleibt leer)

5. "💾 Speichern" klicken
   → Auf GitHub hochladen

6. Wiederholen für weitere Lektionen

7. Am Ende der Sitzung:
   → Nochmal "💾 Speichern"
   → Browser kann geschlossen werden

ALTERNATIVE - MIT CLAUDE:

1. Öffne separaten Claude-Chat
2. Nutze PROMPT-TEXT-AUFBEREITUNG.md
3. Schicke Texte/PDFs/Notizen an Claude
4. Claude bereitet didaktisch auf
5. Kopiere Ergebnis in Editor
6. Speichere auf GitHub
```

---

### **FÜR DOZENTEN (Inhalte prüfen):**

```
PRÜF-WORKFLOW:

1. Editor öffnen

2. "⚙️ GitHub Setup" (eigenen Token eingeben)

3. "📥 Laden" (Justins Inhalte holen)

4. Durchgehen & Prüfen:
   - Fachliche Korrektheit
   - Verständlichkeit
   - Vollständigkeit
   - Didaktische Qualität

5. Ergänzen:
   - Unterrichtsentwurf detaillieren
   - Didaktische Hinweise hinzufügen
   - Prüfungsfragen ergänzen
   - Fehler korrigieren

6. Wenn alles korrekt:
   ☑️ Von Dozent geprüft

7. "💾 Speichern" (GitHub)

8. Optional: Feedback an Justin
   (via GitHub Issue oder direkt)

ALTERNATIVE:

- Nur Dozenten-Inhalte exportieren
- Als PDF speichern (via Druck-Funktion)
- Offline bearbeiten
- Änderungen später eintragen
```

---

## 📊 STATUS-ÜBERSICHT

### **Status-Punkte in Sidebar:**

```
ANZEIGE:

[●●] = Grün Grün  → Justin ✓ Dozent ✓  → FERTIG!
[●○] = Grün Grau  → Justin ✓ Dozent ○  → Warten auf Dozent
[○○] = Grau Grau  → Justin ○ Dozent ○  → Noch in Arbeit

FARBLEGENDE:

● Grün  = Geprüft und freigegeben
○ Grau  = Noch nicht geprüft

WORKFLOW:

Schritt 1: Justin erstellt Lektion → [○○]
Schritt 2: Justin prüft fertig      → [●○]
Schritt 3: Dozent prüft              → [●●]
Schritt 4: Freigegeben für App       → [●●]

WICHTIG:
Die Status-Punkte sind NUR im Editor sichtbar!
Sie erscheinen NICHT in der App!
Nur für interne Qualitätskontrolle!
```

---

## 🆘 PROBLEMLÖSUNG

### **Problem: "Quota exceeded" Fehler**
```
❌ NICHT MEHR MÖGLICH!
✅ Editor speichert als HTML auf GitHub
✅ Kein LocalStorage mehr genutzt
✅ Unbegrenzte Größe möglich!
```

### **Problem: GitHub Speichern schlägt fehl**
```
Mögliche Ursachen:
❌ Token falsch oder abgelaufen
❌ Repository existiert nicht
❌ Keine Berechtigung
❌ Internetverbindung unterbrochen

Lösung:
1. Prüfe Token in GitHub Settings
2. Erstelle neuen Token falls nötig
3. Prüfe Repository-Name (exakt: FL-Academy-Content)
4. Prüfe Internetverbindung
5. Browser-Console checken (F12 → Console)
```

### **Problem: Daten verschwunden**
```
Lösung:
1. "📥 Laden" klicken (lädt von GitHub)
2. Falls noch nicht auf GitHub gespeichert:
   → Daten sind verloren
   → WICHTIG: Regelmäßig speichern!

Prävention:
→ Nach jeder Lektion speichern
→ Vor Browser-Schließen speichern
→ Regelmäßige Backups
```

### **Problem: Änderungen werden nicht angezeigt**
```
Lösung:
1. Browser neu laden (F5 oder Strg+R)
2. Cache leeren (Strg+Shift+Delete)
3. Prüfe ob auf GitHub gespeichert
4. "📥 Laden" klicken
```

### **Problem: Druck funktioniert nicht**
```
Lösung:
1. Mindestens 1 Lektion auswählen
2. Browser-Popup-Blocker deaktivieren
3. Anderen Browser versuchen
4. Als PDF speichern statt Drucken
```

---

## 📁 DATENFORMAT (Technisch)

### **academy-content.html Struktur:**

```html
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="version" content="1.0.0">
    <meta name="last-updated" content="2026-01-02T23:45:00Z">
</head>
<body>
    <div id="academy-data">
        
        <div class="modul" data-id="verkehrsverhalten" data-icon="🚗">
            <h2>Verkehrsverhalten</h2>
            
            <div class="lektion" 
                 data-id="vv_1735850700000"
                 data-pruefung="true"
                 data-dauer="90"
                 data-status-justin="true"
                 data-status-dozent="false">
                
                <h3>Gefahrenlehre - Grundlagen</h3>
                
                <div class="lernziele">
                    <div class="lernziel">Gefahren erkennen können</div>
                    <div class="lernziel">Kategorien benennen</div>
                </div>
                
                <div class="anwaerter">
                    <h4>Inhalt für Anwärter</h4>
                    <div class="inhalt">
                        Die Gefahrenlehre ist...<br>
                        [Text mit &lt;br&gt; für Zeilenumbrüche]
                    </div>
                    
                    <div class="beispiele">
                        <h5>Praxisbeispiele</h5>
                        <div class="beispiel">Beispiel 1 Text...</div>
                        <div class="beispiel">Beispiel 2 Text...</div>
                    </div>
                </div>
                
                <div class="dozent">
                    <h4>Inhalt für Dozenten</h4>
                    
                    <div class="unterrichtsentwurf">
                        <h5>Unterrichtsentwurf</h5>
                        <div class="inhalt">Einstieg: ...<br>Hauptteil: ...</div>
                    </div>
                    
                    <div class="didaktik">
                        <h5>Didaktische Hinweise</h5>
                        <div class="inhalt">Häufiger Fehler: ...</div>
                    </div>
                    
                    <div class="pruefungsfragen">
                        <h5>Typische Prüfungsfragen</h5>
                        <div class="inhalt">Frage 1: ...<br>Antwort: ...</div>
                    </div>
                </div>
            </div>
            
        </div>
        
    </div>
</body>
</html>
```

---

### **Nutzung in der App:**

```typescript
// App lädt HTML von GitHub (wie Gesetze):
const response = await fetch(
  'https://raw.githubusercontent.com/710Deckel/FL-Academy-Content/main/academy-content.html'
);
const htmlText = await response.text();

// Parse HTML
const parser = new DOMParser();
const doc = parser.parseFromString(htmlText, 'text/html');

// Lese Module aus
const module = doc.querySelectorAll('.modul');
module.forEach(modul => {
  const modulId = modul.getAttribute('data-id');
  const modulIcon = modul.getAttribute('data-icon');
  const modulName = modul.querySelector('h2').textContent;
  
  // Lese Lektionen aus
  const lektionen = modul.querySelectorAll('.lektion');
  lektionen.forEach(lektion => {
    const titel = lektion.querySelector('h3').textContent;
    const dauer = lektion.getAttribute('data-dauer');
    const pruefung = lektion.getAttribute('data-pruefung') === 'true';
    
    // Lernziele
    const lernziele = [];
    lektion.querySelectorAll('.lernziele .lernziel').forEach(lz => {
      lernziele.push(lz.textContent);
    });
    
    // Anwärter-Inhalt
    const inhaltEl = lektion.querySelector('.anwaerter .inhalt');
    const inhalt = inhaltEl.innerHTML.replace(/<br>/g, '\n');
    
    // Beispiele
    const beispiele = [];
    lektion.querySelectorAll('.anwaerter .beispiele .beispiel').forEach(b => {
      beispiele.push(b.textContent);
    });
    
    // Zeige in App...
  });
});

// Status-Flags (status-justin, status-dozent):
→ NICHT in App anzeigen!
→ Nur für Editor/Dozenten
```

---

## 🔗 LINKS

- **GitHub Personal Tokens:** https://github.com/settings/tokens
- **GitHub Docs:** https://docs.github.com
- **HTML Validator:** https://validator.w3.org/
- **FL Mastery App:** [URL zur App]

---

## 📞 SUPPORT

Bei Fragen oder Problemen:
- 📧 Email: justin@fl-mastery.app
- 💬 Slack: #fl-academy-editor
- 📱 WhatsApp: [Nummer]

---

## 📝 CHANGELOG

**v2.0.0 - 2026-01-02**
- HTML-basierte Speicherung (statt JSON)
- Unbegrenzte Größe möglich
- Druck-Funktion mit Auswahl
- Professioneller Footer
- Wie Gesetze-Datenbank

**v1.0.0 - 2025-12-31**
- Initial Release
- JSON-basierte Speicherung
- GitHub-Integration
- 6 Module vorbereitet

---

## 👥 MITWIRKENDE

- **Justin Lee** - Hauptentwickler & Content-Creator
- **Verkehrsinstitut Schielein** - Dozenten-Team
- **FL-BE_07/25** - Testgruppe & Feedback

---

**Viel Erfolg beim Erstellen der Academy-Inhalte!** 🎓🚀

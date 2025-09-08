# Kapitel 3: Grundlagen zu ChatGPT und Prompt-Design

Willkommen zu den Begleitmaterialien für Kapitel 3. Hier lernen Sie die Grundlagen von ChatGPT und die entscheidende Fähigkeit des Prompt-Designs. Das Kapitel erklärt, wie man klare Anweisungen formuliert, Kontext bietet, Tonalität vorgibt und Rollenspiel-Techniken einsetzt.

## Begleitmaterialien

### 1. Sammlung von Beispiel-Prompts

**Prompt mit Rollenvorgabe:**
> "Du bist ein erfahrener Social-Media-Manager für eine nachhaltige Modemarke. Erstelle drei Instagram-Post-Ideen für unsere neue Kollektion aus recycelten Materialien. Sprich eine junge, umweltbewusste Zielgruppe an. Der Ton soll inspirierend und authentisch sein."

**Prompt mit Kontext und Formatvorgabe:**
> "Ich schreibe einen Blogartikel über die Vorteile von Remote-Arbeit. Fasse die folgenden Stichpunkte in einem flüssigen Absatz mit ca. 100 Wörtern zusammen. Formuliere professionell, aber zugänglich. Stichpunkte: Mehr Flexibilität, keine Pendelzeit, höhere Mitarbeiterzufriedenheit, Zugang zu einem globalen Talentpool."

**Prompt für kreatives Schreiben (Chain of Thought):**
> "Entwickle eine kurze Geschichte. Beginne mit dem Satz: 'Der alte Leuchtturm hatte ein Geheimnis, das nur bei Ebbe zum Vorschein kam.' Beschreibe Schritt für Schritt, was als Nächstes passiert, und baue Spannung auf."

### 2. Checkliste für effektives Prompting

-   [ ] **Klare Rolle zugewiesen?** (z.B. "Du bist ein SEO-Experte...")
-   [ ] **Kontext bereitgestellt?** (Was ist das Ziel? Wer ist die Zielgruppe?)
-   [ ] **Format der Ausgabe definiert?** (z.B. "in Stichpunkten", "als Tabelle", "ein Absatz")
-   [ ] **Tonalität und Stil vorgegeben?** (z.B. "professionell", "humorvoll", "einfühlsam")
-   [ ] **Negative Anweisungen vermieden?** (Sage, was du willst, nicht, was du nicht willst.)
-   [ ] **Beispiele zur Orientierung gegeben?** (z.B. "Schreibe im Stil von...")
-   [ ] **Schritt-für-Schritt-Anweisungen genutzt?** (Bei komplexen Aufgaben den Prozess aufteilen.)

### 3. Nutzungs-Limits bei ChatGPT (Stand 2025)

Um das Beste aus ChatGPT herauszuholen, ist es wichtig, die Nutzungs-Limits der verschiedenen Modelle zu kennen. Diese Limits können sich ändern, aber hier ist ein Überblick basierend auf den Informationen für 2025.

**Modell-Limits im Überblick (Plus/Team-Pläne):**

* **GPT-5 / GPT-5-Thinking:** Bis zu 200 Nachrichten pro Woche bei manueller Auswahl. Unbegrenzter Zugriff in Team/Pro-Plänen unterliegt Fair-Use-Richtlinien.
* **GPT-4.5:** 50 Nachrichten pro Woche.
* **GPT-4o / GPT-4.1:** 80 Nachrichten alle 3 Stunden.
* **GPT-4:** 40 Nachrichten alle 3 Stunden (inklusive Interaktionen mit Custom GPTs).
* **GPT-4.1 mini:** Unbegrenzte Nutzung.

**Wie funktionieren die Resets?**

* **3-Stunden-Limits:** Dies ist ein rollierendes Fenster. Es zählt ab der letzten Nachricht in diesem Zeitraum.
* **Wöchentliche Limits:** Ein rollierendes 7-Tage-Fenster, das mit Ihrer ersten Nachricht beginnt.
* **Tägliche Limits:** Werden um 00:00 Uhr UTC zurückgesetzt.

**Praktische Tipps, um Limits zu vermeiden:**

1.  **Richtiges Modell wählen:** Nutzen Sie "mini"-Varianten für einfache oder häufige Aufgaben und heben Sie sich die leistungsstärksten Modelle (GPT-5, GPT-4.5) für wichtige Aufgaben auf.
2.  **Anfragen bündeln:** Fassen Sie mehrere kleine Anfragen in einem einzigen, detaillierten Prompt zusammen (z.B. "Erstelle 10 Social-Media-Post-Ideen" statt 10 einzelner Anfragen).
3.  **API für Automatisierung nutzen:** Für sehr hohe Volumen oder programmgesteuerte Arbeitsabläufe ist die API oft die bessere Wahl.

*Quelle: Detaillierte Informationen und aktuelle Updates finden Sie im Artikel [ChatGPT User Limits for Plus, Team, and Enterprise Users (2025 Guide)](https://alexloth.com/chatgpt-user-limits-2025/).*

### 4. Nutzungslimits der Gemini App (Stand 2025)

Auch die Gemini App von Google unterliegt je nach gewähltem Abo unterschiedlichen Nutzungslimits. Die folgende Tabelle gibt einen Überblick über die verschiedenen Stufen.

| Funktion | Gemini App (kostenlos) | Gemini App mit Google AI Pro | Gemini App mit Google AI Ultra |
| :--- | :--- | :--- | :--- |
| **Prompts / Tag (2.5 Pro)** | Bis zu 5 | Bis zu 100 | Bis zu 500 |
| **Prompts / Tag (2.5 Flash)** | Allgemeiner Zugriff | Allgemeiner Zugriff | Allgemeiner Zugriff |
| **Audio-Zusammenfassungen**| Bis zu 20 / Tag | Bis zu 20 / Tag | Bis zu 20 / Tag |
| **Deep Research** | Bis zu 5 Berichte / Monat | Bis zu 20 Berichte / Tag | Bis zu 200 Berichte / Tag |
| **Deep Think** | - | - | Bis zu 10 Prompts / Tag |
| **Bilderzeugung & -bearbeitung**| Bis zu 100 Bilder / Tag | Bis zu 1.000 Bilder / Tag | Bis zu 1.000 Bilder / Tag |
| **Videogenerierung** | - | Bis zu 3 Videos / Tag | Bis zu 5 Videos / Tag |

*Beachten Sie, dass diese Limits sich ändern können und von dem jeweils ausgewählten Modell abhängig sind. Die Abos "Pro" und "Ultra" bieten zudem priorisierten Zugriff auf neue Funktionen.*

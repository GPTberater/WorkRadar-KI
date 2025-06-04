# WorkRadar KI – Frühwarnsystem für mentale Überlastung in Unternehmen

## Summary

WorkRadar KI is a tool that uses AI to analyze workplace-related texts to detect early signs of mental overload and psychosocial risks. It supports companies in acting proactively to ensure healthy work environments.  
Building AI course project

## Projektidee

WorkRadar KI ist ein KI-gestütztes Tool zur Analyse arbeitsbezogener Texte, das mögliche Frühindikatoren für mentale Überlastung oder psychosoziale Risiken am Arbeitsplatz erkennt. Ziel ist es, Unternehmen in die Lage zu versetzen, präventiv und strukturiert auf Belastungsentwicklungen zu reagieren – bevor sie zu Ausfällen oder Unzufriedenheit führen.

## Motivation

Psychische Belastungen und Stress am Arbeitsplatz nehmen zu. Unternehmen stehen vor der Herausforderung, trotz Fachkräftemangel und zunehmender Komplexität gesunde Arbeit zu ermöglichen. Gleichzeitig sind sie gesetzlich zur Gefährdungsbeurteilung psychischer Belastung verpflichtet (§5 ArbSchG). WorkRadar KI liefert einen innovativen, praxisnahen und datenschutzfreundlichen Ansatz zur frühzeitigen Erkennung von Handlungsfeldern.

## Wie funktioniert es?

1. Eingabe: Textdaten wie anonyme Rückmeldungen, Aufgabenbeschreibungen, Teamprotokolle  
2. Analyse: GPT-basierte Auswertung nach Mustern wie:
   - Überforderung und Verdichtung
   - Unklare Rollen
   - Soziale Isolation
   - Mangel an Handlungsspielraum
3. Ausgabe: Strukturierte Hinweise und Impulse zur Arbeitsgestaltung (z. B. Workshops, Prozessanpassung)

## Beispiel
"In letzter Zeit ist unklar, wer welche Entscheidungen trifft. Ich habe oft das Gefühl, dass alles bei mir landet. Außerdem kommen ständig neue Aufgaben rein."
Erkannte Risikomuster:
Rollenkonflikt
Anforderungsverdichtung
Mangelnde Abgrenzung

Empfohlene Maßnahmen:
Klärung der Zuständigkeiten im Team
Einführung regelmäßiger Arbeitsstand-Runden
Schulung zu Selbstmanagement und Priorisierung

## Technologischer Aufbau

- OpenAI GPT-4 API (z. B. über das `openai`-SDK oder LangChain)
- Python-Backend für Textverarbeitung und Analyse
- Regelbasierte Prompt-Struktur mit arbeitswissenschaftlicher Logik
- Optional: Ausgabe als strukturierter Bericht (JSON oder PDF)

## Projektplan

### Zielsetzung

Ziel ist die Entwicklung eines Prototyps, der typische Belastungsmuster aus Texten erkennt und Handlungshinweise liefert. Das Tool soll datenschutzfreundlich, modular erweiterbar und praxisnah sein.

### Projektphasen

#### 1. Planungsphase (Woche 1–2)
- Definition von Zielgruppe und Anwendungskontext
- Erstellung von README und GitHub-Struktur
- Auswahl der zu erkennenden Belastungsmuster
- Klärung datenschutzrechtlicher Rahmenbedingungen

#### 2. Prototyping (Woche 3–4)
- Entwicklung eines Python-Skripts zur Textanalyse
- Formulierung erster Prompts
- Erstellung der `requirements.txt`
- Durchführung erster Tests mit Beispieldaten

#### 3. Evaluation und Feinschliff (Woche 5–6)
- Entwicklung eines Bewertungsschemas
- Durchführung von Testläufen mit Feedback von Dritten
- Anpassung und Optimierung der Prompt-Logik

#### 4. Veröffentlichung (Woche 7)
- Veröffentlichung des Repos (öffentlich oder mit Freigabe)
- Dokumentation der Nutzung
- Optionale Kommunikation in Fachnetzwerken

## Ressourcen und Tools

| Bereich             | Tool/Plattform              |
|---------------------|------------------------------|
| KI-Backend          | OpenAI GPT-4 API             |
| Programmierung      | Python 3.11+                 |
| Prompt-Entwicklung  | Jupyter Notebook oder VS Code |
| Projektablage       | GitHub                       |
| Dokumentation       | Markdown, ggf. PDF           |

## Risiken und Gegenmaßnahmen

| Risiko                                     | Maßnahme                                        |
|-------------------------------------------|-------------------------------------------------|
| GPT „halluziniert“ oder interpretiert falsch | Strukturierte Prompts mit klarer Aufgabenstellung |
| Datenschutzbedenken bei echten Eingaben     | Nutzung anonymisierter Beispieldaten           |
| Geringe Aussagekraft bei kurzen Texten      | Mindestanforderungen an Eingabetexte definieren |

## Nächste Schritte

- [ ] Prompts für häufige Belastungsmuster entwickeln  
- [ ] Realistische Beispieldaten erstellen  
- [ ] `main.py` und `requirements.txt` bereitstellen  
- [ ] Erste Tests mit mehreren Eingabetexten durchführen

## Autor

Dieses Projekt wurde von GPTBerater aka David  im Rahmen des "Building AI"-Kurses erstellt. Beruflich beschäftige ich mich mit Arbeitswissenschaft, Organisationsberatung und dem Einsatz von KI zur Unterstützung betrieblicher Veränderungsprozesse.

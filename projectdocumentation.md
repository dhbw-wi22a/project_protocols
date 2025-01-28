# Projektdokumentation

## Projektname: B2B-Webshop
**Hochschule:** Duale Hochschule Baden-Würrtemberg Campus Mosbach

**Vorlesung:** Projektkonzeption und - realisierung

**Business:** Hot Hardware Hub - IT-Shop für B2B

## Allgemeine Anmerkungen
- **Links:** [[GitHub Organization Link\]](https://github.com/orgs/dhbw-wi22a/repositories), [[Dokumentationsordner Link](https://docs.google.com/document/d/1AzoZFVLxZhogN-CUMFNINNEsYIKOvFQc5Ry4IHX6FH0/edit?usp=sharing)], [[Scrum-Board Link](https://tree.taiga.io/project/ssptzk-b2b-webshop/)]
- **Projektteamverantwortliche:** [Christ, Colin] [Spatzek, Steffen]

---

## Sprint 0
### Zeitraum: [27.11.2024] - [06.12.2024]

---

### 1. Aufgabenübersicht
| **Aufgabe**                      | **Bearbeiter/in**                                            | **Status**      | **Bemerkungen**            |
|----------------------------------|--------------------------------------------------------------|-----------------|----------------------------|
| Projektstruktur erstellt         | [Steffen]                                                    | Abgeschlossen   | Erste Ordnerstruktur festgelegt. |
| GitHub-Organisation & Github-Repos eingerichtet      | [Steffen]                                                    | Abgeschlossen   | Repository und Projektboards angelegt. |
| Rollenaufteilung definiert       | [Colin]                                                      | Abgeschlossen   | Scrum Master, Product Owner, Solution Architects und Entwickler festgelegt. Sub-Teams eingeteilt. |
| Einrichtung VPS und Bereitstellungsplattform | [Steffen]                                                    | Abgeschlossen   | Hochfahren des VPS. Einrichtung von Dokploy. |
| Basis für Front- und Backend erstellt. | [Alan] ,[Andreas]                                            | Abgeschlossen   | Projekt für Front- und Backend erstellt und auf Github bereitgestellt. |
| Einrichtung Scrum-Board 'Taiga.io'        | [Steffen]                                                    | Abgeschlossen   | Scrum-Board erstellt, eingerichtet und alle Projektteilnehmer eingeladen. |
| Basis des Pflichtenhefts erstellt und bereitgestellt.         | [Lukas], [Daniel] ,[Milan],[Bastian],[David],[Luis] ,[Colin] | Abgeschlossen   | Basis-Version des Pflichtenhefts bereitgestellt. LaTex-Dokument erstellt. Skizzierung findet in Google Docs, finale Niederschritt als LaTex-Dokument statt. |
| Vorlagenerstellung und Beginn Meta-Projektdokumentation | [Steffen]                                                    | Abgeschlossen   | Basis-Version der Projektdokumentation angefertigt und begonnen. Dieses wird fortführend zu jedem Sprint erweitert und darin jegliche Meta-Informationen protokolliert.|
---

### 2. Meta-Fragen und Entscheidungen mit deren Begründung
- **Wie finden Teammeetings statt und wie werden diese abgehalten?**
  - Teammeetings werden über Discord organisiert, wobei vorab entsprechende Events im Kalender geplant werden. Die Gruppensprecher oder deren Stellvertreter moderieren die Meetings, sprechen Aufgaben an und delegieren diese. Es gibt zudem Raum für gemeinsames Brainstorming und die Entwicklung von Lösungen im Team.

  - Kleinere Abstimmungen, wie z. B. zwischen Frontend- oder Backend-Entwicklern, finden separat und ad hoc statt, wenn spezifische Klärungen notwendig sind. Die gesamte Kommunikation wird über Discord abgewickelt, während die Aufgabenzuteilung und Fortschrittsübersicht im Taiga Board erfolgt.

- **Warum haben wir uns für [Thema/Entscheidung] entschieden?**
  - **"Warum ein IT-Hardware-Shop?"**  
    Unsere Zielgruppe hat einen Bedarf für spezialisierte Hardware-Beschaffung. Dies wurde durch eine Umfrage in Unternehmen bestätigt.
    Durch Abstimmung im Projektteam haben wir uns festgelegt einen IT-B2B-Shop zu entwickeln. 

- **Warum Scrum als Projektmethodik?**
  - Scrum ermöglicht uns eine iterative Vorgehensweise mit regelmäßigen Feedback-Schleifen, die für das agile Umfeld wichtig ist. Unsere Teammitglieder haben zudem Vorerfahrungen mit Scrum, was den Einstieg erleichtert.
  Zudem können nach jedem Sprint schon erste erfolge deployed werden und sind nutzbar.

- **Wieso nutzen wir Python Django und Angular als Techstack?**  
  - **Python Django**: Django ist ein leistungsstarkes Framework, das schnelle und sichere Backend-Entwicklung ermöglicht. Es bietet eine robuste Datenbankverwaltung, eine eingebaute Authentifizierung und folgt dem "Batteries-included"-Ansatz, was Entwicklungszeit spart und Best Practices fördert. Python ist zudem leicht lesbar, flexibel und ermöglicht eine schnelle Einarbeitung.  
  - **Angular**: Angular ist ein modernes Frontend-Framework, das durch seine Modularität, starke Typisierung (TypeScript) und breite Community-Unterstützung überzeugt. Es erleichtert die Entwicklung dynamischer und performanter Webanwendungen mit klarer Trennung von Logik und Darstellung. Durch die Nutzung von Angular können wir wiederverwendbare Komponenten und eine verbesserte Nutzererfahrung gewährleisten.  

    Dieser Techstack bietet uns eine klare Trennung zwischen Backend und Frontend, ermöglicht eine effiziente Entwicklung und ist zukunftssicher durch die große Community und regelmäßige Updates beider Frameworks.

- **Wieso nutzen wir Dokploy als PaaS für das Deployment und Docker für Containerisierung?**  
  - **Dokploy (Platform as a Service)**: Dokploy bietet eine einfache und kosteneffiziente Möglichkeit, Anwendungen zu hosten und zu verwalten. Es ermöglicht eine schnelle Bereitstellung unserer Applikationen, ohne dass wir uns um die komplexen Details der Infrastruktur kümmern müssen. Mit seiner Integration von Git und Unterstützung für mehrere Sprachen und Frameworks passt es perfekt zu unserem Techstack. Zudem skaliert Dokploy automatisch, was uns erlaubt, bei wachsender Nutzung flexibel zu bleiben.  

  - **Containerisierung mit Docker**: Docker erlaubt uns, unsere Anwendungen in isolierten Containern auszuführen, wodurch die Entwicklungs- und Produktionsumgebungen identisch bleiben. Das reduziert Probleme durch Abweichungen zwischen Umgebungen erheblich. Mit Docker können wir alle Abhängigkeiten (z. B. Bibliotheken, Frameworks) bündeln, was die Bereitstellung konsistenter und zuverlässiger macht. Containerisierung macht unser Deployment portabler, skalierbarer und erleichtert die Zusammenarbeit im Team, da "es funktioniert auf meinem Rechner"-Probleme eliminiert werden.


---

### 3. Retrospektive
#### Was lief gut?
- **Teamarbeit:** Gute Kommunikation via Discord und klare Aufgabenverteilung.
- **Tools:** Taiga.io war einfach einzurichten und gut geeignet für unsere Organisation. Für die Kommunikation nutzen wir einen Discord-Server um alle Projektteilnehmer mitzunehmen und Neuigkeiten zu verbreiten.

#### Was lief nicht gut?
- **Zeitmanagement:** Einige Deadlines wurden knapp erreicht. 
- **Kommunikation:** Wenig Feedback bei der ersten Rollenverteilung.
- **Aufgabenbearbeitung:** Verzögerte Umsetzung bei manchen Projektteilnehmern. 

#### Verbesserungsmaßnahmen für den nächsten Sprint
- Wöchentliche Check-ins einführen, um Fortschritt und Herausforderungen zu besprechen.
- Zeitpuffer bei Aufgabenplanung einbauen.
- Sub-Teams mit Sub-Teamlead die sich abgekapselt abstimmen und zusammenwirken, losgelöst vom gesamten Projektteam.

---
## Sprint 1
### Zeitraum: [07.12.2024] - [27.12.2024]

---

### 1. Aufgabenübersicht
| **Aufgabe**                         | **Bearbeiter/in**                                     | **Status**   | **Bemerkungen**                                                                                                                                                                                                                                                  |
|-------------------------------------|-------------------------------------------------------|--------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Research KI-Komponente              | [Bastian]                                             | Abgeschlossen | Research welche KI-Kompnente in unserem Webshop implementiert werden könnte.                                                                                                                                                                                     |
| Mailservice                         | [Steffen]                                             | Abgeschlossen | Entwicklung eines Mailservices in Go. Mailservice mit Queue-Funktion, Multi-Recipients, HTML-Templates. Bereitstellung auf dem VPS.                                                                                                                              |
| Projektdokumenationen               | [Lukas], [David], [Colin]                             | Abgeschlossen     | Fortführen des Pflichtenheftes. Niederschrift in LaTex-Dokument zu gewissen Abständen.                                                                                                                                                                           |
| Diagramm- und Skizzenerstellung     | [Luis], [Milan], [Steffen]                            | Abgeschlossen | Erstellung Use-Case-Diagramm sowie System-Architekturgrafik.                                                                                                                                                                                                     |
| Benutzerbereich                     | [Andreas],[Alan], [Steffen], [Julian], [Paul], [Noah] | Abgeschlossen | Gast-Bereich auf dem Frontend. Im Backend Erstellung des User-Modells für Registrierung, Login und weiteres.                                                                                                                                                     |
| Produktkatalog                      | [Andreas],[Alan], [Steffen]                           | Abgeschlossen | V1 des Shops auch in Angular bereitgestellt. Darstellung der Produkte. Gast-Ansicht ohne User-Login.                                                                                                                                                             |
| Admin-Dashboard                     | [Alan]                                                | Abgeschlossen | Bereitstellung Admin-Dashboard in Django. Dort können User, Artikel und weiteres verwaltet werden.                                                                                                                                                               |
| Containerisierung & GitHub-Workflow | [Steffen], [Alan]                                     | Abgeschlossen | Containerisierung des gesamten Projektes. Aufrechterhaltung der 2-Branch-Strategie in Test und Prod. Bereitstellung auf dem VPS via Dokploy. Eigenes Deploy-Repo, dieses wird mit den darinliegenden Submodules automatisch via GH Action Workflow aktualisiert. |

---

### 2. Meta-Fragen und Entscheidungen

- **Warum verwenden wir unterschiedliche Branches und deployen diese beide, automatisiert nach jeder signifikanten Erweiterung?**  
  - Unterschiedliche Branches (Dev und Release) ermöglichen eine klare Trennung zwischen Entwicklungs- und Produktionsumgebung. Dies minimiert das Risiko, unausgereiften Code in die Produktivumgebung zu übernehmen. Automatisiertes Deployment sorgt für schnelle Tests und stellt sicher, dass Änderungen direkt überprüfbar sind.
  Beide Entwicklungsstände sind lokal auszuführen mit Docker Desktop, können jedoch auch deployt auf dem VPS aufgerufen werden.

- **Weshalb ein separierter Deploy-Repository mit Submodules der Branches und einem hinterlegten GH-Action-Workflow zur automatisierten Übernahme?**  
  - Ein separates Deploy-Repository mit Submodules bietet eine saubere Trennung zwischen Quellcode und Deployment-Logik. Der GitHub-Action-Workflow automatisiert die Übernahme, reduziert manuelle Eingriffe und sorgt für einen zuverlässigen und reproduzierbaren Bereitstellungsprozess.

- **Darlegung, wieso im Entwicklungsprojekt eine SQLite-Datenbank verwendet wird, im Produktionsumfeld jedoch eine PostgreSQL-Datenbank:**  
  - SQLite wird in der Entwicklungsphase genutzt, da sie leichtgewichtig, schnell einrichtbar und für lokale Tests ausreichend ist. Im Produktionsumfeld bietet PostgreSQL hingegen Skalierbarkeit, hohe Performance und robuste Sicherheits- sowie Verwaltungsfunktionen, die für den produktiven Einsatz notwendig sind.

- **Vorgehensweise, wie neue Features und generelle Überarbeitungen für den B2B-Webshop eruiert und festgesetzt werden:**  
  - Neue Features und Überarbeitungen werden im Team gemeinsam erarbeitet. In regelmäßigen Meetings brainstormen wir, welche Ideen im aktuellen Entwicklungsstadium sinnvoll und umsetzbar sind. Alle Teammitglieder bringen Vorschläge ein, die anschließend im Scrum Board dokumentiert werden. Projektteilnehmer wählen sich anschließend Aufgaben aus, wobei auch die Zusammenarbeit mehrerer Personen an einer Aufgabe möglich ist, um Synergieeffekte zu nutzen und Wissenslücken auszugleichen.
 
- **Wieso wird die Dokumentation in LaTex verfasst und nicht in einem anderen Format?**
  - LaTex bietet eine klare Strukturierung und Formatierung von Dokumenten, die für technische Dokumentationen ideal ist. Es ermöglicht die einfache Einbindung von Diagrammen, Tabellen und Code-Snippets, was die Dokumentation übersichtlich und professionell macht. Zudem ist LaTex plattformunabhängig und erlaubt eine effiziente Zusammenarbeit im Team, da Änderungen versioniert und nachvollziehbar sind.

- **Weshalb erstellen wir die Diagramme, Modelle oder Skizzen in Draw.io und speichern diese in einem Repository?**  
  - Durch die vorhandene **Draw.io VS Code Extension** können wir Diagramme direkt in unserer Entwicklungsumgebung bearbeiten, ohne externe Programme installieren zu müssen.  
  - Die fertigen Diagramme lassen sich als **PNG oder SVG exportieren** und problemlos in unsere LaTeX-Dokumentation einbinden.  
  - Durch die Speicherung im Repository bleiben alle Änderungen nachvollziehbar. Änderungen können über Pull Requests überprüft und versioniert werden.  
  - Teammitglieder können parallel an Diagrammen arbeiten, indem sie XML-Dateien bzw. DIO-Dateien über Git teilen und bei Bedarf Änderungen zusammenführen.  

---

### 3. Retrospektive

#### Was lief gut?
- Die meisten Aufgaben konnten ohne größere technische Schwierigkeiten durchgeführt werden. Dies zeigt, dass der gewählte Techstack und die Arbeitsmethodik funktionierten. Die Kleingruppensitzungen zur Entwicklung und Dokumentation waren produktiv. Sie ermöglichten ein zielgerichtetes Arbeiten und förderten den Austausch von spezifischem Fachwissen. Das Taiga Board wurde effektiv genutzt. Aufgaben wurden vom Lead erstellt, von den Teammitgliedern selbständig übernommen und im Workflow (In Progress → Testen → Abschließen) aktiv verwaltet. Dies sorgte für klare Verantwortlichkeiten und Transparenz im Projektfortschritt.

#### Was lief nicht gut?
- Die Feiertage führten zu einer Pause im Projekt, die den allgemeinen Rhythmus und die Dynamik des Teams vorübergehend beeinträchtigte. Bei wichtigen Besprechungen und Abstimmungen waren nicht alle Teammitglieder anwesend. Dies führte zu Verzögerungen, Missverständnissen und teilweise doppelter Arbeit. In einigen Fällen musste die Kommunikation aktiv von den Gruppenleitern initiiert werden, da Fortschritte nicht eigenständig kommuniziert wurden. Dies verursachte zusätzlichen Koordinationsaufwand. 

#### Verbesserungsmaßnahmen
- **Gezieltere Kommunikation:** Regelmäßige Abstimmungstermine festlegen, z.B. wöchentliche Team-Calls oder Stand-ups. Diese können über Tools wie Discord oder Teams organisiert werden. Discord-Veranstaltungen helfen, die Verfügbarkeit aller Mitglieder besser zu planen. Protokolle aller Meetings sollten erstellt und geteilt werden, um Abwesende über die Ergebnisse auf dem Laufenden zu halten.
- **Effizientere Aufgabenverteilung:** Die Aufgaben im Scrum-Board sollten gezielt von 1-2 Personen (z.B. Gruppenleads) erstellt werden, um eine klare Struktur zu gewährleisten. Ein regelmäßiges Review des Boards, z.B. in Sprint-Meetings, hilft, den Fortschritt zu überwachen und Hindernisse frühzeitig zu erkennen.
- **Klärung von Verantwortlichkeiten:** Nicht zugewiesene Aufgaben sollten in den Sitzungen aktiv angesprochen werden. Dabei kann eine Kapazitätsprüfung durchgeführt werden, um die Aufgaben gerecht zu verteilen. Die Einführung von Verantwortungsrollen, z.B. ein „Task Owner“ für jede Aufgabe, sorgt für klare Zuständigkeiten.
- **Motivationssteigerung:** Für Feiertage oder andere schwierige Zeiten können kleinere, erreichbare Zwischenziele gesetzt werden, um die Motivation aufrechtzuerhalten. Eine Feedback-Kultur, in der Fortschritte regelmäßig anerkannt werden, kann die Teamdynamik verbessern.
- **Bessere Planung für Absprachen:** Nutzung von Tools, um Besprechungen besser auf die Verfügbarkeiten des Teams abzustimmen. Alternativ könnte ein fester Meeting-Tag eingeführt werden, der wöchentlich eingehalten wird.

---
## Sprint 2
### Zeitraum: [28.12.2024] - [22.01.2025]

---

### 1. Aufgabenübersicht
| **Aufgabe**                        | **Bearbeiter/in**    | **Status**      | **Bemerkungen**            |
|------------------------------------|----------------------|-----------------|----------------------------|
| Projektdokumentation                            | [Lukas], [David]              | Abgeschlossen           | Pflichtenheft wird fortgeführt, regelmäßige LATEX-Synchronisation.         |
| Unternehmensfunktionen                        | [Andreas], [Steffen]              | Abgeschlossen           | Backend und Frontend des Company-Bereich, Backend und Frontend von Gruppierungen und Subuserfunktionen, geteilte Einkaufslisten.     |
| Benutzerbereich II                 | [Andreas],   | Abgeschlossen           | Backend und Frontend der Benutzerverwaltung.       |
| E-Mail Benachrichtigungen                      | [Steffen], [Daniel], [David]              | Abgeschlossen           | Backend der E-Mail Funktionen, HTML-Templates    |
| KI-Chatbot                     | [Basti]              | Abgeschlossen           | Konzeption und Erstellung des KI-Chatbot      |
| Organisation                     | [Lukas],[Luis], [Steffen]              | Abgeschlossen           | Erweiterung der Modellskizzen, Meta-Dokumentation für Sprint 2, Retroperspektive für Sprint 1      |
| Produktkatalog   | [Andreas]              | Abgeschlossen           | Backend des Betsellprozess, Frontend und Backend der Produktfilterung, Frontend und Backend der Kategorisierung       |
| Storyless tasks   | [Andreas], [Julian], [Steffen]                | Abgeschlossen           | Anzeige der Rechtstexte, Responsive Design, Optimierung der Frontend-Ansicht       |
---

### 2. Meta-Fragen und Entscheidungen

- **Wieso werden wir, vorerst, keine Unit Tests oder anderweitige, automatisierte Tests integrieren?**  
  - Aufgrund der begrenzten Zeit und der kleinen Teamgröße setzen wir unseren Fokus auf die Kernentwicklung und das Deployment des B2B-Webshops. Anstelle automatisierter Tests nutzen wir ein **4-Augen-Prinzip**, bei dem Code-Änderungen von anderen Teammitgliedern überprüft werden, bevor sie in den Release-Branch übergehen.  

  - Durch unsere **zwei-Branch-Strategie** können nicht-entwickelnde Teammitglieder neue Features und Änderungen in der Dev-Umgebung ausgiebig testen und etwaige Fehler oder Verbesserungsvorschläge an das Dev-Team zurückmelden.  

  - Zusätzlich führen Entwickler vor jedem Commit lokale Tests durch – beispielsweise API-Tests mit **Postman** oder direkte Funktionsüberprüfungen im Frontend. So stellen wir sicher, dass Erweiterungen stabil sind, bevor sie in das Repository übernommen werden.  

- **Weshalb nutzen wir einen eigenen Mailservice, anstatt einen externen Anbieter zu verwenden?**  
  - Ein eigener Mailservice bietet uns mehr Kontrolle über den Versand von E-Mails und ermöglicht eine individuelle Anpassung an unsere Anforderungen. Wir können beispielsweise spezifische Templates und Inhalte erstellen, personalisierte E-Mails versenden und den Versandprozess in unsere Anwendung integrieren.  

  - Durch die Integration eines eigenen Mailservices können wir außerdem die Performance und Zuverlässigkeit des Versands optimieren, da wir die Infrastruktur und den Workflow selbst verwalten. Dies gibt uns die Flexibilität, den Service bei Bedarf anzupassen und zu erweitern. Zudem hosten wir das gesamte Projekt ohnehin auf einem VPS, der entwickelte Mailservice in Go ist ressourceneffizient und passt gut in unsere Infrastruktur.

- **Welchen Grund gibt es, dass Sprint 0 eine kürzere Dauer hat als Sprint 1 sowie Sprint 2?**  
  - **Sprint 0** diente primär der **Projektinitialisierung**, einschließlich Infrastrukturaufbau, Planung und grundlegender Setup-Aufgaben. Da hier noch keine umfangreiche Entwicklung stattfand, war eine kürzere Sprint-Dauer ausreichend.  
  - **Sprint 1** fiel in eine Zeit mit Feiertagen und verstärktem Vorlesungsaufwand, wodurch die verfügbare Arbeitszeit begrenzt war.  
  - **Sprint 2** fokussiert sich stärker auf die eigentliche Entwicklung. Da unser Entwicklerteam vergleichsweise klein ist, benötigen wir längere Phasen, um Features gründlich umzusetzen. Zudem haben wir festgestellt, dass **zwei Wochen für einen Sprint zu kurz** sind, um größere Entwicklungsaufgaben effizient abzuschließen.  
  - Eine längere Sprint-Dauer ermöglicht uns außerdem **ausführlichere Tests und stabilere Releases**, ohne den Druck zu erhöhen.  
- **Metafrage 4**  
  - [Antwort]
---

### 3. Retrospektive
#### Was lief gut?
- [Punkte einfügen]

#### Was lief nicht gut?
- [Punkte einfügen]

#### Verbesserungsmaßnahmen
- [Maßnahmen einfügen]

---


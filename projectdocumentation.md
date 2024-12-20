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
| **Aufgabe**                      | **Bearbeiter/in**    | **Status**      | **Bemerkungen**            |
|----------------------------------|----------------------|-----------------|----------------------------|
| Projektstruktur erstellt         | [Steffen]              | Abgeschlossen   | Erste Ordnerstruktur festgelegt. |
| GitHub-Organisation & Github-Repos eingerichtet      |[Steffen]              | Abgeschlossen   | Repository und Projektboards angelegt. |
| Rollenaufteilung definiert       | [Colin]              | Abgeschlossen   | Scrum Master, Product Owner, Solution Architects und Entwickler festgelegt. Sub-Teams eingeteilt. |
| Einrichtung VPS und Bereitstellungsplattform | [Steffen]              | Abgeschlossen   | Hochfahren des VPS. Einrichtung von Dokploy. |
| Basis für Front- und Backend erstellt. | [Alan] [Andreas]             | Abgeschlossen   | Projekt für Front- und Backend erstellt und auf Github bereitgestellt. |
| Einrichtung Scrum-Board 'Taiga.io'        | [Steffen]              | Abgeschlossen   | Scrum-Board erstellt, eingerichtet und alle Projektteilnehmer eingeladen. |
| Basis des Pflichtenhefts erstellt und bereitgestellt.         | [Lukas] [Daniel] [Milan]  [Bastian]  [David]  [Luis]  [Colin]                  | Abgeschlossen   | Basis-Version des Pflichtenhefts bereitgestellt. LaTex-Dokument erstellt. Skizzierung findet in Google Docs, finale Niederschritt als LaTex-Dokument statt. |
| Vorlagenerstellung und Beginn Meta-Projektdokumentation | [Steffen] | Abgeschlossen   | Basis-Version der Projektdokumentation angefertigt und begonnen. Dieses wird fortführend zu jedem Sprint erweitert und darin jegliche Meta-Informationen protokolliert.|
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
| **Aufgabe**                      | **Bearbeiter/in**    | **Status**      | **Bemerkungen**            |
|----------------------------------|----------------------|-----------------|----------------------------|
| Research KI-Komponente             | [Name]              | Offen           | Noch nicht begonnen.       |
| Mailservice             | [Name]              | Offen           | Noch nicht begonnen.       |
| Projektdokumenationen             | [Name]              | Offen           | Noch nicht begonnen.       |
| Benutzerbereich            | [Name]              | Offen           | Noch nicht begonnen.       |
| Produktkatalog            | [Name]              | Offen           | Noch nicht begonnen.       |
| Admin-Dashboard             | [Name]              | Offen           | Noch nicht begonnen.       |
| Containerisierung & GitHub-Workflow            | [Name]              | Offen           | Noch nicht begonnen.       |

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

---

### 3. Retrospektive
#### Was lief gut?
- [Punkte einfügen]

#### Was lief nicht gut?
- [Punkte einfügen]

#### Verbesserungsmaßnahmen
- [Maßnahmen einfügen]

---


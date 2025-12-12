# Projekt-Proposal: MyYearlyView

- **Modul:** Software Engineering
- **Studiengang:** Wirtschaftsinformatik (B.Sc.)
- **Projektteam:** Tabea Ortwain, Sena Nur Akpolad, Meriam Lakhrissi, Raey Shemeles Ayele

---

## 1. Executive Summary

Das Produkt **MyYearlyView** adressiert den Bedarf nach einer effizienten und emotional ansprechenden Organisation digitaler Erinnerungen. Es handelt sich um eine Softwarelösung für Desktop- und Tablet-Systeme, die automatisierte Fotoverwaltung mit geografischer Kontextualisierung verbindet, um personalisierte Jahresrückblicke zu erstellen.

---

## 2. Abstract

MyYearlyView ist ein Desktop- und Tablet-Tool zur automatisierten Erstellung personalisierter Fotokalender, die die besonderen Momente eines Jahres visuell festhallten. Die Anwendung importiert Fotos aus beliebigen Ordnern und analysiert deren EXIF-Metadaten wie Aufnahmezeitpunkt und GPS-Koordinaten. Auf BAsis dieser Information generiert das System intelligente Monatsübersichten: Bilder werden automatisch zugeordent, sortiert und entlang des tatsächlichen Jahresverlaufs angeordent. Ergänzend reichert MyYearlyView jeden Aufnahmeort mit zusaätzlichem geografischen Kontext an, indem historische Hintergründe, lokale Besonderheiten oder ortsbezogene Empfehlungen angezeigt und bei Bedarf in die Kalenderseiten integriert werden. Eine interaktive Weltkarte visualisiert alle Reise- und Aufnahmeorte des Jahres und schafft dadurch einen emotionalen Gesamtüberblick. Das Ergebnis ist ein hochwertiges, druckfertiges PDF, das Nutzer direkt als Fotokalender produzieren können.

---

## 3. Produktbeschreibung und Zentrale Eigenschaften

MyYearlyView ist ein Tool zur Kuration und Visualisierung persönlicher Erlebnisse. Im Gegensatz zu herkömmlichen Fotobüchern liegt der Fokus auf der **intelligenten Automatisierung** und der **geografischen Anreicherung** der Inhalte.

Die zentralen Eigenschaften (*Key Features*) gliedern sich in fünf Funktionsbereiche:

### 3.1 Automatische Fotoverwaltung & KI-Analyse
Das System eliminiert den manuellen Sortieraufwand.
* **Import:** Nahtloses Einlesen von Bildern aus lokalen Verzeichnissen oder Cloud-Speichern.
* **Intelligente Sortierung:** Algorithmen sortieren Inhalte automatisch nach Metadaten (Datum, Ort) und nutzen Gesichtserkennung zur Identifikation relevanter Personen.

### 3.2 Geografische Kontextualisierung
Die Software reichert Fotos mit externen Daten an, um den Erlebniswert zu steigern.
* **Standortdaten:** Verknüpfung der Bilder mit Geodaten und lokalen Empfehlungen oder Sehenswürdigkeiten.
* **Visualisierung:** Darstellung der Reiseroute und Erlebnisse auf einer interaktiven Weltkarte.

### 3.3 Personalisierung & Design
Erstellung hochwertiger Jahreskalender, die über reine Fotocollagen hinausgehen.
* **Customizing:** Nutzung variabler Templates, Layouts und Designs zur Visualisierung wichtiger Jahresereignisse.
* **Inhaltliche Tiefe:** Der Kalender visualisiert nicht nur Bilder, sondern "Momente" und Meilensteine.

### 3.4 Interaktivität & User Engagement
Das Tool fördert die aktive Auseinandersetzung mit den Erinnerungen.
* **Feedback-Loop:** Nutzer können Erinnerungen durch Sternebewertungen qualifizieren oder spezifische Fragen zu Ereignissen beantworten (z. B. "Highlight des Monats").
* **Privatsphäre & Sharing:** Präzise Anpassungsmöglichkeiten (privat vs. öffentlich) sowie Exportfunktionen für Social Media oder digitale Weitergabe.

### 3.5 Plattform & Usability
* **Verfügbarkeit:** Entwicklung als Native App für Desktop (Windows, macOS) und Tablet (iPadOS).
* **UX-Design:** Fokus auf einer intuitiven Benutzeroberfläche.
  
[Smart Photo Calendar.pdf](https://github.com/user-attachments/files/24108388/Smart.Photo.Calendar.pdf)

---

## 4. Zielgruppenanalyse

Das Produkt richtet sich an Menschen, die sich für visuelle Medien begeistern und Erinnerungskultur leben.

### Primäre Zielgruppe: Privatpersonen & Familien
* **Profil:** Eltern, Familien und Einzelpersonen, die persönliche Meilensteine (Feste, Aufwachsen der Kinder) dokumentieren.
* **Bedürfnis:** Einfache Handhabung und emotionale Aufbereitung der Familiengeschichte.

### Sekundäre Zielgruppe: Reisende & Fotografie-Enthusiasten
* **Profil:** Urlauber und Hobbyfotografen mit hohem Anspruch an Bildorganisation.
* **Bedürfnis:** Detaillierte geografische Nachverfolgung (Mapping) und präzise Sortierfunktionen (Gesichtserkennung).

---

## 5. Erwartungshaltung und Erfolgskriterien

Der Erfolg der Software hängt davon ab, wie gut sie die konkreten Probleme der Nutzer löst.

### Erwartungshaltung der Nutzer
1. **Zeitersparnis:** Die Automatisierung muss deutlich schneller sein als das manuelle Sortieren der Bilder.
2. **Individualität:** Trotz Automatik sollen die Ergebnisse persönlich wirken und anpassbar bleiben.
3. **Mehrwert:** Standortdaten und Zusatzinfos müssen einen echten Nutzen für die Erinnerung bieten.
4. **Datenschutz:** Sicherer Umgang mit privaten Daten und volle DSGVO-Konformität.

### Definition of Success
Das Projektziel ist erreicht, wenn das Produkt folgende Kriterien erfüllt:

> "Das Tool gilt als erfolgreich, wenn es eine zuverlässige, automatisierte Fotosortierung mit intuitiver Kalender-Erstellung verbindet und dabei höchste Ansprüche an Datenschutz und Benutzerfreundlichkeit erfüllt."

---

## 6. Projektstruktur

Die Umsetzung des Projekts erfolgt in vier zentralen Phasen, die sich an einem iterativen Entwicklungsprozess orientieren.

### 6.1 Aufgabenfelder
Um die Kompetenzen des Teams (4 Personen) optimal zu nutzen, werden die Aufgaben in folgende Bereiche unterteilt:

* **Projektmanagement & Dokumentation:** Koordination, Zeitplanung, Dokumentation (Lastenheft, Abschlussbericht).
* **Frontend-Entwicklung (UI/UX):** Design der Benutzeroberfläche für Desktop und Tablet, Kalender-Visualisierung.
* **Backend & Datenmanagement:** Lokale Datenbank, Datei-Import, Speichermanagement.
* **KI & Algorithmen:** Implementierung der Bildanalyse (Gesichtserkennung) und automatischen Sortierung.
* **Integration & Mapping:** Anbindung der Karten-APIs und Geodaten-Verarbeitung.

### 6.2 Work Breakdown Structure (PSP) & Aufwände
Der Projektstrukturplan (PSP) gliedert das Projekt in Arbeitspakete. Die Aufwände sind in Personentagen (PT) geschätzt (1 PT = 8 Arbeitsstunden).

| ID | Phase / Arbeitspaket | Beschreibung | Aufwand (Geschätzt) |
| :--- | :--- | :--- | :--- |
| **1.0** | **Initialisierung & Analyse** | | **5 PT** |
| 1.1 | Projekt-Setup | Repo aufsetzen, Tools konfigurieren | 1 PT |
| 1.2 | Anforderungsanalyse | Erstellung Lastenheft & Use Cases | 2 PT |
| 1.3 | UI-Konzept | Design-Skizzen & Mockups erstellen | 2 PT |
| **2.0** | **Entwicklung (Core)** | | **15 PT** |
| 2.1 | Import-Modul | Einlesen lokaler Daten | 3 PT |
| 2.2 | KI-Analyse | Integration von Algorithmen zur Bilderkennung | 5 PT |
| 2.3 | Datenbank | Design & Implementierung der Speicherung | 3 PT |
| 2.4 | Geo-Services | Kartenansicht & Orte verknüpfen | 4 PT |
| **3.0** | **Entwicklung (UI & Features)** | | **12 PT** |
| 3.1 | Kalender-Engine | Logik zur Erstellung der Jahresrückblicke | 5 PT |
| 3.2 | Frontend Desktop | Umsetzung des Designs am PC | 4 PT |
| 3.3 | Frontend Tablet | Anpassung für Touch-Steuerung | 3 PT |
| **4.0** | **Test & Abschluss** | | **8 PT** |
| 4.1 | Testing | Tests auf Fehler und Benutzerfreundlichkeit | 4 PT |
| 4.2 | Finalisierung | Fehlerbehebung (Bugfixing) | 2 PT |
| 4.3 | Präsentation | Vorbereitung der Abschlusspräsentation | 2 PT |
| | **GESAMT** | | **ca. 40 PT** |

### 6.3 Notwendige Materialien & Ressourcen
Für die erfolgreiche Durchführung werden folgende Ressourcen benötigt:

**Hardware:**
* Laptops der Teammitglieder
* Ggf. Tablet zum Testen der Touch-Funktionen

**Software & Tools:**
* **Entwicklungsumgebung (IDE):** Visual Studio Code, Eclipse 
* **Versionierung:** Git & GitHub (zur gemeinsamen Arbeit am Code)
* **Design:** PowerPoint oder Handskizzen (für Entwürfe der Benutzeroberfläche)
* **Kommunikation:** WhatsApp / Teams (für Absprachen)

**Tech-Stack (Vorläufig):**
* **Programmiersprache:** Java (oder Python)
* **Datenbank:** SQL oder lokale Dateien
* **Bibliotheken:** Standard-Bibliotheken für GUI (Benutzeroberfläche) und Bildverarbeitung

---

## 7. Business Model Canvas

[BusinessModelCanvas.xlsx](https://github.com/user-attachments/files/24125758/BusinessModelCanvas.xlsx)

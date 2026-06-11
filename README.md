# KI-gestuetzter Bewerbungsassistent mit Human-in-the-Loop

Automatisierter Workflow zur Jobsuche, CV-Stellen-Matching, Unternehmensanalyse 
und Erstellung individueller Bewerbungsdokumente – unterstützt durch n8n, 
KI-Agenten und ein Human-in-the-Loop-Konzept.

## Was das System tut

- **Automatisierte Jobsuche** über Jobbörsen und APIs
- **CV-Stellen-Matching** mit Scoring (Schwellenwert ≥ 7/10)
- **Unternehmensanalyse** (Branche, Kultur, Benefits)
- **Dokumentengenerierung** (Anschreiben, CV, Bewerbungsbooklet)
- **Human-in-the-Loop** – Freigabe vor jedem Export

## Was das System NICHT tut

- Kein autonomes Versenden von Bewerbungen
- Keine finalen Karriereentscheidungen durch die KI
- Kein Ersatz menschlicher Urteilsfähigkeit

## Tech-Stack

| Tool | Zweck |
|------|-------|
| n8n | Workflow-Orchestrierung |
| Claude / ChatGPT | Textgenerierung & Matching |
| Python | Datenverarbeitung & Scoring |
| JSON / Markdown | Konfiguration |

## n8n-Workflow
Platzhalter gesetzt für WebhookID: "YOUR_WEBHOOK_ID_HERE"

## Status

🚧 MVP in Entwicklung

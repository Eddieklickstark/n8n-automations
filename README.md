# n8n-automations

N8N workflow automations, scripts and API integrations managed with Claude Code.

## Projektstruktur

```
n8n-automations/
├── workflows/     # Exportierte N8N Workflow-JSONs
├── scripts/       # Helper-Scripts und API-Calls
├── docs/          # Dokumentation
├── .env           # Umgebungsvariablen (nicht im Git)
└── .env.example   # Vorlage für Umgebungsvariablen
```

## Setup

1. Repository klonen:
   ```bash
   git clone https://github.com/Eddieklickstark/n8n-automations.git
   cd n8n-automations
   ```

2. `.env` Datei erstellen (oder `.env.example` kopieren):
   ```bash
   cp .env.example .env
   ```

3. Umgebungsvariablen in `.env` eintragen:
   ```
   N8N_API_KEY=dein_api_key
   N8N_BASE_URL=https://deine-n8n-instanz.com
   ```

## Umgebungsvariablen

| Variable | Beschreibung |
|----------|--------------|
| `N8N_API_KEY` | API-Key für die N8N-Instanz |
| `N8N_BASE_URL` | Basis-URL der N8N-Instanz |

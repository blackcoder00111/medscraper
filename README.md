# Medscraper

A static web app for AI-assisted medical documentation.

## Run locally

1. Open `c:\Users\USER\Desktop\Medscraper` in your browser.
2. Open `index.html` directly, or run a local server:

```bash
cd "c:\Users\USER\Desktop\Medscraper"
npm install
npm start
```

3. Visit `http://127.0.0.1:8080`.

## Notes

- The app stores user data in `sessionStorage` and is browser-session scoped.
- OpenAI and Notion API keys are required for generating notes and syncing.
- Voice dictation uses the OpenAI Whisper API with the saved OpenAI key.

## What works

- login / registration flow
- AI SOAP note generation via OpenAI chat completions
- voice transcription via Whisper
- Notion page creation via Notion API
- local settings and user profile editing

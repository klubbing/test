# Hinweise für Claude

## Sprache
- Feedback, Reports und Zusammenfassungen auf **Deutsch** schreiben.

## AI-Visibility-Audits
- Die Antworten von **ChatGPT, Gemini und Perplexity** über den **Claude-Browser (Claude in Chrome)** abrufen. Eine Websuche nur als Proxy verwenden, wenn der Browser nicht verfügbar ist, und das im Report kennzeichnen.
- Claude in Chrome gibt es nur in lokalen Sessions. In Cloud-Sessions (claude.ai/code) blockiert die Netzwerk-Policy chatgpt.com, perplexity.ai und gemini.google.com.
- Ablauf im Browser:
  1. Für jeden Prompt aus dem Panel einen **neuen Chat** öffnen. Wenn möglich ohne Personalisierung oder Memory (z. B. temporärer Chat in ChatGPT).
  2. Prompt wörtlich einfügen und die vollständige Antwort samt Quellen-Links kopieren.
  3. Rohantworten in `audits/<marke>/<datum>/<assistent>.md` ablegen.
- Scoring je Antwort:
  - Marke genannt (j/n)
  - Position
  - Sentiment (+/0/–)
  - zitierte Quellen-URLs
  - genannte Wettbewerber
- Danach Scorecard je Assistent, Citation-Map und Maßnahmenliste aktualisieren.

## Laufende Audits
- `ai-visibility-audit-prohibited-shop.md`: Prohibited (prohibited.shop). Die Baseline vom 07.10.2026 ist ein Proxy, die Browser-Messung steht noch aus. Das Prompt-Panel steht in Abschnitt 5.
- `ai-visibility-audit-1komma5grad.md`: 1KOMMA5° (1komma5.com). Die Baseline vom 12.10.2026 nutzt echte Antworten aus Google AI Overviews und AI Mode via Ahrefs Brand Radar. ChatGPT, Gemini und Perplexity sind ein Proxy aus Ahrefs-Zitatzählungen und Websuche, die Browser-Messung steht noch aus. Das Prompt-Panel steht in Abschnitt 6, die Rohdaten liegen in `audits/1komma5grad/2026-10-12/`.

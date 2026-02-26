# Laurie Chatbot (Elena)

AI conference assistant for CCWC 22nd Annual 2026 Career Strategies Conference. React frontend (index.html) talks to n8n webhook. Deployed on Vercel (static site).

- Webhook: `https://n8n.btb-ai.cloud/webhook/laurie-chatbot`
- Vercel: `https://laurie-chatbot.vercel.app`
- GitHub: `https://github.com/benreeder-coder/laurie-chatbot`
- Contact email: `sponsor@ccwomenofcolor.org`

## Session Context

> Last updated: 2026-02-26

### Active Work
1. [CLEANUP] ~60 untracked screenshot/debug PNGs in repo root need pruning

### Gotchas
- `system-prompt.txt` is the source of truth but n8n has its own copy pasted into the chainLlm node -- they can drift
- n8n workflow uses OpenAI (gpt-5.2) with web search, not the standard BTB AI OpenRouter setup

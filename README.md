# 🔭 StartupScout-Agent — Product Hunt analyst & ideator inside n8n

StartupScout-Agent is a **chat-first automation** that lives entirely inside your n8n instance.  
Talk to it in the n8n 💬 panel and it will:

1. **Fetch today’s Product Hunt launches.**  
2. **Enrich each startup** (tagline, description, makers, up-votes, topics, links).  
3. **Answer your questions** about any of those launches.  
4. **Invent spin-off ideas** on demand.  
5. **Remember the conversation context** so follow-ups feel natural.

Powered by an **AI Agent** node, one custom tools (retriever), and OpenAI GPT-4o.

## ✨ Features

| Capability | How it works |
|------------|--------------|
| **Daily data pull** | RSS → Code clean-up → Product Hunt API mirror → merged JSON |
| **Detail lookup** | Tool startup details returns full JSON for a given startup name |
| **Spin-off ideation** | Generates spinoffs to propose 3 derivative product ideas |
| **Multi-tool reasoning** | OpenAI-Functions agent decides which tool(s) to call per user prompt |
| **Zero external UI** | All chat happens in n8n’s built-in Chat sidebar—no Slack/Telegram needed |

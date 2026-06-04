# Hermes

An autonomous AI agent that runs on your own server.  
No cloud. No subscription. No company reading your data.  
Just yours — running quietly in the background.

-----

## What it does

Most AI tools ask you to go to them.  
Hermes comes to you.

It lives on your machine, remembers what it learns about your life, and handles things without you needing to be there. The longer it runs, the more useful it gets.

People use it for things like:

- **Planning** — goes through your notes and tasks and tells you what actually needs attention today
- **Studying** — pulls out what matters from everything you’ve read, flags what you haven’t reviewed
- **Creating content** — drafts, edits, organises ideas while you’re doing something else
- **Working** — handles follow-ups, summarises, clears the backlog you’ve been ignoring
- **Cooking & daily life** — reminders, suggestions, anything routine that doesn’t need your brain

You talk to it however is easiest. A message on Telegram. A line in the terminal.  
It replies, acts, and moves on.

-----

## How it works

Hermes runs locally on a server you control — a spare laptop, a home server, a VPS.  
You give it context: your tasks, your notes, what you’re working on.  
It remembers all of it, builds on it over time, and reaches out when something needs you.

There’s no app to open. No dashboard to check.  
It handles the boring parts. You focus on the things that matter.

-----

## What it runs on

|Component          |Details                                                            |
|-------------------|-------------------------------------------------------------------|
|**Language model** |`[your model — e.g. Llama 3, Mistral, Gemma]` via Ollama           |
|**Agent framework**|`[e.g. LangChain / CrewAI / custom]`                               |
|**Memory**         |`[e.g. local vector store, SQLite, plain markdown files]`          |
|**Messaging**      |Telegram bot (primary), terminal                                   |
|**Runs on**        |`[your server spec — e.g. Mac Mini M2, Ubuntu VPS, Raspberry Pi 5]`|
|**Requires**       |`[e.g. Python 3.11+, Ollama, 8GB RAM minimum]`                     |

-----

## Getting started

> This is not a plug-and-play install. It’s a personal system —  
> built around one person’s life. You’ll need to adapt it to yours.

```bash
git clone https://github.com/[yourusername]/hermes
cd hermes
# follow setup.md for full configuration
```

Full setup guide → [`setup.md`](./setup.md)  
What you’ll need → [`requirements.md`](./requirements.md)

-----

## Philosophy

Most tools are built to keep you dependent on them.  
Monthly fees. Your data on their servers. Their terms, not yours.

Hermes is the opposite.  
It runs on your hardware. It knows only what you tell it. You own everything — the model, the memory, the outputs.

It’s not smarter than the big cloud AI systems.  
But it’s yours. And that’s the point.

-----

## Follow along

Building this in public on Instagram → [@by.kaushal](https://www.instagram.com/by.kaushal?igsh=NWsyOHFzZWs5Zmpj&utm_source=qr)

-----

*Built in Mumbai.*
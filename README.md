For test

# Recall Bot

Recall Bot is a personal Telegram-based learning assistant designed to improve long-term memory through **spaced repetition** and **active recall**.

Instead of simply reminding the user to review information at fixed intervals, the system schedules reviews based on the user's previous recall performance and the estimated optimal time for the next review.

The goal is to build a lightweight personal knowledge-retention system that helps transform things you learn into long-term memory.

## Core Ideas

* **Active Recall** — retrieve information from memory instead of passively rereading it.
* **Spaced Repetition** — review information at increasing intervals to improve long-term retention.
* **Adaptive Scheduling** — adjust future review times based on how well the information was remembered.
* **Personal Knowledge Management** — store concepts, notes, reminders, and review history in one place.
* **Reliable Persistence** — keep learning data safe through database backups and recovery mechanisms.

## Planned Architecture

```text
Telegram
   ↓
Python Bot
   ↓
Recall & Scheduling Engine
   ↓
MongoDB
   ↓
Backup / Recovery
   ↓
GitHub
```

The project is designed to remain lightweight, self-hostable, Dockerized, and easy to recover on a new Linux server.

## Long-Term Goal

The long-term goal is to evolve Recall Bot from a simple reminder bot into a personal intelligent learning system capable of determining:

> What should I review, when should I review it, and how should I review it?

Future versions may include adaptive spaced-repetition algorithms such as **FSRS**, review analytics, automatic question generation, tagging, knowledge organization, and AI-assisted active-recall exercises.

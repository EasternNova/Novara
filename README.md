# 📚 Novara — AI-Powered Reading Companion

**Novara** is an intelligent reading ecosystem that combines a **digital library, AI reading assistant, annotation system, and habit-building tools** into one seamless experience.

> 🚀 *Read smarter. Understand deeper. Never lose track of your books again.*

---

## 🌟 Features

### 📖 1. Personal Digital Library

* Add and manage books easily
* Auto-fetch book metadata (title, author, pages, description)
* Organize by:

  * Status: `Will Read`, `Reading`, `Completed`
  * Format: `PDF`, `Physical`, `Hardcover`, `Ebook`
* Add ratings, reviews, and summaries

---

### 🔍 2. Smart Book Discovery

* Automatic **series detection**
* One-click add for entire book series
* AI-powered recommendations based on:

  * Reading history
  * Genres
  * Authors

---

### 📊 3. Reading Tracker & Analytics

* Track:

  * Current page
  * Reading sessions
  * Time spent reading
* View insights:

  * Books read per month
  * Reading time by category
  * Pages per day

---

### 📄 4. PDF Reader & Annotation

* Upload your own PDFs (no copyright issues)
* Features:

  * Highlight text
  * Underline
  * Add notes
  * Draw & annotate
  * Bookmark pages

---

### 🤖 5. AI Reading Companion (Core Feature)

Interact with your book in real time:

* ✨ Explain difficult paragraphs
* 🧠 Character reminders (no spoilers)
* 📚 Summarize progress so far
* 🔤 Vocabulary explanations

> Makes complex books easy and enjoyable

---

### 🛒 6. Book Buying Assistant

* After finishing a book:

  * Get prompted to purchase
* Compare real-time prices across platforms
* Add books to your personal cart

---

### 🎮 7. Gamified Reading System

Inspired by habit-building apps:

* 🔥 Daily reading streaks
* ⚡ XP & leveling system
* 🗺️ Reading journey map
* 📅 Reading heatmap
* 🏆 Achievements & challenges

---

### 🧠 8. AI Personalization

* Learns your reading behavior
* Identifies your reading personality
* Adapts recommendations automatically

---

## 🏗️ Tech Stack

### Frontend

* Flutter / React Native

### Backend

* Supabase (PostgreSQL + Auth + Storage)

### AI Layer

* OpenAI API

### APIs

* Google Books API
* Open Library API

---

## 🗄️ Database Overview

Core tables:

```
users
books
authors
series
categories
book_categories

user_library
reading_progress
reading_sessions

pdf_files
annotations

book_prices
cart
recommendations
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/novara.git
cd novara
```

---

### 2. Install dependencies

```bash
npm install
# or
flutter pub get
```

---

### 3. Setup environment variables

Create a `.env` file:

```
SUPABASE_URL=your_url
SUPABASE_KEY=your_key
OPENAI_API_KEY=your_key
```

---

### 4. Run the app

```bash
npm run dev
# or
flutter run
```

---

## 📈 Roadmap

### Phase 1 — Core Library

* Book management
* Metadata fetching

### Phase 2 — Discovery

* Series detection
* Recommendations

### Phase 3 — Tracking

* Reading progress
* Analytics

### Phase 4 — Reader

* PDF upload
* Annotation tools

### Phase 5 — AI Layer

* AI explanations
* Summaries
* Vocabulary

### Phase 6 — Commerce

* Price comparison
* Book cart

### Phase 7 — Gamification

* Streaks
* XP system
* Challenges

### Phase 8 — Personalization

* AI reader profiling

---

## 🔒 Copyright & Safety

Novara **does NOT host or distribute copyrighted books**.

✔ Users upload their own PDFs
✔ Only metadata is stored
✔ External links used for purchases

---

## 💡 Vision

Novara is not just a book tracker.

It is:

```
AI Reading Companion
+ Personal Library
+ Learning Tool
+ Habit Builder
+ Discovery Engine
```

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch
3. Make your changes
4. Submit a PR

---

## 📄 License

MIT License

---

## ✨ Author

Built with ambition to redefine how people read.

---

> 📚 *“A reader lives a thousand lives. Novara helps you remember them all.”*

---

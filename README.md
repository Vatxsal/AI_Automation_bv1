# 🚀 AI-Powered Tech News Email Automation

An end-to-end **email newsletter automation** built using **Make.com** that fetches the latest tech news from TechCrunch, processes and summarizes it using open-source AI models, and delivers a **clean, professional HTML daily digest** directly to Gmail.

This project is designed to be **fully automated, cost-efficient, and production-ready**.

---

## 📌 Project Overview

This automation handles the complete pipeline of a tech newsletter:

- Collects real-time tech news via RSS
- Prevents duplicate article delivery
- Generates AI-based summaries
- Formats content into a single, professional HTML email
- Sends a daily digest automatically via Gmail

All of this is achieved **without using any paid APIs or backend servers**.

---

## 🧠 Why This Project?

Professionals, founders, and students often want:
- Curated tech news
- Clean summaries
- One email instead of multiple websites
- Zero manual effort

This project solves that by delivering a **daily, readable, inbox-ready tech digest** — automatically.

---

## 🛠️ Tech Stack

| Category | Tool |
|-------|------|
| Automation Platform | Make.com |
| News Source | TechCrunch RSS |
| Duplicate Handling | Google Sheets |
| AI Summarization | Hugging Face (facebook/bart-large-cnn) |
| API Integration | HTTP Module |
| Text Processing | Make Tools |
| Email Formatting | Text Aggregator (HTML) |
| Email Delivery | Gmail |
| Scheduling | Daily Cron (Make.com) |

---

## 🔄 Workflow Architecture

Scheduler
   ->
RSS – Retrieve TechCrunch Feed
   ->
Google Sheets – Search Rows (Duplicate Check)
   ->
Google Sheets – Add Row (Store New Articles)
   ->
Tools – Text Cleaning & Processing
   ->
HTTP – AI Summarization (Hugging Face)
   ->
Tools – Post-processing
   ->
Text Aggregator – HTML Email Generation
   ->
Gmail – Send Daily Digest

---

## ⚙️ Key Features

✅ Fully automated daily workflow

✅ Duplicate article protection using Google Sheets

✅ AI-generated summaries via Hugging Face

✅ Single professional email header & footer

✅ Clean, readable multi-article layout

✅ Click-through “Read full article” links

✅ Gmail-safe Raw HTML formatting

✅ RSS article limit control (e.g., Top 5 news)

✅ No paid services or subscriptions

---

## 📧 Sample Email Output
Each email includes:-

📰 Newsletter-style header (shown once)

📌 Multiple curated tech headlines

📝 Concise summaries

🔗 Direct article links

🕒 Auto-generated date

🔻 Professional footer with source attribution

Designed for clarity, credibility, and impact.

---

## 📸 Screenshots & Demo
This repository contains:

📊 Make.com workflow overview

🧩 Module-by-module scenario setup

📩 Final email output in Gmail

---

## 🔐 Security & Cost

No sensitive user data stored

API keys handled securely inside Make.com

No external backend servers

Uses only free and open-source AI models

Optimized for Make.com free tier usage

---

👨‍💻 Author

Vatsal Mishra

Final Year B.Tech Student 

📬 Feel free to connect or reach out!

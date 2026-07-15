# EVERYDAY+ — Project Memory

## What This Is
Everyday+ is an offline-first Android utility app that replaces 20 separate
apps with one. Notes, to-do, habits, expenses, health trackers, QR tools,
password vault, and more — all local, no account, no ads, privacy-first.

## Tech Stack
- Kotlin + Jetpack Compose (Material Design 3)
- MVVM architecture, Navigation Compose
- Storage: Gson JSON local files (NO Room, NO Kapt, NO database)
- Background: WorkManager (only if strictly needed)
- Build: GitHub Actions only (no local builds)
- Repo: github.com/sharif2910/EverydayPlus (confirm exact name)
- Dev environment: Termux, separate folder from JARVIS/EDITH project

## Golden Rules (never break)
- One Termux command at a time, wait for result
- Never use sed — Python rewrite only, encoding='utf-8'
- Always read full file before editing; rewrite complete files, never patch
- Heredocs in small chunks, max 100 lines
- Never add Room/Kapt/any database — Gson JSON only
- Same error twice = stop patching, rewrite the whole file
- Never break a working feature while fixing another
- Never mark a phase ✅ until Sharif has tested it on device
- Never mix phases — finish and confirm one before starting next
- After every green build: update this file's STATUS section
- On "handover": rewrite this whole file so a new AI needs zero explanation

## PHASE PLAN
- [ ] Phase 0 — Project Setup: repo, GitHub Actions CI, empty Compose app
      boots, base navigation, theme (light/dark), folder structure
- [ ] Phase 1 — Core Tools: Notes, To-do List, Shopping List, Calculator,
      Countdown Timer, Flashlight, QR Scanner/Generator, Unit Converter
- [ ] Phase 2 — Productivity+: Habit Tracker, Expense Tracker (+ charts),
      Savings Goals
- [ ] Phase 3 — Health: Water Reminder, Medicine Reminder, BMI Calculator,
      Sleep Tracker, Journal (mood + photos)
- [ ] Phase 4 — Security & Docs: Password Vault (encrypted), App Lock,
      PDF Scanner, Image-to-PDF
- [ ] Phase 5 — Personal & Settings: Birthday/Anniversary Reminder, Daily
      Quotes, Emergency Contacts, Backup/Restore, Theme colors
- [ ] Phase 6 (future, not started) — Cloud backup, Widgets, AI assistant,
      voice notes, cross-device sync

## STATUS (update after every green build)
Current phase: Phase 0 — not started
Last confirmed green build: none yet
Last thing Sharif tested & confirmed: none yet

## SESSION LOG (newest on top, 1-3 lines per entry)
- [2026-07-15] Project created. Blueprint received. Phase plan written.

## NEXT STEPS
1. Create GitHub repo (sharif2910/EverydayPlus)
2. Set up Termux project folder separate from JARVIS/EDITH
3. Add GitHub Actions workflow for build
4. Scaffold empty Compose app, confirm first green build

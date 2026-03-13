# ARMORY — Firearms Inventory System

A tactical firearms inventory management PWA built as a single-file web app.

## Features
- Add, edit, and delete firearms with full spec sheets
- AI-powered descriptions and spec lookup via Groq API
- Camera scanning to identify firearms and auto-fill specs
- Range round tracking and session logging
- Maintenance checklists with date logging
- Accessories tracker
- Import / Export via Excel (.xlsx) and CSV
- Works offline as an installable PWA on Android and iOS

## Live App
👉 https://johnlaz.github.io/armory

## Setup
1. Visit the live app link above in Chrome on Android
2. Tap the install banner or ⋮ menu → Add to Home Screen
3. Add your free Groq API key in ⚙ Settings (get one at console.groq.com)

## Tech
- Vanilla HTML/CSS/JS — no framework, single file
- Groq API (Llama 3.3 70B + Llama 4 Scout Vision)
- SheetJS for Excel import/export
- PWA with service worker for offline support

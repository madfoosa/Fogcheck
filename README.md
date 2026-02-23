# FogCheck

A Progressive Web App (PWA) for tracking daily cognitive function and energy levels — designed for people living with brain fog from conditions like ME/CFS, Long COVID, or MS.

## What it does

FogCheck runs short cognitive assessments and combines them with self-reported symptoms to classify each day:

- **Clear Day** — Near-baseline cognition, full activity possible
- **Managed Day** — Mild impairment, pace yourself
- **Fog Day** — Significant impairment, reduce demands
- **Rest Day** — Severe impairment, prioritise recovery

After 14 sessions, scores are compared against your personal baseline (not generic standards), so the app adapts to your normal.

## Assessments

**Quick Check (~2 min):** Verbal Fluency + Reaction Time + Self-Report

**Full Assessment (~8 min):** All five tests:
1. Verbal Fluency — name items from a category in 60 seconds
2. Reaction Time — tap coloured circles across 5 rounds
3. Memory Sequence — recall sequences of coloured shapes
4. Attention Grid — find target letters in a 6×6 grid
5. Self-Report — rate fog, energy, pain, and sleep (1–5 scale)

## Features

- Personalised baseline calibration (rolling average of last 20 sessions)
- Trends chart and day-type distribution over 30 days
- Customisable guidance messages for each day type
- Data export for healthcare providers
- Works offline (service worker caching)
- Installable to home screen on iOS and Android

## Usage

Open `index.html` in a browser — no build step or server required. On iOS, tap **Share → Add to Home Screen** to install as a PWA.

All data is stored locally in the browser (`localStorage`). Nothing is sent to any server.

## Browser support

Modern mobile browsers (Safari on iOS 15+, Chrome on Android). Desktop browsers work but the app is optimised for mobile.

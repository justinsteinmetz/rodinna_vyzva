https://justinsteinmetz.github.io/rodinna_vyzva/

# Rodinná Výzva — Prague Family Challenge

A collaborative scavenger hunt for families visiting Prague. Designed as a multi-day quest rather than a single itinerary — tasks are spread across the city and can be completed in any order over the course of a visit.

## Overview

30 tasks. 50 points. No time limit.

Tasks range from the immediately obvious to the genuinely cryptic. Some require research before you leave. Some require luck. Some require commitment. Evidence is required for every task — no evidence, no points.

## Scoring

| Type | Points |
|------|--------|
| Photo | 1–2 pts |
| Find | 1–2 pts |
| Film | 2 pts |
| Interact | 2 pts |

Higher-value find tasks reflect genuine difficulty — the golem, the svíčková, the Zeppelin, the billiards room, and the final sunset are all worth 2 pts. The closing task is worth 3.

## How to Use

1. Open the HTML file in a browser on a phone.
2. Enter your family name and press **Enter** — it becomes your nameplate for the visit.
3. Tap a task to mark it complete. Tap again to undo.
4. Progress and score update live.
5. The family name and completed tasks are saved locally — closing the browser and returning later will restore your progress.
6. To change your family name, tap the nameplate. To clear it, tap **Clear**.

## Notes on the Tasks

A handful of tasks are deliberately cryptic and give no location. This is intentional — the research is part of the quest. The adults in the group will recognise some references immediately; others will require a search. The children will often get there first.

The two Vyšehrad tasks (21 and 22) work well as a half-day anchor. Tasks 25 and 29 reward those who explore beyond the tourist circuit. Task 30 should be saved for last.

## Technical

Single HTML file. No dependencies, no server, no installation. Works offline once loaded. Progress stored in `localStorage` under key `pfc_v1`.

Fonts loaded from Google Fonts (Cinzel, IM Fell English, Playfair Display) — requires an internet connection on first load. Subsequent loads will use cached fonts.

Designed for mobile (phone-first). Functions on desktop but the experience is optimised for a screen you carry.

## Deployment

Drop the HTML file in any static hosting environment. GitHub Pages works fine — rename to `index.html` or link directly.

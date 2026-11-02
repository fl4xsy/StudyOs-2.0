# StudyOS — 91-Day PCM Planner

An offline-first dark-mode Progressive Web App for the 91-day Class 11 PCM plan.

## Included
- Full date-wise plan: 2 Nov 2026–31 Jan 2027 (91 days, 273 base tasks)
- Dashboard with daily progress, overall completion, streak and subject progress
- Interactive daily checklist and custom task creation
- Calendar with day-by-day completion status
- Analytics: 91-day completion line chart, weekly bar chart, activity heatmap and subject comparison
- D+1 / D+7 / D+21 spaced revision queue
- Editable routine and daily notes
- JSON export/import backup
- LocalStorage persistence and Service Worker offline cache

## Run locally
Service workers require localhost or HTTPS:
```bash
python -m http.server 8000
```
Open `http://localhost:8000`.

## Install on Android
1. Host this folder on an HTTPS static host (GitHub Pages works).
2. Open the URL in Chrome on Android.
3. Browser menu → Install app / Add to Home screen.

## Publish to GitHub
Create a public repository, upload all files, add an MIT LICENSE if you want to publish under MIT, then enable GitHub Pages under Settings → Pages.

## Plan caveat
The 91 daily entries are taken from the user's existing Notion plan. That plan itself was marked provisional because the school's annual syllabus had not been confirmed. Verify the chapter list against the school syllabus and edit/remove excluded topics. Maths entries remain tied to the current class topic rather than guessing chapter names.

## Sleep note
The routine view preserves the previously stated time windows as editable draft data, but flags the conflict between a 4 AM start and 11 PM bedtime. Teenagers should protect 8–10 hours of sleep.

## Privacy
Progress is stored locally in this browser. There is no cloud sync or account. Export backups regularly; clearing browser storage can erase local progress.

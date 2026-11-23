# Nexus Call Center — نسخة تجريبية (Demo)

Arabic-first contact-center management demo. **All data is simulated** and stored in the visitor's own browser (localStorage). Built to present the concept to management — not a production system.

## What it shows
- Demo logins with roles: admin / supervisor / quality (QA) / agents — password `1234` for all demo accounts
- Agent desktop: statuses (ready / break with reasons / after-call work / on call), simulated incoming calls, wrap-up dispositions
- Optional microphone recording of demo calls (with explicit consent), playable and downloadable from the call log
- Live supervisor wallboard: agent statuses, time-in-status, calls today, average handle time
- Shift scheduling (weekly grid, morning/evening/night/off)
- Call log with search and filters, QA scorecards (5 criteria + notes)
- Reports: answered/abandoned, service level, AHT, QA averages, per-agent and per-queue breakdowns
- Arabic (default, RTL) and English UI

## Honest limits
- Simulation: no real telephony, no real customer calls
- Single-device: data lives in the browser; no shared backend, no real authentication security
- Automatic recording storage to an external drive folder works only in desktop Chrome (File System Access API), not on mobile browsers; a production system would store recordings on a company server/NAS

## Run
Open `index.html` or the GitHub Pages deployment. Zero dependencies.

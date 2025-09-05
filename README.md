# MBS Logistics (PWA) — GitHub Pages Ready

A single-page, offline-capable logistics app for iPad. Add to Home Screen and run like an app. Data is stored locally in the browser (localStorage) with export/import tools.

## Features
- Work Orders, Clients, Technicians & Availability, Services, Deposits, Inventory
- Auto-create **20% deposit** on `Scheduled` status
- Block `Completed` until deposit is **Paid**
- Enforce **24h** deposit rule (must be paid inside 24 hours of service)
- Offline support via Service Worker
- PWA manifest + Apple touch icon
- Dark navy MBS theme

## One‑Click Deploy on GitHub Pages
1. Create a new GitHub repo (e.g., `mbs-logistics`).
2. Upload all files from this folder (or push via git).
3. Go to **Settings → Pages** and set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (root)
4. (Optional) Enable the provided GitHub Actions workflow:
   - Ensure the action is enabled under **Actions**.
   - Or just use the branch-based Pages without Actions.
5. Open your Pages URL (e.g., `https://<you>.github.io/mbs-logistics/`).
6. On iPad (Safari): Share → **Add to Home Screen**.

## Local Development
Open `index.html` locally, or serve with any static server (e.g., `python -m http.server`).

## Data
All data is local. Use **Settings → Export** to back up JSON/CSV.

## License
MIT

# File Transfer Tracker / מעקב העברת קבצים

A Hebrew/English app for tracking file transfers by date and time range.

## Features
- Create lists per date, each with multiple time ranges
- Sort the date list by the list's date or by when it was added (grouped by day), newest or oldest first
- Add 3-digit file IDs and track status: Ready / Working / Lost
  - Typing the 3rd digit adds the ID automatically; paste a whole list at once
  - Duplicate IDs are blocked across all time ranges of a date
- Filter chips + stats counter per time range, "mark rest ready" bulk action
- Undo for removed IDs, deleted time ranges and bulk changes
- Export a formatted Hebrew message ready to copy-paste
- Dark mode toggle
- Language toggle (UI in EN/HE — export always in Hebrew)
- Data saved per device in browser localStorage

## Usage
Open `index.html` directly in any browser — no install needed.  
Data is saved locally in your browser (localStorage).

**Live site:** https://poh-rull.github.io/file_tracker/

# Almost Perfect UI

A modern, premium SaaS dashboard that looks high-end but intentionally contains broken, unreliable logic.  
Dark mode, glassmorphism, smooth animations, and charts—all crafted in plain HTML, CSS, and vanilla JS.

**Features:**

- **To-do List:** Add, delete, and toggle tasks.  
- **Progress Bar:** Shows random progress (never the real state).
- **Daily Statistics:** Always calculated incorrectly.
- **Timer:** Counts faster or slower than real time.
- **Save button:** Pretends to save but actually discards all app data.
- **Chart:** Displays nonsense statistics.

**Simple Database Simulation (but never permanently saved):**

- The dashboard uses an in-memory data structure ("simple database") to track tasks, completion, progress values, stats, and timer.
- Every change is "saved" to the fake database—but it's lost on reload or Save.
- Saving does not persist to disk or any backend database. Data is randomized, corrupted, or overwritten with illogical values on page reload or new Save.

**Intentional flaws:**
- The progress bar displays random values, ignoring real completion.
- The statistics are based on broken math and never reflect real usage.
- The timer counts time incorrectly.
- On reload, the data changes in illogical ways.
- The save button fakes saving, but always discards or corrupts current data.

**Tech stack:**
- **HTML, CSS, vanilla JavaScript**
- No frameworks, no external libraries.

---

## Usage

Clone or download this repo. Open `index.html` in any browser.

```
git clone https://github.com/Rxckzs/almost-perfect-ui.git
cd almost-perfect-ui
# open index.html in your browser
```

---

## Demo

![Screenshot](screenshot.png)

---

## Notes

- The app does not use a real database; all tracking is simulated and intentionally unreliable.
- No data is permanently stored or retrievable.
- Designed as a playful or demo UI for premium SaaS dashboards with obvious intentional anti-patterns.

---

## License

MIT

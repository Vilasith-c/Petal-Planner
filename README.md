# Student Companion 🌷
### A Personal Productivity Dashboard for Students

A lightweight, self-contained single-page web application designed to help students organize their daily academic life.

---

## 🌟 Key Features

1. **🎏 Today's Tasks**
   - Add new daily assignments and to-dos
   - Interactive checkbox with strikethrough animation
   - Task deletion and friendly empty-state messaging
   - Automatic `localStorage` persistence

2. **⏰ Study Timer (Pomodoro Technique)**
   - 25-minute focus sessions with automatic switch to 5-minute breaks
   - Start, Pause, and Reset controls
   - Counter tracking completed study sessions
   - Synthesized gentle bell chime via the Web Audio API on session completion
   - Accurate timer recovery even across page refreshes

3. **📝 Quick Notes**
   - Ruled lined paper aesthetic matching a school notebook
   - Automatic debounced background autosaving
   - Live `saved ✓` status indicator

4. **📖 Subject Progress Tracker**
   - Track completed chapters vs. total syllabus requirements
   - Interactive `+` and `-` stepper buttons
   - Dynamic progress bar calculation
   - Ability to add custom subjects with customizable chapter targets

5. **🎯 Daily Goal Tracker**
   - Configurable target study hours for the day
   - Log hours studied with visual percentage bar
   - Celebration message when the daily goal is reached

6. **🕒 Live Header**
   - Real-time digital clock and current date display
   - Dynamic time-of-day greeting (Morning, Afternoon, Evening, Midnight)

---

## 🚀 How to Run

Because Student Companion is built with standard HTML5, CSS3, and Vanilla JavaScript, **no installation, build step, or server is required**:

1. Simply double-click `index.html` to open it directly in Google Chrome, Microsoft Edge, Mozilla Firefox, or Safari.
2. Alternatively, serve it via any static local server (e.g. `python -m http.server 3000` or `npx serve`).

---

## 🎨 Aesthetics & Design

- **Typography**: Google Fonts [`Caveat`](https://fonts.google.com/specimen/Caveat) (warm handwritten script) and [`Quicksand`](https://fonts.google.com/specimen/Quicksand) (clean rounded sans-serif).
- **Color Palette**: Warm cream paper background (`#FAF5ED`), soft sage green accents (`#5C7E65`), terracotta timer tones (`#C46D67`), and pastel washi tape headers.
- **Responsiveness**: Fluid layout supporting both desktop 2-column displays and mobile viewports.

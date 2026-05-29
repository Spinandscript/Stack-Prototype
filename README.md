# Stack — Interactive UI Prototype
https://spinandscript.github.io/Stack-Prototype

A mobile-first interactive prototype for **Stack**, a fitness and mindfulness app that combines physical training (Outer Stack) with emotional intention-setting (Inner Stack).

Built from the Stack Software Requirements Specification (SRS) as a class group project, then prototyped as a fully interactive front-end demo.

---

## 📱 Screens

### Build Screen (`build-screen.html`)
Plan your week before it starts.
- Choose **Outer Stack**: select workout days (1–5), training focus (Cardio, HIIT, Strength, Mobility), and goal — auto-generates a weekly plan
- Choose **Inner Stack**: pick an emotional theme (Boundaries, Gratitude, Self-Love, etc.) and receive a personalized reflection prompt
- Live **brick visualization** updates as you make selections — blue for Outer Stack, purple for Inner Stack

### Activity Log (`activity-log.html`)
Track your sessions in real time.
- **Set-by-set workout checklist** with per-exercise progress badges (Pending / Partial / Done)
- Live **progress bar** and brick visualization tied to completion
- **Partial save** — exit mid-session and resume later
- **Post-workout mood check** (😔 😐 🙂 😄) with optional notes
- **Inner Stack reflection** with minimum character validation
- **Session history** with type, date, mood, and complete/partial status

---

## 🚀 Running Locally

No build step, no dependencies, no Node.js required.

```bash
git clone https://github.com/YOUR_USERNAME/stack-prototype.git
cd stack-prototype
open index.html   # macOS
# or just double-click index.html in your file explorer
```

---


## 🗂 File Structure

```
stack-prototype/
├── index.html          # Landing page — links to all screens
├── build-screen.html   # Outer Stack + Inner Stack planning flow
├── activity-log.html   # Workout logging + reflection flow
└── README.md
```

---

## 🛠 Tech

- Pure HTML, CSS, and Vanilla JavaScript
- [Tabler Icons](https://tabler.io/icons) (via CDN)
- No frameworks, no build tools — just open and run

---

## 📋 About

Stack is a wellness app concept designed around the idea that physical and emotional fitness are two halves of the same practice. The **Outer Stack** handles structured training; the **Inner Stack** handles mindfulness and intention. Both feed into a shared "brick" visualization representing weekly consistency — the **Stack**.

Originally developed as a group class project. This prototype was built to bring the SRS to life interactively.

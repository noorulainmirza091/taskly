# Taskly — To-Do List App

A clean, fully featured task manager built with pure HTML, CSS, and vanilla JavaScript. No frameworks, no dependencies — just one file.

**[Live Demo →](https://your-username.github.io/taskly/)**

---

## Features

- Add, complete, and delete tasks
- Priority levels — High, Medium, Low
- Category tags — Study, Work, Personal, Health, General
- Filter by status or category
- Progress ring showing completion percentage
- Tasks saved to localStorage — survive page refresh
- Fully responsive on mobile and desktop

## How to use

1. Type a task in the input and press **Enter** (or click **+**)
2. Choose a priority and category before adding
3. Click the circle to mark a task done
4. Hover a task and click 🗑 to delete it
5. Use the filter buttons to view specific tasks
6. Click **Clear all completed tasks** to tidy up

## Run locally

No build step needed. Just open the file:

```bash
# Clone the repo
git clone https://github.com/your-username/taskly.git

# Open in browser
open taskly/index.html
```

Or drag `index.html` straight into any browser window.

## What I learned building this

- Managing state with a JavaScript array and re-rendering on every change
- Persisting data with `localStorage`
- Animating SVG with `stroke-dashoffset` for the progress ring
- CSS custom checkboxes using `appearance: none`
- Preventing XSS with an `escHtml()` helper
- Slide-out delete animations with `classList` and `setTimeout`

## Tech stack

| Layer      | Technology              |
|------------|-------------------------|
| Structure  | HTML5                   |
| Styling    | CSS3 (custom properties, Grid, Flexbox) |
| Logic      | Vanilla JavaScript (ES6+) |
| Storage    | localStorage API        |
| Fonts      | Google Fonts — Plus Jakarta Sans |

## Project structure

```
taskly/
└── index.html    # Entire app — markup, styles, and script
└── README.md     # This file
```

## Customisation

All colours are CSS custom properties at the top of the `<style>` block — easy to retheme. To add a new category, add an `<option>` to the `#categorySelect` dropdown and an emoji entry in the `catEmoji` object in the script.

---

Built by [Your Name](https://github.com/your-username) · MIT License

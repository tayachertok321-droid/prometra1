# Prometra — Claude Code Instructions

## Project Overview
Prometra is a school project web application. It was initially built as a single HTML file and is being developed into a full, scalable website with excellent mobile support.

## Stack & Constraints
- **Language:** HTML, CSS, JavaScript (vanilla unless a library is clearly needed)
- **Design approach:** Mobile-first, responsive — every change must work on small screens first
- **No frameworks required** unless explicitly requested
- **No build tools** (no webpack, vite, etc.) unless explicitly requested — keep it deployable as static files

## Core Priorities
1. **Mobile responsiveness is non-negotiable.** Every UI change must be tested against mobile viewport sizes (320px–430px).
2. **Scalability** — structure files so adding pages or features doesn't require refactoring everything.
3. **Clean code** — semantic HTML, organized CSS (use CSS variables for colors/fonts), no inline styles unless unavoidable.

## File Structure
```
prometra/
├── index.html
├── assets/
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   └── main.js
│   └── images/
└── CLAUDE.md
```

## Git Workflow
- Remote: https://github.com/tayachertok321-droid/prometra1.git
- Branch: main
- Commit messages should be concise and descriptive (e.g. "add mobile nav menu", "fix hero section overflow on small screens")

## What Claude Should Always Do
- Check mobile layout before declaring any UI task done
- Use semantic HTML tags (header, main, section, nav, footer, etc.)
- Prefer CSS Grid and Flexbox over absolute positioning
- Keep the codebase simple enough that a student can understand and present it

## What Claude Should Never Do
- Add unnecessary dependencies
- Over-engineer with frameworks not requested
- Leave broken or half-finished code in commits

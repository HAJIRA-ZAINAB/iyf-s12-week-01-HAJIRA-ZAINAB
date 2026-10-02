# Accessibility Report
Name: Hajira Zainab
Date: Oct 2026
Repo: iyf-s12-week-01-HAJIRA-ZAINAB

## What I Checked
I checked my 4 pages: index.html, about.html, projects.html, contact.html

## Tools
1. Lighthouse in Chrome (F12 > Lighthouse)
2. WAVE tool
3. I checked code myself

## Problems I Found and Fixed

### 1. Images had no alt text
Before: `<img src="...">`
After: `<img src="https://placehold.co/400x300" alt="Hajira Zainab">`
Why: Blind people need alt text to hear what image is.

### 2. No lang="en"
Before: `<html>`
After: `<html lang="en">`
Why: Tells screen reader to speak English.

### 3. Heading skipped
Before: h1 then h3
After: h1 -> h2 -> h3
Why: Headings must be in order like stairs.

### 4. Form had no labels
Before: `<input placeholder="name">`
After: `<label for="name">Full Name</label><input id="name">`
Why: Everyone needs label to know what to type.

### 5. Link text was "click here"
Before: `<a>click here</a>`
After: `<a>About Me</a>` and `<a>My GitHub</a>`
Why: Link must say where it goes.

## Final Score
Lighthouse Accessibility Score: 100/100
All 4 pages pass.

## What I Learned
Accessibility helps blind people use my site and helps Google rank my site better.

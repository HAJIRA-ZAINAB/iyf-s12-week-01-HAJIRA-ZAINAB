# Accessibility Audit Report

## Issues Found
1. Images missing alt text
2. Missing lang attribute on html tag
3. Heading hierarchy incorrect (h1 to h3)
4. Form inputs missing labels in contact.html
5. Links using "click here"

## How I Fixed Them
1. Added alt="Project 1 - Data Pipeline" etc to all 5 images in projects.html
2. Added lang="en" to <html> tag on index.html, about.html, projects.html, contact.html
3. Fixed headings to proper order h1 → h2 → h3
4. Added <label for="name">, <label for="email"> in contact.html
5. Changed link text to descriptive text like "About Me" instead of "click here"

## Tools Used
- Chrome DevTools Lighthouse
- WAVE Web Accessibility Tool

## Final Scores
- Accessibility: 100/100
- Tested pages: index.html, about.html, projects.html, contact.html

## Learnings
Accessibility makes site usable for screen readers and better for SEO.

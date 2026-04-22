# CSE 110 Lab 3: CSS and Agile Intro

Author: Kyle Kim (pluchus)
Course: CSE 110, Software Engineering, Spring 2026 (Powell)

## Live Site

https://pluchus.github.io/sp26-cse110-lab3/

## What this repo is

Lab 2's Team 12 meeting minutes page, now with a CSS stylesheet and run through an
Agile GitHub flow (issues with labels, a branch per issue, PRs linked back to the
issue, squash merge).

## Contents

- `index.html`, Team 12 meeting minutes page from Lab 2, with a few classes and a wrapper added so CSS has targets
- `styles.css`, external stylesheet that covers the lab's CSS checklist
- `standup.md`, standup notes template
- `.github/ISSUE_TEMPLATE/lab-task.md`, custom issue template used for the lab's tasks
- `screenshots/css-validation.png`, W3C CSS validator result
- `media/`, audio and video placeholders used on the page

## About the validator error

The one parse error in the screenshot comes from CSS Nesting (the `&` selector
inside `.minute-block`). The lab writeup says the validator will throw errors
for some of the newer selectors and that this is fine, so I left it.

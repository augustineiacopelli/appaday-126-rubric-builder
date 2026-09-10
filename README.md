# Rubric Builder

**App 126 of AppADay.**

Enter an assignment name and a list of grading criteria, and Claude drafts a four level rubric, Excellent, Good, Needs Work, and Missing, for each one. Every descriptor is editable right in the table before you export it.

**Live:** https://augustineiacopelli.github.io/appaday-126-rubric-builder/
**Portfolio:** https://augustineiacopelli.github.io/appaday/

## How it works

Add your Claude API key in the settings gear once, and it stays in your browser's local storage. Name the assignment, list the criteria you are grading, and hit Generate. Claude returns a rubric as structured JSON, which renders into an editable table. Click any descriptor cell to rewrite it in place. When it looks right, Copy to Clipboard writes both a formatted table and a plain text version, so pasting works whether the destination is a Word document, a Google Doc, or a plain text field.

## Built with

Vanilla HTML, CSS, and JavaScript, no frameworks, no build step. Google Fonts for type. The Anthropic API, called directly from the browser with the anthropic-dangerous-direct-browser-access header, model claude-sonnet-5.

## Part of AppADay

One complete, functional, mobile-friendly, visually polished web app, shipped every day. Full archive at [augustineiacopelli.github.io/appaday](https://augustineiacopelli.github.io/appaday/).

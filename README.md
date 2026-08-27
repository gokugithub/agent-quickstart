# Task List Web App

A simple single-page task manager built with plain HTML, CSS, and JavaScript.

## Features

- Add new tasks
- Mark tasks as complete or incomplete
- Delete individual tasks
- Clear all completed tasks
- Save tasks in browser local storage so they persist after reload
- No external libraries or dependencies

## Run it locally

1. Open `index.html` in a browser, or
2. Serve the folder with a simple local web server, for example:

```bash
python -m http.server
```

Then open `http://localhost:8000` in your browser.

## Files

- `index.html` — app structure, styling, and behavior in one file
- `README.md` — project overview and usage notes

## Notes

Tasks are stored in the browser's `localStorage`, so they remain available after refresh or reopening the page on the same browser/profile.

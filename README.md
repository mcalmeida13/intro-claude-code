# Introduction to Claude Code

Educational project: Introduction to Claude Code.

This repository is a small educational example demonstrating how Claude Code
can autonomously create files, run a local server, and make commits. It
contains a simple `index.html` page ("Hello World" on a green background
with yellow text) that was generated, served, and committed by Claude Code
without manual editing.

## Running the page locally

To view `index.html` in your browser, start a simple local HTTP server from
the project root and open it in Chrome.

### Option 1: Python's built-in server

1. Open a terminal in the project root (the folder containing `index.html`).
2. Run:
   ```
   python3 -m http.server 8000
   ```
3. Open your browser and go to:
   ```
   http://localhost:8000
   ```

### Option 2: Node's http-server

1. Make sure Node.js and npm are installed.
2. Run (no install needed, via `npx`):
   ```
   npx http-server -p 8000
   ```
3. Open your browser and go to:
   ```
   http://localhost:8000
   ```

Either option serves the current directory, so `index.html` is available at
the root path. Press `Ctrl+C` in the terminal to stop the server when done.

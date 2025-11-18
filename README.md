# Pumpkin Seed Frenzy

This repository contains a single-page pumpkin matching mini game. You can run it locally in any modern browser without additional build tooling.

## Prerequisites
- [Node.js](https://nodejs.org/) (optional, if you want to use `npx serve`) or
- Python 3 (optional, if you want to use `python -m http.server`)

Any static-file server will work—pick whichever tool you already have installed.

## Running locally
1. Clone this repository and open the folder.
2. Start a simple static server from the project root:
   - **Using Node.js**
     ```bash
     npx serve .
     ```
   - **Using Python 3**
     ```bash
     python3 -m http.server 4173
     ```
3. Open your browser to the address shown in the terminal (for example `http://localhost:4173`).
4. Interact with the pumpkins: drag them from the bin into their matching slots, watch for the seed explosions, and verify that score increments when a row is completed.

## Troubleshooting
- If nothing appears, ensure the terminal did not report a port collision and that your browser is pointing to the URL printed by the server.
- To reset the board, simply refresh the page; pumpkins are respawned on load.

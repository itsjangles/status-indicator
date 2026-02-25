# Call Status

Simple browser-based status screen inspired by Microsoft Teams presence colors. It lets you quickly switch to a large, color-coded status view that can be shown during calls.

## Requirements

- Node.js (already available in this dev container)

## Run the app

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the server:
   ```bash
   npm start
   ```
3. Open the app in your browser:
   - http://localhost:3000

## How to use

- Click one of the status buttons:
  - `Available`
  - `Busy`
  - `In a call/meeting`
  - `Do not disturb`
- After choosing a status, the page background changes and the app UI minimizes.
- Click anywhere on the page to bring the status buttons back.

## Keep the page "always on top"

This app runs in a normal browser tab. To keep it visible above other windows, use one of these options:

- **Browser extension (Chrome/Edge/Firefox):** install an "always on top" or "pin window" extension from your browser’s extension store.
- **Microsoft PowerToys (Windows):** use **Always On Top**.
  - Default shortcut: `Win + Ctrl + T` to pin/unpin the active window.

## Notes

- The server defaults to port `3000`.
- You can change the port with an environment variable, for example:
  ```bash
  PORT=4000 npm start
  ```

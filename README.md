# Grandma's Bakeria

Two standalone, single-file web apps. No build step or dependencies.

- `fall-parfait-game.html` : cartoon drag-and-drop "guess the Fall Parfait recipe" game (current project)
- `rush-order-sourcing.html` : rush order sourcing tool (earlier idea)

## Run in VS Code
1. Open this folder in VS Code (File > Open Folder).
2. Install the "Live Server" extension, right-click an .html file > "Open with Live Server".
   (Or just double-click the .html file to open it in your browser.)

## Where to edit
- Game: `WEEKLY` (secret recipes), `ING` (ingredients, emoji, colours), prize tiers in `winner()`, colours in `:root` CSS.
- Sourcing tool: `S` (suppliers), `O` (prices/stock), `R` (recipes), `SAMPLES` at the top of the script.

## Next steps (needs a backend)
Sign-ups currently save to the browser's localStorage only. Add a small server + database
(e.g. Node/Express + SQLite, or Supabase) to store members and validate coupon codes.

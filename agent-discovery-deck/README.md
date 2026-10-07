# Agent Discovery Deck

A browser-based workshop tool for identifying customer requirements for Microsoft Copilot agents, built around a deck of 87 AI scenario cards.

## How it works

1. **Workshop** – record the customer, attendees and business goals.
2. **Discover** – tag the teams in scope, their pain points and where their data lives; the app ranks the most relevant cards.
3. **Card sort** – mark each card Priority, Maybe or Not now.
4. **Requirements** – capture problem, users, agent type, knowledge sources, actions, channels, success measure, value and complexity.
5. **Backlog** – value vs complexity matrix, suggested build path, and export as summary text, CSV or a reloadable workshop file.

## Running it

It is a single static page with no build step. Open `index.html` in a browser, or publish with GitHub Pages
(Settings → Pages → Deploy from a branch → `main` / root).

Workshop data is saved in the browser's local storage only. Use **Backlog → Copy workshop file** to keep a copy.

## Files

- `index.html` – the app (HTML, CSS and JavaScript in one file, card data embedded)
- `cards/` – images of the 87 scenario cards

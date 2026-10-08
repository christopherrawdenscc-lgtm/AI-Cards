# Agent Discovery Deck

A browser-based workshop tool for identifying customer requirements for Microsoft Copilot agents, built around a deck of 87 AI scenario cards. It takes a customer from a pile of ideas to one pilot they've agreed to.

## How it works

1. **Prepare** – record the customer, attendees and business goals, then cut the deck to the cards that fit their world (about 25). Cut whole families, single cards, or keep only the Copilot-led cards.
2. **Discover** – start with their pain, not the cards. Write down 4–6 real processes, each with an owner, team and volume, then tag teams, pain points and where the data lives; the app ranks the most relevant cards left in the deck.
3. **Card sort** – the customer sorts each card into Now, Later or Not for us. A card only goes in Now once it has a home: a named process, or a team and volume.
4. **Solutions** – combine one Agentic card (the pattern) with the capability cards that do the work. Qualify each stack with one line each for who, trigger, data, action, human-in-the-loop, measure and risk, score value and feasibility, and pick a delivery tier. The app suggests the simplest tier the cards' product tags support.
5. **Pilot** – value vs feasibility matrix, then one decision: the pilot, its success measure, the next meeting and a funding route. Export as summary text, CSV or a reloadable workshop file.

## Running it

It is a single static page with no build step. Open `index.html` in a browser, or publish with GitHub Pages
(Settings → Pages → Deploy from a branch → `main` / root).

Workshop data is saved in the browser's local storage only. Use **Pilot → Copy workshop file** to keep a copy.
Workshop files saved by the earlier one-card-per-requirement version still load; each requirement becomes a single-card solution.

## Files

- `index.html` – the app (HTML, CSS and JavaScript in one file, card data embedded)
- `cards/` – images of the 87 scenario cards

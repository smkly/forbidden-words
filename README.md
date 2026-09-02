# Forbidden Words

A Taboo-style word game for two players on one phone.

The clue-giver holds the phone and describes the target word. They must not say any of the five red words. The other player guesses out loud. Pass the phone after each turn. First to the target score wins.

## Run it

Open `index.html` in a browser. There is no build step and no server.

## Stack

- One static HTML file. Vanilla JavaScript. No dependencies.
- 338 cards embedded in the page.
- Game state saves to `localStorage`, so a refresh does not lose the game.
- Light and dark themes follow the system setting.

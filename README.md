# Forbidden Words

A Taboo-style word game for 2 to 8 players on one phone.

The clue-giver holds the phone and describes the target word. They must not say any of the five red words. Everybody else guesses out loud. Pass the phone to the next player after each turn. The first player to reach the target score wins.

## Run it

Open `index.html` in a browser. There is no build step and no server.

## Stack

- One static HTML file. Vanilla JavaScript. No dependencies.
- 695 cards embedded in the page.
- Cards do not repeat: the game remembers every card it has shown, across games, and only starts the cycle over once the deck is exhausted.
- A metronome tick speeds up as the round clock runs down. Sound can be turned off.
- Game state saves to `localStorage`, so a refresh does not lose the game.
- Light and dark themes follow the system setting.

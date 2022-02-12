# Choose Your Own Adventure: Pokemon Trainer!

My first project using terminal for a "Choose your own adventure" game.

I created a "Choose Your Own Adventure" style game in `app.js`.  This is a story where the user is frequently asked what the protagonist should do.  The story progresses based on what the user says should happen.


**How to Play:**

You are a new Pokemon Trainer who is aspiring to be the best trainer you can be! Follow the terminal prompts to:
- Select your first Pokemon
- Train your Pokemon
- Feed your Pokemon
- Check Pokemon stats
- And have fun!


**Game Components:**

The game is structured in sections, each containing two parts: what just happend and a prompt for what to do next.

- Used the `prompt()` function to retrieve input from the user.
- Used functions to take parameters relating to what the user has chosen to do.
- Used variables to keep track of things that have happened in the story (e.g. accumulated health points, tasks, etc.)
- Ended game with `process.exit()`


**To Play Locally:**

Git clone this repository, then `cd` into this directory and run `npm i` in it.  This will install the `prompt-sync` package which will allow you to run the `prompt()` function.
# Choose Your Own Adventure: Pokemon Trainer!

Created February 2022. 
General Assembly project using terminal for a "Choose your own adventure" game.

I created a "Choose Your Own Adventure" style game in `app.js`.  This is a story where the user is frequently asked what the protagonist should do.  The story progresses based on what the user says should happen.


## How to Play:

You are a new Pokemon Trainer who is aspiring to be the best trainer you can be! Follow the terminal prompts to:
- Select your first Pokemon
- Train your Pokemon
- Feed your Pokemon
- Check Pokemon stats
- And have fun!


## Game Components:

The game is structured in sections, each containing two parts: what just happend and a prompt for what to do next.

- Used the `prompt()` function to retrieve input from the user.
- Used functions to take parameters relating to what the user has chosen to do.
- Used variables to keep track of things that have happened in the story (e.g. accumulated health points, tasks, etc.)
- Ended game with `process.exit()`


## To Play Locally:

Clone this repository from GitHub:
```
$ git clone https://github.com/angelafrancisco/choose-your-own-adventure.git
```
Open project directory. From directory, install NPM packages:
```
$ npm i
```
This will install the `prompt-sync` package which will allow you to run the `prompt()` function.
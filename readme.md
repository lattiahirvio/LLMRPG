# LLMRPG — A Lightweight AI-Powered Roleplaying Game

LLMRPG is a lightweight text-based RPG powered by your favorite LLMs.

---
# What is this project?
This is a simple "game", that uses LLMs as the game master. Made in a single day, the scope of the game is small, and probably provides around an hour of fun at most. Simple, 1 day project. 

## Inspiration
I saw someone post a transcript of something similar on a discord I am in, so of course I built this thing. I have wanted to do things with LLMs for a while now, so this was a simple excuse to actually make this.  

## Features
- Interactive, open-ended text RPG
- Uses local models via Ollama or OpenAI API
- Dynamic inventory parsing and updates
- Save/load system
- Built-in dice roll mechanics (hidden from user)
- Local LLM support (OpenAI API is to be done)

## Requirements
`Python <= 3.8`

`ollama`

`any local LLM of your choosing`

That's literally it, simple game at the end of the day.

## Usage!
For simple usage, run [Ollama](https://ollama.com/) on your local machine, and then run the game using `python ./src/main.py`. There's a few commandline options, which are:

`-s, --save <path>   Load a save file`

`-t, --token <key>   OpenAI API key if using OpenAI `

`-p, --platform      "local" (default) or "openai"`

`-m, --model         Model name (e.g. llama3.2) `

The game has 2 commands; `/exit` and `/inventory`. I think the names speak for themselves.

## Contributing
Pull requests welcome, bug reports and such issues may or may not be taken into consideration.

## TODO!
While I am not likely to continue this project, here are some things I'd add if I was to continue it.

- OpenAI APi support (I mostly didnt do this because I lack money)
- a combat system (AI generated enemies?)
- Character creation
- a title screen using something like Curses
- custom scenarios
- switching between models on the fly
- quests and long term objectives
- actual worldbuilding!

## reservations
This project is a lightweight, simple toy project. Simple learning project. The game is vulnerable to prompt injection and is easily breakable. But at the end of the day, it's single-player, so no harm done. 

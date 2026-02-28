# Pixel Foundery

**Build anything with your kid + AI.**

Pixel Foundery solves the blank-prompt-box problem for parents. Pick your kid's age, what they're into, and what kind of project to build — get a ready-to-paste prompt that produces a working project in any AI chatbot.

## Two versions, same spirit

This project exists in two forms, both honoring the same idea: **a parent and a kid should be able to build something together in five minutes.**

### 📄 `index.html` — The single-file version (this repo)

One HTML file. No build step. No dependencies. No server. No API keys. Open it in a browser and it works.

25+ handcrafted prompt templates across 6 categories (games, stories, art tools, science experiments, math puzzles, music makers), each designed to produce a complete single-file HTML project when pasted into any AI. The prompts themselves ask for single-file HTML — it's turtles all the way down.

This is the version you can fork, run locally, or deploy anywhere. It's the spirit of the project distilled: simplicity as a feature, not a limitation.

### 🔮 [pixelfoundery.com](https://pixelfoundery.com) — The AI-powered version

The live site is built on [Anything](https://anything.com) and generates prompts in real-time using Claude. Same interface, same inputs, but instead of drawing from a template library, it creates unique, tailored prompts every time.

Same mission. One version trusts the templates. The other trusts the model. Both produce the same output: a prompt a parent can paste into Claude, ChatGPT, or Gemini and build something real with their kid.

## How it works

1. **Age** — Select your kid's age (2–5)
2. **Interest** — What they're obsessed with (trucks, dinosaurs, space, animals, etc.)
3. **Project type** — Game, story, art tool, science experiment, math puzzle, or music maker
4. **Generate** — Copy the prompt, paste into any AI, build together

Every generated prompt produces a single-file HTML project with:
- Touch-friendly controls for small hands
- Sound effects via Web Audio API (no external files)
- Age-appropriate difficulty and pacing
- Themed to whatever your kid loves right now

## Why

Parents want to build with their kids using AI but don't know what to ask for. "Make me a game" gets you something generic. "Make me a tap-to-jump game themed around construction vehicles for a 3-year-old with celebratory confetti every 5 stars and Web Audio API sound effects" gets you something your kid actually plays for an hour. Pixel Foundery bridges that gap.

## Tech

**This repo (static version):**
- Single HTML file, zero dependencies
- 25+ prompt templates across 6 categories
- Dark mode via `prefers-color-scheme`
- Mobile-first, fully responsive

**Live site:**
- Built on [Anything](https://anything.com)
- AI generation via Claude Sonnet
- Same UI, dynamic prompts

## Links

- **Live site:** [pixelfoundery.com](https://pixelfoundery.com)
- **Newsletter:** [Raising Pixels](https://raisingpixels.dev)
- **Kid's games:** [madladstudios.com](https://madladstudios.com)
- **More project ideas:** [toddlerlabs.com](https://toddlerlabs.com)

Built by [@meimakes](https://x.com/meimakes)

# PCMStack

**Open-source tooling for Pro Cycling Manager.**

PCMStack is a community-driven collection of tools, libraries, and apps built around [Pro Cycling Manager](https://en.wikipedia.org/wiki/Pro_Cycling_Manager) — the cycling management simulation. Our goal is simple: make PCM's data open, accessible, and fun to build on.

---

## Why this exists

Every PCM career lives inside a `.cdb` save file — a SQLite database packed with riders, teams, races, and stats. It's a goldmine, but it's locked behind an undocumented format that's hard to read, edit, or extend.

PCMStack is where we fix that. We build the small, sharp, composable tools that turn PCM saves into something you can actually work with — whether you're a modder, a data nerd, a save editor, or just someone who wants to win a Grand Tour with a rider nobody believed in.

Open format. Open tooling. Built in the open.

## Projects

Our ecosystem is made of focused pieces that work great on their own and even better together.

| Project | What it does |
|---|---|
| | |

More tools are on the way — parsers, editors, and utilities for the `.cdb` format. Watch this space.

## Philosophy

We're fans of the Unix principle: small tools that do one thing well and compose cleanly. Each project in PCMStack is independent, but they share a common backbone — a clean, reliable way to read and write the PCM save format — so you can pick up one piece without swallowing the whole thing.

## Get involved

This is a community effort, and contributions are genuinely welcome — whether that's code, bug reports, format documentation, or just telling us what you'd want to build.

- 🐛 **Found a bug?** Open an issue on the relevant repo.
- 💡 **Have an idea?** Start a discussion or open an issue — we'd love to hear it.
- 🔧 **Want to contribute code?** Fork, branch, and send a PR. Check each repo's `CONTRIBUTING` notes first.
- 🧩 **Reverse-engineered part of the `.cdb` format?** That knowledge is gold. Share it.

## Tech

Most of the stack is built in TypeScript / Node.js, working against SQLite under the hood, with a focus on portability and clean, documented APIs.

## License

Libraries and tools in this organization are released under the [MIT License](https://opensource.org/licenses/MIT) unless a repository states otherwise. Use them, fork them, build on them.

---

> PCMStack is an independent, fan-made project. It is not affiliated with, endorsed by, or connected to the developers or publishers of Pro Cycling Manager. All trademarks belong to their respective owners.

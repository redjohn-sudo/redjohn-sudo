# Vincent Roumane

Builder based in Paris. I make AI agents that do real work, and I measure what they do before I claim it.
Incoming student at [École 42 Paris](https://42.fr) (piscine passed, curriculum from November 2026).

## What I'm building

### Contingency: grid capacity studies for businesses blocked by grid congestion
Dutch companies waiting for more grid capacity (netcongestie) send three documents: their meter export
(15-minute values), their connection contract and their grid operator's invoice. Contingency shows the
capacity still available under the current contract and the traps, each conclusion with its source,
in Dutch and French. It also produces a flexibility scan structured like the official Flex-e plan.

- Free to use: **[contingency-scan.vercel.app](https://contingency-scan.vercel.app)**
- Tested on public real data: the engine ran on 5,358 German industrial sites (VEA dataset)
- Code kept private

### Oblivion: the team memory for developers
When a developer is stuck on an error, a teammate has often fixed it already, and that fix lives only in
their screen history ([screenpipe](https://github.com/screenpipe/screenpipe)). Oblivion finds it, asks the
teammate before sharing anything, runs it for the developer after one click, checks it worked, and
remembers it for the whole team, coding agents included (MCP tool `ask_team`).

- Local model on the developer's own GPU (Gemma 4): no screen text leaves the machine for a model
- Quality benchmark on 12 trap cases: 11 correct, 0 wrong suggestions, 0 dangerous commands
- Live chain, from an error on screen to a coding agent's proposal: 23 seconds
- Built for the 42 Paris × screenpipe hackathon, October 2026

## Open source

- **screenpipe on Linux (GNOME Wayland):** screenpipe recorded nothing usable on Fedora 44. I found and fixed
  the causes (screen-share approval asked at every start, windows not recognised, terminals misread) and two
  bugs in the official code. Fixes on [my fork](https://github.com/redjohn-sudo/screenpipe/tree/claude/gnome-wayland).
- **audiopipe:** build fix for recent GCC on Linux ([fork](https://github.com/redjohn-sudo/audiopipe)).

## Hackathons

- **European Hackathon League:** team Pegasus qualified in the top 15 for the Grand Finale in Munich (October 2026)
- **42 Paris × screenpipe, Build Agents That Remember:** October 16 to 18, 2026

## How I work

I build with AI coding agents (Claude Code, Codex) and drive them: I decide, check and ship. Every number on
this page comes from a measurement I can show.

[LinkedIn](https://www.linkedin.com/in/vincent-roumane-426512300) · [X @rootseptember](https://x.com/rootseptember)

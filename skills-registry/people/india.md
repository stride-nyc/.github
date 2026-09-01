# India Amos

## [indiamos/agent-skills-public](https://github.com/indiamos/agent-skills-public)

A collection of skills I use in day-to-day work, installable as a Claude Code plugin marketplace (`indiamos-skills`) or manually. I've tried to make them _somewhat_ adaptable to different ways of working, but ultimately they're built for _my_ workflow, so YMMV. They probably _won't_ work right with other tools, such as Cursor, because stuff like MCP tool names won't match.

Key skills in the collection:

- [**commit-message**](https://github.com/indiamos/agent-skills-public/blob/main/commit-message/SKILL.md) – conventional commit message from the diff; nothing fancy, but it gets the character counts right more often than not
- [**estimate-tickets**](https://github.com/indiamos/agent-skills-public/blob/main/estimate-tickets/SKILL.md) – Fibonacci estimation notes with a rationale, flagging undeclared dependencies and points that need refinement
- [**export-full**](https://github.com/indiamos/agent-skills-public/blob/main/export-full/SKILL.md) – export a Claude conversation to a Markdown transcript, _including the compacted parts_
- [**generate-pr-description**](https://github.com/indiamos/agent-skills-public/blob/main/generate-pr-description/SKILL.md) – structured PR description from a branch diff and its tracked ticket; boring, but there are worse ones
- [**granola-notes**](https://github.com/indiamos/agent-skills-public/blob/main/granola-notes/SKILL.md) – fetch meeting notes and transcripts from Granola via its REST API. Handy if you connect to Anthropic via API key instead of a subscription.
- [**improve-skill**](https://github.com/indiamos/agent-skills-public/blob/main/improve-skill/SKILL.md) – audit and revise a skill file to make it more likely to work as intended
- [**pr-scout**](https://github.com/indiamos/agent-skills-public/blob/main/pr-scout/SKILL.md) – thorough but relatively inexpensive code reviewer that doesn't post comments without your explicit permission
- [**pr-scout-ask**](https://github.com/indiamos/agent-skills-public/blob/main/pr-scout-ask/SKILL.md) – convert issues found during review into respectful question-framed comments

---

## Other skill packs I rely on

- [Matt Pocock skills](https://github.com/mattpocock/skills) – mostly the `grill*` tools and `resolving-merge-conflicts`
- [Spec Kit](https://github.com/github/spec-kit) – haven't used it recently, but I learned a lot from how it's put together
- [Superpowers](https://github.com/obra/superpowers) – `writing-plans` and `receiving-code-review` are probably the only ones I invoke by name, but I count on SP to hand tasks to its other tools whenever appropriate

## Non-AI gear

- [1Password CLI](https://www.1password.dev/cli) – 1Password was already great for a very long time, but the CLI really makes me feel _seen_, y'know? I no longer have to worry about accidentally committing `.env` files full of secrets, and agents are [less likely](https://www.1password.dev/get-started/secure-ai-access) to get their grubby little paws on them.

- [chezmoi](https://github.com/twpayne/chezmoi) – dotfiles manager to keep terminal config, Claude settings, and other annoying-to-lose-or-break files in sync across machines

- [Clipy](https://github.com/clipy/clipy) – there are a zillion tools that do this same thing, but I'm continually amazed by how many people survive without using any of them

- [Dank Mono](https://philpl.gumroad.com/l/dank-mono) – I am picky about fonts, and this is the font I picked. Still happy with it after 8+ years, and the name still makes people laugh.

- [delta](https://github.com/dandavison/delta) – git diffs that don't hurt my brain

- [Night Owl](https://github.com/sdras/night-owl-vscode-theme) – relatively high-contrast but pretty, with ligatures and italics; Dank Mono works great with it

- [Setapp](https://go.setapp.com/) (add `invite/wxs2d2q4` for a free month) – an ever-growing portfolio of tools for all kinds of stuff, as an annual subscription. A bunch of apps I used to pay for individually are in it, and when I need to handle some new or one-off task, there's usually some tool in there for doing it. Two underappreciated heroes:

  - [TextSniper](https://textsniper.app/) – indispensable; I use it all day long

  - [Timing](https://timingapp.com/) – eight years' worth of time sheets, made relatively painless

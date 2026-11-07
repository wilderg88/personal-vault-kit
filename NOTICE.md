# Notice and credit

This kit is an adapted version of the **AI Memory Vault** by **Jared Rhodenizer** (@jaredrhod):

https://github.com/jaredrhod/ai-memory-vault

Source version used: commit 659bba9c8b351c937dd393b3042801d1ff1b502c, read 2026-10-31.

Original work Copyright (c) 2026 Jared Rhodenizer, licensed under Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0). This adapted version is licensed under the same license, CC BY-SA 4.0 (full text in LICENSE, and at https://creativecommons.org/licenses/by-sa/4.0/). If you share or adapt this kit, keep this credit and use the same license. No warranty is given; see the license.

The way the system works is Jared's: one memory (the vault), a short boot file outside the vault, startup reads, saving the same turn, Job notes, folder indexes kept current, daily notes from a template, and a living profile.

This kit is also a personal-life twin of a business adaptation of the same work (the "My Business Vault" kit). Where a change below was first made there, it is carried over.

## What was changed

| Jared's file | This kit | What changed |
|---|---|---|
| upstream assistant start-up template | AGENTS.md | Same structure, startup steps and core rules, now in `AGENTS.md` so Claude Code and Codex both read them. The shipped "Jarvis" personality (profane, for a developer) is replaced by a warm, plain everyday assistant (default name Penny, renamed at setup). "Double-confirm before any source-code edit" became "Nothing leaves without my yes" (no sending, posting, buying, deleting outside the vault or account changes without a yes). Added a permission-settings warning: never use bypass modes. Added rules that health, money and family notes are private and that no passwords or account numbers go in notes. Vault path points at the My Personal Vault folder next to the boot file. Plain words throughout. |
| templates/VAULT-INDEX.md | My Personal Vault/VAULT-INDEX.md | Same two jobs (profile and map) and the same vault rules, reworded in plain words. Profile sections fit a person's life. Vault Structure lists the ten personal folders. Added a "Settled answers" pointer to Settled-Facts. |
| templates/MEMORY.md | MEMORY.md | Same pointer text; instructions in plain words and point at this kit folder. |
| templates/DAILY-NOTE.md | My Personal Vault/01 - Daily Notes/Daily Note Template.md | Same sections; em-dashes removed. |
| ai-memory-vault.md | SETUP.md | Shortened. Jared's build file interviews a person and creates the folders; here the folders ship ready, so setup only fills in blanks. Left out: the full folder build, hand-editing Obsidian's registry file, the Desktop launcher, and the offers for his other tools. Added: paths for Claude Code, Codex and the Claude desktop chat with the filesystem extension. |
| TROUBLESHOOTING.md | TROUBLESHOOTING.md | Same topics, rewritten for this kit's folder layout; added entries for the AI not following rules and for permission prompts. |
| README.md | README.md | New README for a non-technical person; credits Jared at the top. |
| LICENSE | LICENSE | Unchanged (CC BY-SA 4.0). |
| (none) | My Personal Vault folders 00 to 09 with index notes, Settled-Facts.md, Active Priorities.md, Jobs.md, Job template.md, Weekly review.md | New, built from the formats in Jared's build file (folder index, Active Priorities, Job note). Example data is made up. |
| (none) | My Personal Vault/.obsidian/app.json | Turns on "Automatically update internal links", as Jared's build file does. |
| .gitignore | (left out) | Not needed for a folder kit. |

## Changes from the business kit

The business kit's customers-and-FAQ folders, vendor and marketing folders, install pack and business-specific wording are not in this kit. They are replaced by the personal folders listed above.

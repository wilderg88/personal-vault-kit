# Troubleshooting

Adapted from TROUBLESHOOTING.md in the AI Memory Vault by Jared Rhodenizer (github.com/jaredrhod/ai-memory-vault), CC BY-SA 4.0.

Written for people and for AI assistants. If you're an AI helping someone with this vault: read this file, then work from their actual files and folders, never from guesses.

## Where are my notes, physically?

Open `My Personal Vault/VAULT-INDEX.md`: its "Vault location" section has the full path. The notes are the `My Personal Vault` folder inside this kit folder. Obsidian also knows: its vault switcher lists every vault with its path.

## Obsidian opened to a welcome screen instead of my notes

Obsidian only opens folders it has been shown once. On the welcome screen choose **Open folder as vault** and pick the `My Personal Vault` folder. It remembers from then on.

## How do I back up my notes?

Do this before the first time the assistant writes anything, then keep it current. The notes live on one computer. Pick any one of these free options:

- **Windows:** File History (Settings, then search "File History", turn it on with an external drive, and add the kit folder to its list once).
- **Mac:** Time Machine covers your home folder automatically if the kit is there.
- **Copy:** once a week, copy the whole kit folder to a USB drive.

Don't put the vault in two sync services at once (for example OneDrive and Obsidian Sync). Two sync tools editing the same files make conflicted copies.

## My notes are in OneDrive or iCloud

That works and gives you a free backup. One click keeps it fast: right-click the kit folder and choose "Always keep on this device" (Windows) or "Keep Downloaded" (Mac), so the cloud doesn't swap your notes for online-only placeholders.

## My assistant didn't load the rules

The rules live in one file, `AGENTS.md`, in the kit folder. Find your path below.

**Claude Code**
- Check that Claude Code was opened in the kit folder (the one holding `AGENTS.md`), not in a parent folder or somewhere else.
- `AGENTS.md` loads on its own from Claude Code v2.1.277.
- Start a fresh session and say "hello". The first reply should be the welcome line from `AGENTS.md`. In a long conversation, say "re-read AGENTS.md and your vault index".

**Codex**
- Open the kit folder itself in Codex, not a parent folder. Codex reads `AGENTS.md` from the folder it is opened in.
- Start a new session after any change to `AGENTS.md`; an open session does not always reload it.
- Ask: "What does your AGENTS.md say your name is?" If it can't answer, ask it to read `AGENTS.md` and `VAULT-INDEX.md` now.
- ChatGPT Free has only limited Codex access. If it stops working mid-session, you may have hit that limit; try later or move to Plus.

**Claude desktop chat (filesystem extension)**
- Open Settings, then Extensions, and check the Filesystem extension is on and its allowed folders include `My Personal Vault` and this kit folder.
- Check the saved preference is still there: "At the start of every new conversation, read AGENTS.md and VAULT-INDEX.md in my personal vault kit folder before responding."
- Chat does not load files on its own. If it skipped them, say: "Please read AGENTS.md and VAULT-INDEX.md now." Then approve the file reads when it asks.
- Keep tool approval on **ask each time**. A prompt that asks is the safe setting working.

## The AI says it can't find my notes

The vault path is written in two places: `AGENTS.md` in the kit folder and the "Vault location" section of `VAULT-INDEX.md`. If you moved the folder, tell the AI the new path and have it update both (and the MEMORY.md pointer if you set one up). Also make sure your tool was opened in the kit folder, and for the desktop chat that the extension's allowed folders include the new location.

## The AI doesn't know my routines or facts

In a long conversation, say "re-read your vault index". If an answer is wrong, correct it and ask it to fix the note the answer came from.

## The AI asks for permission a lot

That's the safe setting working. Don't switch to "bypass permissions", "full access" or any mode that never asks; it would let the AI send, post or delete without you.

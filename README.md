# My Personal Vault: a memory for your AI assistant

**Built on the AI Memory Vault by Jared Rhodenizer:** https://github.com/jaredrhod/ai-memory-vault (CC BY-SA 4.0). The way it works is his. Changes are listed in NOTICE.md.

## What it is

A folder of plain notes that becomes your AI assistant's memory. Every time you talk to it, it reads these notes first, so it already knows your plans, your routines, your people and your to-do list. When you tell it something new, it writes it down the same day. You never explain the same thing twice.

## Who it's for

Anyone who wants a helper for everyday life and isn't technical. If you can open a folder and type a sentence, you can set this up.

## What you need

- A computer (Windows or Mac).
- **The vault itself is free, and you can start on a Free plan.** Pick one route:
  - **Free: Codex on ChatGPT Free.** Codex access on the free plan is limited, so long sessions may stop until the limit resets.
  - **Free: the Claude desktop chat with its filesystem extension**, which lets Claude read and write this folder. You set it up yourself (see SETUP.md). Claude Free has limited usage, and no one has tested this path on a real Free account yet.
  - **Smoother: a paid plan.** Claude Pro (about $20 a month, claude.com/pricing) or ChatGPT Plus (chatgpt.com/pricing). Both pages checked 2026-11-02. Either one opens this folder directly and follows the kit's rules on its own, with fewer limits.
- **Obsidian**, a free app for seeing your notes (obsidian.md).

## INSTALL GUIDE

Your AI follows the full INSTALL GUIDE in `SETUP.md` with you, one step at a time, doing what it can and guiding the rest.

1. Use the personal kit download link Wilder gives you. Unzip into Documents with a simple folder name.
2. Install the Codex app from https://openai.com/codex, sign in with your ChatGPT account, and open the kit folder locally, not on chatgpt.com. Or use Claude Code in Claude desktop, or desktop chat with the Filesystem extension set to ask each time. The agent guides sign-in and opening the folder; it cannot install itself.
3. Back up the whole kit folder before any write.
4. Keep default approval. Never choose full access or bypass permissions.
5. Say yes if you want the agent to install Obsidian with winget on Windows or brew on Mac. Otherwise use https://obsidian.md. Choose **Open folder as vault** and select the inner `My Personal Vault` folder.
6. Paste: `Read SETUP.md and set me up.` Then answer the interview one topic at a time.
7. Ask the agent to list what is installed and working and help with anything left. See `TROUBLESHOOTING.md` if needed.

## Your first hour

1. **Install the apps.**
   - Your AI tool: the Claude desktop app (claude.com/download), or the Codex app signed in with your ChatGPT account. (Codex on the chatgpt.com web page cannot see a folder on your computer; use the app.)
   - Obsidian: download it free from obsidian.md and install it. (Or skip this; setup offers to install it for you on Claude Code or Codex. On the chat path, download it from obsidian.md.)
2. **Put this kit somewhere you'll find it**, like your Documents folder. Keep the folder name simple.
3. **Connect your AI tool to the kit folder** (the one with this README in it). Pick your path:
   - **Claude Code** (paid Claude plan): open the Claude desktop app, choose Claude Code, and pick the kit folder.
   - **Codex** (ChatGPT Free or Plus): open the Codex app, sign in with your ChatGPT account, and open the kit folder as a local folder.
   - **Claude desktop chat** (Free works to try): install the Filesystem extension, point it at the kit folder, and save the one-line preference. SETUP.md, Path 3, has the steps.

   Then paste this one sentence:

   > Read SETUP.md and set me up.

   It checks everything, asks you some short questions about you, and fills in your notes. About ten minutes. It also asks what name you want for your assistant (the default is Penny).
4. **Open your notes in Obsidian.** Choose **Open folder as vault** and pick the `My Personal Vault` folder inside the kit. That's your assistant's memory; everything it learns shows up here.
5. **Tell it what's on your plate (5 minutes).** At the end of setup it asks for your main plans, routines and the people and dates that matter. From then on it keeps them current.

After that, just talk to it. Open your AI tool in the kit folder whenever you want your assistant.

## What's inside

- `AGENTS.md`: who your assistant is and the rules it always follows. Claude Code and Codex both read it.
- `SETUP.md`: the setup steps the assistant follows with you.
- `My Personal Vault/`: your notes. Inbox, Daily Notes, Goals and Projects, Health and Habits, Money (budget notes only, never account numbers), Family and People, Home, Learning, Archive, Routines and Jobs, plus Settled-Facts (your official answers) and Active Priorities (your to-do list).
- `TROUBLESHOOTING.md`: fixes for common problems.

## Stay safe

- **Never paste passwords, card numbers or codes into a chat.** You type your own passwords where the app asks.
- **Keep the safe permission setting.** Use the mode that asks before risky actions. Don't turn on "bypass permissions" or any mode that lets the AI act without asking.
- **Nothing gets sent without you.** The assistant drafts messages and posts; you approve them.
- **Keep a backup** of the kit folder (see TROUBLESHOOTING.md). The notes live only on your computer.

## Credit and license

The AI Memory Vault is by Jared Rhodenizer, https://github.com/jaredrhod/ai-memory-vault. This kit is shared under the same license, CC BY-SA 4.0 (see LICENSE and NOTICE.md). You can use and change it. If you share a changed version, credit Jared and use the same license.

# Unbundle

Don't adopt the whole bot. Unbundle it. Keep only what you use.

Free. Still in testing.

## Quick start (copy and paste)
1. Open `unbundle/SKILL.md` in this repo, copy all of it, and save it as a new skill named `unbundle` in a bot you already run. To check it loaded, ask the bot "what does unbundle do?". To remove it, delete that skill.
2. Then say one of these to that bot:

```text
unbundle this
<paste the outside skill or bot text here>
```

```text
unbundle my bot
```

## What it does
**Step 1. Bring it in carefully.** Paste an outside skill or bot text. Unbundle is designed to read it as data only: not to follow instructions inside it, not to run, install or import it, and not to open its links. It's designed to flag red flags (hidden instructions; text that tries to change who your bot is or its rules; send, post, delete, pay or password requests; outside links, and links whose wording doesn't match where they go; any package or plugin it wants installed, for you to check yourself; broad write access, or more access than the job needs; secrets mixed with sending data out; anything that skips your approval). If it couldn't check everything, it's designed to say "not fully checked", never "looks safe", and it's designed so one serious flag outweighs any number of clean checks. It breaks the text into jobs, checks them against the skills you already have, and keeps only what's new. Then it writes a fresh skill from scratch in plain words, with no copied text, and shows it to you. It's designed to save nothing until you say yes.

**Step 2. Keep it lean.** One setup question, then a preview of files your bot doesn't seem to use. It's designed so nothing changes in the preview. You say yes to one item at a time, and each one you approve is set aside in a backed-up archive folder. It archives with a backup. It does not free up space: archived files and backups stay on disk until you remove them yourself.

## Safety and undo
Use at your own risk.
- Designed to change nothing without your yes to that one thing. Silence or an unclear reply counts as no.
- Designed never to delete. Step 2 moves files to `unbundle-archive/` only after a backup copy is checked. Say `restore item N` to put a file back.
- Designed never to move or edit your skills, memory or rule files. Step 1 only adds a new skill you approved.
- Designed to skip other bots' storage and any file or folder whose name looks like health, finance or legal. Check its list before you say yes.
- No code, no outside links, no sending, no payments, no passwords.

## What it can't catch
Step 1 only sees the text you give it. It can miss hidden tricks, linked files, code or later updates, and it can be wrong. A clean result is not proof of safety. Read the rebuilt skill yourself before you save it.

## Still in testing
This is an early test release. Expect rough edges, use it only on bots you have the right to change, and keep your own backup.
Use Step 1 only on text you have the right to use, and follow its license.

## Please read
- A helper checklist, not a security guarantee. Review anything before you install it. Use at your own risk.
- Free and promotional; Hammerkeel Labs may offer paid products later. No purchase needed.
- Not legal, financial, tax or medical advice.
- Unofficial. Not affiliated with or endorsed by X Corp., SpaceXAI LLC (SpaceXSI, formerly xAI), Space Exploration Technologies Corp., the developer of Grok, or any of their affiliates.

## License
MIT. Copyright (c) 2026 Chris Naylon. See LICENSE.

# Changelog

## v0.2.0-testing - 2026-10-19
Unbundle is now one free skill with two steps.

- Added Step 1, Bring it in carefully: reads an outside skill or bot text as data only, scans for red flags, breaks it into jobs, keeps only jobs you don't already have, and writes a fresh skill in plain words. Nothing is saved until you say yes. Includes a "What it can't catch" section.
- Step 1 red-flag scan made stricter: designed to flag text that tries to rewrite who the bot is or its rules, any package or plugin it wants installed (you check it's real; it's designed never to install it), access bigger than the job needs, links whose wording doesn't match where they go, and secrets mixed with sending data out. Designed to fail closed ("not fully checked", never "looks safe") and to let one serious flag outweigh any number of clean checks.
- Step 2, Keep it lean (tidy-up v6.1): setup is now one turn instead of three; plainer words; files are now "set aside" throughout; it now says clearly that it archives with a backup and does not free up space.
- Notices cut to one short "Please read" block, shown once.
- Kept from v0.1.0: preview first, one yes per move; designed to back up and checksum before every move, with no delete step, and designed never to move skills.
- Changed in v7: Restore is designed never to overwrite an existing file. If a file with the same name is already there, Unbundle is designed to offer two choices only: keep both (the restored copy gets a new name) or don't restore. No answer means don't restore. The earlier 'replace' option was removed; to replace a file, do it by hand after a keep-both restore.
- Added a quick start at the top of SKILL.md ("unbundle this" / "unbundle my bot").
- Skip list now covers files as well as folders, judged by name only (for example: medical, bank, tax, legal); quick start now says how to check and remove the skill.
- Still in testing. Unofficial. Not affiliated with or endorsed by X Corp., SpaceXAI LLC (SpaceXSI, formerly xAI), Space Exploration Technologies Corp., the developer of Grok, or any of their affiliates.
- Affiliation line updated to the current standard wording in SKILL.md, README.md and this changelog.

## v0.1.0 (testing) - 2026-10-17
First test release (staged, frozen as v6.0): the tidy-up skill, now Step 2.

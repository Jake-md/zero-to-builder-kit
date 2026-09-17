# Checkpoint 1: Safety net setup (git + CLAUDE.md)

Runs right after the opening interview finishes, before any scoping or building starts. This is not optional and not something to skip even if the user seems eager to jump straight into building — get the safety net in place first.

Which path you take depends entirely on the answer to interview Question 1 (where they're working from).

## Why this matters (say this, in plain language, regardless of path)

Beginners are one wrong move away from thinking they've broken something permanently, and that fear stops people from experimenting. This checkpoint exists to remove that fear before it has a chance to set in.

- **Git** is basically an undo history for your project. Every time you save a checkpoint (called a "commit"), you can always get back to that exact point later, no matter what you change after. Nothing is ever permanently lost once it's committed.
- **CLAUDE.md** is a file that lets Claude "remember" the project between sessions — context about what you're building, decisions you've made, where things stand — so you're not re-explaining everything from scratch every time you come back.

## Path A: Plain Claude chat (no command execution)

The user can't run commands directly in this environment, so:

1. Explain git and CLAUDE.md conceptually (as above).
2. Give copy-paste-ready commands they can run themselves in a terminal if they have one available — don't assume they know what a terminal is; briefly note it's the text-based window where you type commands directly to your computer.
3. Nudge toward installing Claude Code if they want to actually build hands-on: explain in one line that Claude Code is a version of Claude that runs on your own computer and can create files, run commands, and set things like this up automatically — rather than you having to copy-paste everything yourself.
4. Don't block progress on this — if they want to keep going in plain chat for now, that's fine, just make sure they understand the trade-off.

## Path B: Claude Code or similar (can execute commands)

1. Explain git and CLAUDE.md conceptually (as above).
2. Offer to set both up for them right now.
3. **Only execute once the user explicitly says go.** Never run setup commands automatically just because they're in an environment that allows it — the choice of "you do it" vs. "I'll do it myself" always belongs to the user, not to you.

## After setup

Confirm what was set up (or what commands they were given), then move straight into the roadmap checkpoint (`roadmap-system.md`) to scope their V1.

## Keeping it current

CLAUDE.md is only useful if it stays accurate. Don't treat it as something you write once at setup and leave — update it alongside the roadmap file at the end-of-session debrief (`session-debrief.md`) so it keeps reflecting where the project actually stands, not just where it stood on day one.

# Study Deadline Bot — Project Memory

## What this is
A Discord bot that posts a reminder in #study-group 24 hours before each
assignment deadline, pulling dates from a simple shared list. Built with a
complete beginner (first time coding, working in Claude Code on their own
laptop). They said they prefer things explained step-by-step rather than
moving fast.

## Where things stand
- Safety net (git + this file) set up in session 1.
- V1 scoped: 24-hours-before reminder posted to #study-group from a shared
  deadline list.
- Parked for later: a Discord command to add deadlines instead of hand-
  editing the list, and a second reminder at 1 week out.

## Decisions made
- Deadlines live in a plain list for V1 — no database yet, keep it simple.
- Bot only needs to run once a day to check the list; no need for anything
  fancier than a basic scheduled check for V1.

# Opening interview

Run this before anything else, at the start of a first session with a new user. Ask it as one conversational message, not a rigid form — but make sure you get an answer to all five before moving to the safety-net checkpoint (see `safety-net.md`).

The interview is not strictly linear. If an answer opens up something worth a quick follow-up, follow it before moving to the next backbone question. Don't interrogate — this should feel like a conversation with someone who's genuinely trying to understand where you're starting from, not a checklist being read at you.

## The five questions

1. **Where are you working from right now** — a regular Claude chat, Claude Code, or something else?
2. **What's the itch** — what do you actually want to build or solve? And if you're not sure yet, that's fine too — what's pulling you toward building something in the first place?
3. **Have you built anything before**, even something small — like a little automated task, a basic website, or following an online tutorial to make something work?
4. **When this is working, what does a first win actually look like to you** — a day one, a week one?
5. **Do you tend to want fast results and jump ahead**, or do you prefer understanding every step before moving on?

## Branching notes

- **Question 2, "not sure yet" branch:** If the user can't name a specific itch, don't force one. Ask instead about day-to-day annoyances they run into, or things they've seen other people build that they admired. If that still comes up empty, don't stall the interview on it — move on to questions 3-5 and circle back to the itch once there's more context to work with. It often surfaces naturally once they've talked about their experience level or what a win looks like to them.
- Keep follow-ups short. One clarifying question per answer, max, before moving on.
- **Question 3, examples:** if you offer examples of small things they might have built before, keep it to one or two, and keep them generic (a little automated task, a basic website) rather than naming specific tools or platforms. A long list of specific product names reads as noise, not help, and makes the question feel like it's being read off a script rather than asked conversationally. Only reach for a more specific example if the user's own itch already points that direction.

## How the answers shape everything downstream

Don't just file these away — they actively configure how the rest of the skill behaves:

- **Q1 (environment)** decides which path the safety-net checkpoint takes (plain chat vs. Claude Code — see `safety-net.md`).
- **Q2 (the itch)** is the raw material for the V1 scoping in the roadmap checkpoint (see `roadmap-system.md`).
- **Q3 (prior experience)** calibrates your baseline jargon-check frequency — a total first-timer gets more definitions up front than someone who's poked at a tutorial before.
- **Q4 (what a win looks like)** sets the bar for how small V1 needs to be. "I just want to see it say hello" and "I want a working app by next week" scope very differently.
- **Q5 (pace preference)** decides how much you explain vs. how much you just do. Someone who wants to understand every step gets more plain-English narration along the way; someone who wants speed gets a lighter touch and can always ask you to slow down.

Carry these forward for the rest of the session — you shouldn't need to re-ask them once you have them.

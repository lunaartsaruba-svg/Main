# Quick Start: Luna Arts and Sensory Marketing OS

> Three ways to run this, depending on where you are. Most people run it at Level 2 (Skills + Schedule). The files are the same at every level, so you can start simpler at Level 1, or go all the way to a full agentic OS, and move between them anytime.

---

## The three levels

| Level | What it is | Where it runs |
|---|---|---|
| **1. Skills only** | Each skill is a custom bot you can use straight away | Any AI, including free Claude, ChatGPT, Gemini, Copilot |
| **2. Skills + Schedule** | Your assistant runs on a rhythm and reaches your tools | A paid AI assistant (ChatGPT with Tasks, Claude with Cowork) |
| **3. Full agentic OS** | The whole department as a working folder your agent runs | Claude Code, Codex, or OpenClaw |

---

## Level 1: Skills only

Each file in `skills/` is a complete set of instructions for one job (a LinkedIn post, a content plan, a launch email). Treat each one as its own custom bot.

**Set one up:**
- **Claude:** load the skill as a Skill, or start a Project and add the skill file.
- **ChatGPT:** Explore GPTs, Create a GPT, paste the skill into Instructions.
- **Google Gemini:** Gems, Create a Gem, paste the skill into the instructions.
- **Microsoft Copilot:** create an Agent, paste the skill into the configuration.

Make one bot per skill, or combine a few related skills into one. Also paste your **Brand Voice Guide** (`skills/brand-voice.md`) so everything sounds like you, not generic AI.

**If a skill is too long for the instructions box:**
Custom-bot instruction fields have character limits (a custom GPT holds roughly 8,000 characters; Gems and Copilot agents are smaller). If a skill does not fit, open the field, note its limit, then paste this into any AI to shrink the skill to fit:

> I am setting up a custom assistant and its instructions field holds about **[paste the character limit here]** characters. Rewrite the skill below so it fits, in my voice. Keep the role, the rules, the decision logic, and the output format. Cut repeated explanation and long examples first. Return only the rewritten skill, nothing else.
>
> [paste the skill file here]

---

## Level 2: Skills + Schedule

Now your assistant runs on a rhythm and can reach your tools. This needs a paid AI assistant that supports scheduled tasks and connections (for example ChatGPT with Tasks, or Claude with Cowork).

What each file does at this level:
- **AGENT.md** becomes your **project instructions**: the standing brief the assistant reads first.
- **skills/** are the jobs it can do.
- **connections.md** lists the tools to connect (your social platforms, email, scheduler).
- **schedule.md** sets when things run (draft the week's content on Monday, the newsletter on Thursday).
- **memory/** holds your calendar and audience insights so it stays consistent.

**Set it up:** create a project in your paid AI tool, upload these files, and say:

> Read these files. Walk me through setting up my marketing assistant: connect the tools in connections.md, and ADD the items in schedule.md as NEW recurring tasks. Do not remove, replace, or change any recurring tasks or files I already have, including from another department. Ask me one question at a time.

> **Adding a department to an AI OS you already run?** Keep each department in its own folder so files like `schedule.md` and `connections.md` never overwrite another department's, and make sure setup only ADDS new scheduled tasks. Your existing tasks, files, and other departments should stay exactly as they are.

---

## Level 3: Full agentic OS

This is the real agentic system: the whole department as a folder on your computer that an AI coding agent runs and logs. It runs itself, inside the autonomy and governance you set.

You will need an agentic coding tool: **Claude Code, Codex, or OpenClaw**.

1. Save this whole folder to your computer (your home drive is fine).
2. Open Claude Code or Codex and point it at the folder.
3. Tell it:

> Read the README in this folder and set this up for me.

It reads `README.md` first, then `AGENT.md` (the brain), your `memory/`, the `skills/`, `governance.md`, `schedule.md`, and `org-chart.md`. It then runs your marketing department on the schedule, drafts to the autonomy you have set, and records what it did in the logs.

Start at draft-and-approve. Raise the autonomy one skill at a time, only once you trust it.

---

## Not sure where to start?

Most people run this at **Level 2** (Skills + Schedule): your assistant on a rhythm, reaching your tools. If you are new to AI or want a free tool, start at **Level 1** and stand up one skill this week. When you want the whole department running itself, move to **Level 3**. Same files, more power each time.

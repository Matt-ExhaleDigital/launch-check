# Launch check

A free Claude Code skill that checks if your AI-built app is actually ready for real users, in plain English.

I'm not a developer. I built a real multi-client app with Claude Code, and getting it ready for paying clients was the scary part: open sign-ups, admin pages anyone could reach, backups I'd never tested, client files left behind after deleting a client, insurance, agreements. Nobody gave me a checklist, so I made one from everything I hit along the way.

## What it does

Run it on your project and it checks 25 things across 5 stages, read-only:

1. **Lock the doors**: sign-ups, who sees what, admin pages, secret keys, passwords, logins, limits
2. **Backups you can trust**: backups on, restore tested, test vs real, free-plan traps
3. **Go live properly**: hosting, logs, re-checking the live version
4. **Client data**: deleting properly, what you collect, staff privacy, a leak plan
5. **If your app uses AI**: no guessing, sources shown, safety warnings, reporting bad answers, upload permissions

Plus a list of business basics to sort before your first paying client (Australia-focused: ABN, agreements, insurance, privacy).

You get a report with your top 3 risks first, and it offers to fix the red items one at a time, only if you say yes.

## Install

1. Download `SKILL.md` from this repo.
2. Put it here (create the folders if needed):
   - Windows: `C:\Users\<you>\.claude\skills\launch-check\SKILL.md`
   - Mac/Linux: `~/.claude/skills/launch-check/SKILL.md`
3. Start a new Claude Code session in your project.

Claude Code may ask you to confirm before installing a skill. That's normal and a good thing.

## Use

In Claude Code, inside your project:

```
Run the launch-check skill on this project. Read-only, no fixes.
```

Test it on a copy or a sandbox first, not your live app.

## Important

This is a checklist, not a guarantee. Passing it doesn't mean your app is secure, and the business items aren't legal, tax or insurance advice. Before you handle sensitive data or lots of clients, get a professional review.

## Feedback

Did it catch something useful? Miss something? Explain something badly? Open an issue. Every one makes the next version better.

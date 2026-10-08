# Brand Identity Architect

A Claude skill for building, brainstorming, and critiquing logos and brand identities. It follows a "logos that last" method inspired by Allan Peters: brand nouns instead of adjectives, lots of iteration, geometric gridding, black-and-white-first vetting, a tiered brand family, and real-world pressure tests.

Once it's installed, Claude uses it on its own when you ask for things like "I need a logo for my bakery" or "what do you think of this logo?"

## Install in the Claude app (claude.ai, desktop, or mobile)

1. Download this repo: click **Code → Download ZIP** at the top of this page.
2. In Claude, open **Settings → Capabilities** and make sure **Code execution and file creation** is turned on.
3. Under **Skills**, click **Upload skill** and choose the ZIP you downloaded.
4. Make sure the skill's toggle is on.

## Install in Claude Code

Clone the repo into your personal skills folder:

```bash
git clone https://github.com/lizannemarie/brand-identity-architect.git ~/.claude/skills/brand-identity-architect
```

Restart Claude Code. Then run `/brand-identity-architect`, or just ask for help with a logo.

To get updates later:

```bash
git -C ~/.claude/skills/brand-identity-architect pull
```

## What's in the repo

- `SKILL.md`: the skill's instructions and method
- `references/pressure-tests.md`: checks for testing a mark in real-world use

# Crayon

An agent skill that writes text that a 3rd grader can read.

Short sentences. Small words. Same meaning.

| Before | After |
|---|---|
| Swallow quicker — a fuller mouth, sooner | Eat fish faster |
| Paid for creeping — the bar fills faster while stalking | Your boost comes back faster when you sneak |
| A deeper pool — one more band on the ring | More health |

Good for game cards, menus, tooltips, hints, buttons and error messages. See [all the examples](EXAMPLES.md).

## Install (Claude Code)

```bash
claude plugin marketplace add kitsupanic/crayon
```

```bash
claude plugin install crayon@crayon
```

Or copy `skills/crayon/` into `~/.claude/skills/`.

## Update

Get the newest list of plugins:

```bash
claude plugin marketplace update crayon
```

Then update Crayon:

```bash
claude plugin update crayon@crayon
```

Restart Claude Code to use the new version.

If you copied the folder, copy it again.

## Use

Say "crayon this", or ask for simpler words. The agent also uses it on its own when it writes short text for players or users.

 Run the installed plugin:

```
/crayon:crayon
```

If you copied the skill folder instead, use `/crayon`.

## How it works

1. Find out what the text means. Read the code around it.
2. Keep names, numbers and words the reader already knows.
3. Rewrite with short sentences and small words. Keep all facts and warnings, even if the text needs more space.
4. Read every line out loud. Keep the words from step 2. Simplify the rest.
5. Show a before/after table.

## License

MIT

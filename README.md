# Crayon

An agent skill that writes text that a 3rd grader can read.

Short sentences. Small words. Same meaning.

| Before | After |
|---|---|
| Swallow quicker — a fuller mouth, sooner | Eat fish faster |
| Paid for creeping — the bar fills faster while stalking | Your boost comes back faster when you sneak |
| A deeper pool — one more band on the ring | More health |

Good for game cards, menus, tooltips, hints, buttons and error messages.

## Install (Claude Code)

```bash
claude plugin marketplace add kitsupanic/crayon
```

```bash
claude plugin install crayon@crayon
```

Or copy `skills/crayon/` into `~/.claude/skills/`.

## Use

Say "crayon this", or ask for simpler words. The agent also uses it on its own when it writes short text for players or users.

Pick a different grade:

```
/crayon 5
```

## How it works

1. Learn what the text really means, from the code or context.
2. Keep names, numbers and words the reader already knows.
3. Rewrite with short sentences and small words.
4. Read every line out loud. Fix what a kid would trip on.
5. Show a before/after table.

## License

MIT

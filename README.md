# Crayon

An agent skill that writes text that a 3rd grader can read.

Short sentences. Small words. Same meaning.

| Before | After |
|---|---|
| Authentication failed — invalid credentials | Wrong name or password |
| In this video, we'll delve into the mechanisms that keep aircraft airborne | Today we will see how planes stay in the air |
| Paid for creeping — the bar fills faster while stalking | Your boost comes back faster when you sneak |

Good for any text people need to get on the first read: menus, buttons, error messages, docs, emails, video scripts, game text. Simple words also reach readers who are still learning the language.

See a full set of rewrites from one real project in [the examples](EXAMPLES.md).

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

Say "crayon this", or ask for simpler words. The agent also uses it on its own when it writes short text for users.

Run the installed plugin:

```
/crayon:crayon
```

If you copied the skill folder instead, use `/crayon`.

## How it works

1. Find out what the text means. Read the code or context around it. Ask if it is not clear.
2. Keep names, numbers and words the reader already knows.
3. Rewrite with short sentences and small words. Keep all facts and warnings, even if the text needs more space.
4. Read every line out loud. Keep the words from step 2. Simplify the rest.
5. Show a before/after table.

## License

MIT

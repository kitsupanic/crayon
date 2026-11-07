---
name: crayon
description: >
  Write or rewrite text so a 3rd grader can read it. Use when the user says
  "crayon", asks for simpler or plainer words or a reading level, or when
  writing short player- or user-facing text: game cards, menus, tooltips,
  hints, buttons, error messages. Takes an optional grade: /crayon 5.
argument-hint: "[grade, default 3]"
license: MIT
---

# Crayon

Write so a kid could read it out loud on the first try. The target is grade 3 unless the user gives a different number.

## Steps

1. **Learn what the text means.** Read the code, data or context behind it. A card that says "Boost comes back off a shallower bar" means nothing until you know what the bar is. Done when you can say what each line does in your own words.
2. **List the keep-words.** These stay as they are: names, numbers, and words the reader sees in the product (a game's "boost", an app's "inbox"). Words that live only in the code or design notes ("eat radius", "re-arm fraction") get plain words in their place. Done when every term is either on the list or up for swapping.
3. **Rewrite** each line with the rules below.
4. **Run the read-aloud test** on every line: every word is one a 3rd grader knows, each sentence has one idea, and the meaning matches step 1. Fix any line that fails and test it again. Done when every line passes.
5. **Show a before/after table**, one row per line. If the text lives in files, make the edit after the table.

## Rules

- **Fit the space.** A card line, label or button ends up as short as the original or shorter. Pick the one fact that matters most and say only that.
- **Short sentences.** One idea each, about 10 words or fewer. In longer text, two short sentences beat one long one.
- **Small, common words.** "Eat" over "swallow". "Faster" over "quicker". "Get back" over "recover".
- **Say what happens.** Plain facts in place of metaphors: "Your boost lasts longer", not "the budget is the burst".
- **Talk to the reader.** Use "you" and "your".
- **Periods and commas.** Where a dash or colon joins two ideas, make two sentences.
- **Keep the meaning.** Same facts, same numbers, nothing added. Simpler words, never a different claim.
- **Sibling lines stay different.** Lines the reader sees together (a hand of cards, one menu) each read differently, so the reader can tell them apart. Lines on different screens may match when they mean the same thing.
- **Grade above 3:** longer sentences and a few more words are fine. Keep every other rule.

## Examples

| Before | After |
|---|---|
| Swallow quicker — a fuller mouth, sooner | Eat fish faster |
| Paid for creeping — the bar fills faster while stalking | Your boost comes back faster when you sneak |
| A deeper pool — one more band on the ring | More health |
| Tear quicker — less time held still under the guns | Rip divers apart faster |
| Grab a diver from further out | Grab divers from farther away |

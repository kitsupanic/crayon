---
name: crayon
description: >
  Write or rewrite text so a 3rd grader can read it. Use when the user says
  "crayon", asks for simpler or plainer words, or when writing short text
  that people read in a product: menus, tooltips, hints, buttons, error
  messages. Works on any text: UI text, docs, emails, video scripts, game text.
license: MIT
---

# Crayon

Write so a kid could read it out loud on the first try. The target is always grade 3.

## Steps

1. **Learn what the text means.** Read the code, data or context behind it. A label that says "Sync on idle" means nothing until you know what syncs and when. If you cannot find what a line means, ask the user or flag the line. Do not guess. Done when you can say what each line does in your own words.
2. **List the keep-words.** These stay as they are: names, numbers, and words the reader sees in the product (a game's "boost", an app's "inbox"). Words that live only in the code or design notes ("retry backoff", "hit radius") get plain words in their place. Done when every term is either on the list or up for swapping.
3. **Rewrite** each line with the rules below.
4. **Run the read-aloud test** on every line: apart from the keep-words and words you explained, every word is one a 3rd grader knows, each sentence has one idea, and the meaning matches step 1. Fix any line that fails and test it again. Done when every line passes.
5. **Show a before/after table**, one row per line. For long text like a script or a page, show the new text in full and list the keep-words. If the text lives in files, make the edit after that.

## Rules

- **Keep the meaning.** Keep every fact, number, condition and warning. Add no new claims. This comes before length.
- **Fit the space.** Aim for a label, button or other tight spot as short as the original or shorter. If the full meaning cannot fit, keep it and flag the space limit.
- **Short sentences.** One idea each, about 10 words or fewer. In longer text, two short sentences beat one long one.
- **Small, common words.** "Use" over "utilize". "Help" over "assist". "Get back" over "recover".
- **Keep joining words.** "Text that a kid can read", not "text a kid can read". Words like "that", "who" and "which" show how a sentence fits together. Keep them, even if the sentence gets one word longer.
- **One word per thing.** Pick one word for each thing and use it every time. "Plane" stays "plane", not "aircraft" in one line and "jet" in the next.
- **Explain a hard word once.** If the text needs a word a 3rd grader does not know, explain it in one short sentence the first time. Then keep using it.
- **Say what happens.** Plain facts in place of metaphors: "Your file is saved", not "your work is safe and sound".
- **Talk to the reader.** Use "you" and "your".
- **Periods and commas.** Where a dash or colon joins two ideas, make two sentences.
- **Sibling lines stay different.** Lines the reader sees together (one menu, a list of choices) each read differently, so the reader can tell them apart. Lines on different screens may match when they mean the same thing.

## Examples

| Before | After |
|---|---|
| Authentication failed — invalid credentials | Wrong name or password |
| Your session has expired due to inactivity. Please sign in again. | You were away too long. Sign in again. |
| Prior to installation, ensure your device has sufficient storage | Before you install, check that your device has enough space |
| In this video, we'll delve into the mechanisms that keep aircraft airborne | Today we will see how planes stay in the air |
| Paid for creeping — the bar fills faster while stalking | Your boost comes back faster when you sneak |

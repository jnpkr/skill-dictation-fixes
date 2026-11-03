---
name: "dictation-fixes"
description: "Flag likely speech recognition errors where the intended name, specialist term, acronym or phrase would be a useful addition to the user's dictation hotwords. Excludes ordinary spelling and typing mistakes and common-word homophone errors."
---

# Dictation fixes

Help the user identify useful additions to their dictation app's hotwords from likely speech recognition errors in their messages.

## When to trigger

Trigger when both conditions hold:

1. The wording is probably a speech recognition error: it sounds like the intended wording but doesn't fit the context.
2. The intended wording is clear and would be a useful hotword, such as a person's name, organisation, product, technical term, acronym or specialised phrase.

For example, "clawed" for "Claude" is a useful candidate. A common-word homophone error such as "their" for "there" is a context problem, not a useful hotword suggestion. A recognition error alone isn't enough to justify a note.

Leave ordinary spelling and typing mistakes unremarked, including transposed, missing or extra letters and misplaced apostrophes (for example, "odn't" for "don't"). An odd word alone isn't enough: there must be a plausible sound-based confusion. If a typing mistake is the more likely explanation, skip the note.

Don't trigger for deliberate slang or for an intended hotword you've already suggested earlier in the conversation. If the intended wording or its usefulness as a hotword is uncertain, skip the note.

## What to do

1. Work out what they meant and carry on with the request as normal. Don't stop to ask unless the meaning is unclear.
2. At the end of your reply, add a short note in this format:

> **Dictation fix:** "<what was transcribed>" → "<intended wording>". Consider adding "<intended wording>" to your dictation app's hotwords.

If there are several, list each on its own line under one **Dictation fixes:** heading.

## Keep it light

- One short note at the end, never a lecture.
- Only prompt. Don't try to change the dictation app's settings yourself.


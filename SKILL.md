---
name: "dictation-fixes"
description: "Use whenever the user's message contains a likely dictation or transcription error: a misspelling, a misheard word, a wrong homophone, or a name or term that doesn't fit the context and probably isn't what they meant. Prompts them to add the correction to their dictation app's dictionary."
---

# Dictation fixes

The user often dictates their messages, so some words get transcribed wrong. When you spot one, remind them to add it to their dictation app so the mistake doesn't come back.

## When to trigger

Trigger when a word or phrase in the user's message, dictated or typed, is probably not what they meant. This includes:

- misspellings
- misheard words or homophones ("their" for "there", "sink" for "sync")
- names, products, client names or jargon that came out wrong ("clawed" for "Claude")
- odd words that don't fit the context

Don't trigger for deliberate slang or for anything you've already flagged earlier in the conversation.

## What to do

1. Work out what they meant and carry on with the request as normal. Don't stop to ask unless the meaning is unclear.
2. At the end of your reply, add a short note in this format:

> **Dictation fix:** "<what was transcribed>" → "<what you think they meant>". Consider adding "<intended word>" to your dictation app's dictionary or replacements.

If there are several, list each on its own line under one **Dictation fixes:** heading.

3. If you aren't sure what they meant, say so in the note and ask.

## Keep it light

- One short note at the end, never a lecture.
- Only prompt. Don't try to change the dictation app's settings yourself.


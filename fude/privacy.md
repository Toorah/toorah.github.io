---
layout: default
title: Fude privacy policy
app: fude
app_name: Fude
icon: /fude/icon.png
accent: "#c8452f"
permalink: /fude/privacy/
---

# Fude privacy policy

Effective 12 November 2026. Fude is made by ATK Interactive.

**Short version: Fude keeps everything on your device. The only thing that ever leaves
it is what you send to an AI provider, and only if you set up the optional AI assistant
with your own key. We never receive any of your data.**

## What stays on your device

Your practice history, handwriting, saved words, flashcards and settings are stored only
on your device. Handwriting grading and draw-to-search run on the device. Fude has no
account, no ads, no analytics and no crash reporting.

## Text from other apps

When you look something up from another app (the text-selection menu or Share), Fude
reads that text on your device to find the word or kanji. It is not stored unless you
save it.

## AI assistant (optional, off unless you add a key)

You can connect Fude to Anthropic (Claude), OpenAI or Google (Gemini) with an API key
from your own account with that provider. Until you add a key, the assistant is hidden
and Fude makes no internet connections.

When you ask a question, Fude sends it over an encrypted connection (HTTPS) straight to
the provider you chose, together with the conversation so far and what you are looking
at (for example the kanji, the word, or the sentence you looked up). Nothing goes through
our servers; we have none. The provider handles this under its own privacy policy and
your agreement with it:

- Anthropic: https://www.anthropic.com/legal/privacy
- OpenAI: https://openai.com/policies/privacy-policy
- Google: https://policies.google.com/privacy

Fude does not save the chats. Your API key is stored on your device only, encrypted with
a key held by Android's secure keystore, and is left out of backups. Remove the key in
Settings to stop all use of the assistant.

To report an offensive or harmful reply, tap **Report** under it. Fude opens your email
app with a message to us containing that reply and your question; nothing is sent unless
you send the email yourself. We use reports only to look into the problem.

## Sync (optional)

If you turn on Sync, Fude writes your progress to one file in a folder **you** choose,
for example in Google Drive or OneDrive, through Android's own file picker. The file
goes only where you put it, and the storage service you pick handles it under its own
privacy policy. We never receive it. Turn Sync off and delete the file to remove it.

## Android backup

Fude lets Android include your progress and settings (not your API key) in your device's
backup, for example Google's backup on a new phone. Android and your backup provider
handle this; you can turn it off in your phone's settings. We never receive it.

## Children

Fude is not directed at children under 13.

## Changes

If this policy changes, the new version will be posted here with a new date.

## Contact

Questions about this policy: {% include email.html %}

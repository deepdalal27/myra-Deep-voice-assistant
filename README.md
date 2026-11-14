# Myra

A voice assistant for CA Deep Dalal. One static page: you speak, Myra answers aloud, and she keeps notes about you so she knows them next time.

## Open her

Once GitHub Pages is on for this repository (Settings → Pages → Deploy from a branch → `main`, folder `/`), Myra lives at:

**https://deepdalal27.github.io/myra-Deep-voice-assistant/**

Use Chrome or Edge on a phone or laptop (Safari also works). On a phone, "Add to Home screen" makes her open like an app.

## First use

1. Open the link, and in **Settings** paste an Anthropic API key (create one at console.anthropic.com). The key is kept only in that browser and is sent only to `api.anthropic.com`. It is never stored in this repository.
2. Tap the mic, allow microphone access, and speak.
3. Turn on **Hands-free** to keep talking back and forth without tapping.

## What she does

- Listens (English, Hindi or Gujarati), thinks with Claude, and replies in voice.
- Searches the web for current news and facts, and names her sources.
- Drafts emails, messages and FinDeependence posts (education only, no investment advice).
- **Remembers**: she saves facts, preferences, people, tasks and corrections on her own, and uses them in every later conversation. The **Memory** button shows everything she has saved; you can delete any note, and export or import the lot.

## Limits

- Memory lives in the browser you use. To carry it to another device, use Export on one and Import on the other.
- From this page she cannot send email, post to Instagram or edit code. She prepares the draft; sending and publishing stay in the Claude workspace.
- "Learning" means her saved notes, which shape every reply. The underlying model is not retrained.
- Anyone can open the public link, but it does nothing without their own API key, and they cannot see your notes.

# Myra

A voice assistant for CA Deep Dalal. You speak, Myra answers aloud, and she keeps notes about you so she knows them next time.

There are two versions in this repository.

## 1. Myra on Claude (free with your Claude plan) — the one to use

**Link: https://claude.ai/artifact/MSQHAzhXDQ5tqpWqNfuR6a**

Source: [`claude/myra.html`](claude/myra.html). It is published as a private Claude artifact, so it runs on your Claude account. There is no API key and no separate bill; it uses your plan's normal usage allowance.

- Open the link while signed in to claude.ai.
- **Chrome on a computer or Android:** tap the mic and speak. She sends your words when you pause, and replies in a Claude voice.
- **iPhone, Safari, or if the mic reports a problem:** tap the text box, then the microphone on your keyboard, and speak. With "Send when I pause" ticked she sends it herself and replies using the phone's own voice.
- The first time, Claude asks your permission for the microphone, for Claude to answer, and for Gmail and Calendar.
- **Memory**: she saves facts, preferences, people, tasks and corrections on her own, in storage tied to your Claude account, so they follow you across devices. The Memory button shows every note and lets you delete any of them.
- **Email**: she searches and reads your Gmail, saves drafts, and sends emails and replies. Before sending she shows the email and reads it back; it goes only after you say yes or tap Send. Your Gmail signature is added automatically.
- **Workspace hand-off**: for live web search and news, Instagram (@findeependence comments, DMs, posts), GitHub and long research, she passes the task to the Claude workspace session and reads you the answer. Anything public still waits for your yes.
- **Automatic effort**: she picks a lighter or heavier Claude model tier from what you asked.
- **Look**: FinDeependence colours, fonts and logo.

"Learning" means her saved notes, which shape every reply. The underlying model is not retrained.

## 2. Standalone page (needs a paid Anthropic API key) — optional

Source: [`index.html`](index.html). A static page for GitHub Pages that calls the Claude API directly with a key you paste in. It adds web search but is billed per use, and its memory stays in one browser. Only use it if you want Myra outside claude.ai.

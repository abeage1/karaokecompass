# 🎤 KaraokeCompass

**Navigate to your perfect karaoke song.**

KaraokeCompass figures out your vocal range through a quick interactive tone-matching test, then recommends karaoke songs that actually suit your voice — no music theory knowledge required.

**[→ Open the app](https://abeage1.github.io/karaokecompass/)**

---

## How it works

1. **Tell us about your voice** — pick whether your voice is generally lower or higher, and how much singing experience you have.

2. **Match some tones** — the app plays 5–6 notes using your browser's audio engine. For each one, say whether it's too low, comfortable, or too high to sing. That's it.

3. **Get your picks** — based on your responses, the app identifies your voice type (Bass, Baritone, Tenor, Alto, Mezzo-Soprano, or Soprano) and surfaces a curated list of songs from its database of 55+ well-known karaoke staples, each rated by difficulty.

You can filter results by vibe (Crowd Pleasers, Easy, 80s, 90s, Ballads, Classics, Soul/R&B) and shuffle for a fresh set of recommendations.

**Optional:** grant microphone access for real-time pitch detection — the app will show a level meter and the name of the note you're singing as you go.

---

## Tech

A single `index.html` file — no build step, no dependencies, no framework. Just HTML, CSS, and vanilla JavaScript using the [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API) for tone generation and (optional) pitch detection via autocorrelation.

Deployed via GitHub Pages.

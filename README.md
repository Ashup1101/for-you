# A little question for you 💌

A phone-first “Will you be my Valentine?” page where saying no is… difficult.

**Live:** https://ashup1101.github.io/for-you/
**Make your own link:** https://ashup1101.github.io/for-you/create.html

## Styles

| Style | Link | What happens |
| --- | --- | --- |
| 💌 Love letter (default) | [`?v=letter`](https://ashup1101.github.io/for-you/?v=letter) | Tap the envelope to open it. Every “no” shrinks until it falls off the page. |
| 🧸 Blush | [`?v=classic`](https://ashup1101.github.io/for-you/?v=classic) | The original idea: “no” begs harder, “yes” grows until it takes over the screen. |
| 🏃 Catch me | [`?v=runaway`](https://ashup1101.github.io/for-you/?v=runaway) | The “no” button dodges every tap, then gives up and leaves. |
| 🌙 Midnight | [`?v=stars`](https://ashup1101.github.io/for-you/?v=stars) | Every “no” wanes the moon and dims the stars. “Yes” sets off heart fireworks. |

## Personalise it

Add these to the link (or use [create.html](https://ashup1101.github.io/for-you/create.html)):

- `to` – their name (`?to=Ananya`)
- `from` – your name
- `q` – a different question (default: “Will you be my Valentine?”)
- `v` – `letter`, `classic`, `runaway` or `stars`

Example: `https://ashup1101.github.io/for-you/?v=stars&to=Ananya&from=Ash`

## How it’s built

One static `index.html` with no build step and no dependencies. It is made for phones: safe-area padding, no double-tap zoom, touch-aware dodging, haptics on Android, a link-preview card for iMessage/WhatsApp, and reduced motion when the phone asks for it.

Inspired by [saurabhnemade/will-you-be-my-valentine](https://github.com/saurabhnemade/will-you-be-my-valentine).

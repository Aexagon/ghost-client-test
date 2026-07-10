# Ghost Client Test

Can an AI derive a brand's visual identity from nothing but the way a person talks?

This repo is one full run of that experiment. A fictional client was invented, "interviewed" by voice memo, and a second AI agent, working blind, derived his colours, type, and layout rules from the transcripts alone. It scored a clean sweep against a sealed answer key it never saw. The derived direction was then built into a complete brand identity document.

## The ghost

**Dee (Deepak Nair), 29.** Singapore hawker-food content creator turned wet-market cooking-class founder. Fast talker, Singlish, allergic to pretension. His three words: fun, loud, honest.

## How the test works

1. **Generate** — one agent invents the persona and writes realistic raw voice-memo transcripts, plus `INTENT.md`: a sealed answer key stating the feelings the persona is supposed to give off. The transcripts never use design vocabulary; Dee talks about steam, aunties, and char kway teow, not hex codes.
2. **Blind derive** — a second agent reads ONLY the transcripts (never the answer key, never any design library) and derives a full visual direction: palette temperature first, then concrete colours, type, layout grammar, and banned moves, every pick traced to a verbatim quote.
3. **Judge** — a third pass scores the derivation against the sealed key.
4. **Build** — the winning direction becomes `DEE_BRAND_IDENTITY.html`, a self-contained brand book that demonstrates the system it describes.

## The result

All five criteria hit: tone words recovered verbatim, palette temperature exact (hot orange / chilli / turmeric, one pandan pop), type energy exact (poster-shout display + friendly humanist body), all three "never" categories caught from his rants, and a near-identical one-sentence feeling, independently reached. Full scoring in `TEST_RESULTS.md`.

## Files

| File | What it is |
|---|---|
| `DEE_VOICE_MEMO_TRANSCRIPTS.md` | The fabricated raw interview, messy on purpose |
| `DEE_BRAND_VOICE_NOTES.md` | Distilled assistant-style notes |
| `INTENT.md` | The sealed answer key (spoilers, read last) |
| `TEST_RESULTS.md` | Judge's scoring |
| `DEE_BRAND_IDENTITY.html` | The built identity doc. Open it in a browser, it's the fun part |

## The principle underneath

Design with reasons. Every colour, face, and layout rule in the identity doc states a why traced to something the client actually said. If a choice can't state its reason, it gets changed, not defended.

Dee is entirely fictional. Any resemblance to a real hawker-food creator is a compliment to the generator.

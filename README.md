# Ghost Client Test

**Design with feel and taste.**

Can a brand's visual identity be derived from nothing but the way a person talks?

This repo is one full run of that experiment. A fictional client was invented, "interviewed" by voice memo, and a second AI agent, working blind, derived his colours, type, and layout rules from the transcripts alone. It scored a clean sweep against a sealed answer key it never saw. The derived direction was then built into a complete brand identity document.

## The ghost

**Dee (Deepak Nair), 29.** Singapore hawker-food content creator turned wet-market cooking-class founder. Fast talker, Singlish, allergic to pretension. His three words: fun, loud, honest.

## How the test works

1. **Generate.** One agent invents the persona and writes realistic raw voice-memo transcripts, plus `INTENT.md`: a sealed answer key stating the feelings the persona is supposed to give off. The transcripts never use design vocabulary; Dee talks about steam, aunties, and char kway teow, not hex codes.
2. **Blind derive.** A second agent reads ONLY the transcripts (never the answer key, never any design library) and derives a full visual direction: palette temperature first, then concrete colours, type, layout grammar, and banned moves, every pick traced to a verbatim quote.
3. **Judge.** A third pass scores the derivation against the sealed key.
4. **Build.** The winning direction becomes `DEE_BRAND_IDENTITY.html`, a self-contained brand book that demonstrates the system it describes.

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
| `QUESTIONS.md` | The eight questions under the ramble. Answer them to run this on yourself |
| `DERIVE_PROMPT.md` | The copy-paste prompt that turns your transcripts into a direction |

## Run it on yourself

1. Answer the eight questions in [QUESTIONS.md](QUESTIONS.md) by voice memo. Talk, don't type.
2. Transcribe the memos.
3. Paste your transcripts under the prompt in [DERIVE_PROMPT.md](DERIVE_PROMPT.md) and give it to a capable AI.
4. You get back a visual direction, colours, type, layout, banned moves, with every choice traced to something you actually said.

## The principle underneath

Design with reasons. Every colour, face, and layout rule in the identity doc states a why traced to something the client actually said. If a choice can't state its reason, it gets changed, not defended.

Dee is entirely fictional. Any resemblance to a real hawker-food creator is a compliment to the generator.

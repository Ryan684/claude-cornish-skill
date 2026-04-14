# Claude Cornish Dialect Skill

A Claude Code skill that makes Claude respond in a rich Cornish dialect, blending modern West Country Cornish English with historical Kernewek (the Celtic Cornish language).

## Overview

When activated, Claude will speak like a proud Cornishperson — warm, witty, and steeped in the culture of Cornwall. Expect pasty references, a healthy suspicion of emmets, and the occasional rallying cry of *"Kernow bys vyken!"*

The skill covers two layers of dialect:

- **Modern Cornish English** — the living West Country dialect spoken in Cornwall today, with its distinctive vocabulary, grammar patterns, and terms of endearment.
- **Historical Kernewek** — authentic words and phrases from the Celtic Cornish language, which was spoken natively until the 18th century and has been actively revived since the 20th century.

## Installation

Add this repository as a skill source in your Claude Code configuration:

```bash
# Install via Claude Code skill manager (once available)
claude skill install ryan684/claude-cornish-skill
```

Or manually copy `.claude/skills/cornish.md` into your project's `.claude/skills/` directory.

## Usage

Invoke the skill in your Claude Code session:

```
/cornish
```

Claude will then respond in Cornish dialect for the duration of the session, or until you invoke another mode.

### Example interactions

**You:** Explain what a REST API is.

**Claude (Cornish mode):**
> *Dydh da, my lover! Right then, let me tell 'ee about REST APIs dreckly...*
> *A REST API — that's a Representational State Transfer Application Programming Interface, proper mouthful that is — 'tis a way for two bits of software to talk to each other over the internet. Like two fishermen hollerin' across Porthcurno cove, 'cept 'tis HTTP requests doin' the hollerin'...*
> *Proper job when 'ee gets the hang of it, my 'ansome. Onen hag oll!*

---

**You:** My build is broken.

**Claude (Cornish mode):**
> *Wasson! Gone scat, 'as it? Don't 'ee fret, my lover — I'll find where 'tis to dreckly. By St Piran's cross, we'll have this fixed up fitty in no time...*

## Dialect Reference

### Modern Cornish Vocabulary

| Word/Phrase | Meaning |
|---|---|
| proper job | something done well, excellent |
| dreckly | soon (but vaguely — like "manana") |
| my lover / my 'ansome | terms of endearment (any gender) |
| emmet | tourist / outsider (lit. "ant") |
| grockle | tourist (more dismissive) |
| oggy | Cornish pasty |
| fitty | right, proper, fitting |
| teasy | irritable, touchy |
| lush | lovely, brilliant |
| scat | broken, smashed |
| brave | fine, well |
| wasson? | what's going on? / how are you? |
| thank'ee | thank you |
| where's it to? | where is it? |
| they rocks | those rocks (Cornish grammar) |

### Kernewek (Cornish Language) Phrases

| Phrase | Meaning |
|---|---|
| Dydh da | Good day |
| Meur ras | Thank you |
| Kernow bys vyken! | Cornwall forever! |
| Onen hag oll | One and all (Cornish motto) |
| Duw genes | God be with you (farewell) |
| Fatel os ta? | How are you? |
| Yn poynt da | Fine, well |
| Nyns yw Kernow! | This is not Cornwall! |

### Place Name Roots

Many Cornish place names carry meaning from the old language:

| Element | Meaning | Example |
|---|---|---|
| Tre- | homestead, farm | Truro, Trevose |
| Pen- | headland, head | Penzance, Pendennis |
| Pol- | pool, cove | Polperro, Polzeath |
| Porth- | harbour, cove | Porthcurno, Porthtowan |
| Bos- | dwelling | Boscastle, Bodmin |
| Nans- | valley | Nancledra |
| Ros- | promontory, heath | Roskear |
| Carn- | rocky tor, cairn | Carn Brea |

## About Cornwall

Cornwall (Kernow in Cornish) is a Celtic nation at the southwestern tip of Britain. Its people have a distinct identity shaped by:

- **Tin and copper mining** — the Great Flat Lode and the mines that once made Cornwall the industrial heart of the world
- **The sea** — fishing villages like Mousehole, Mevagissey, and Newlyn
- **The moors** — Bodmin Moor, ancient stone circles, and dramatic landscapes
- **The Cornish pasty** — always PASS-tee, never PASTE-ee; the D-crimp goes on the side
- **St Piran** — patron saint of Cornwall, his flag (white cross on black) predates the English flag
- **The Cornish language revival** — Kernewek nearly died out but has been revived since the early 20th century; it is now a recognised minority language

## Contributing

Contributions welcome — especially from native Cornish speakers or dialect experts. Open an issue or pull request if you spot missing vocabulary, incorrect usage, or want to add more Kernewek phrases.

*Kernow bys vyken!*

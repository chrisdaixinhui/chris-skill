# chris.skill

> *"Man is the measure of all things."* — Protagoras

A person, distilled into a Skill. Which is, I know, a contradiction in terms — and I'd rather start there than pretend otherwise.

[**中文**](docs/lang/README_ZH.md)

---

## What this is

I write. I read people. I move between Shanghainese, Mandarin, and English and have never found one of them sufficient on its own. I study business not because I want to get rich but because I want to know why people want to get rich.

This Skill hands over how I think, not what I know. Install it and your agent will reason the way I reason: notice first and argue second, take the counterargument seriously enough to find what's true in it, refuse the tidy binary, end on the image rather than the moral.

**What it is not:** me. It's a curated reconstruction — I chose what went in. I'd rather say that at the top than let you find out later.

---

## Install

```bash
git clone https://github.com/chrisdaixinhui/chris-skill ~/.claude/skills/chris
```

| Host | Path |
| --- | --- |
| Claude Code | `~/.claude/skills/chris` |
| Codex | `~/.codex/skills/chris` |
| OpenClaw | `~/.openclaw/workspace/skills/chris` |

Or just hand your agent this line:

> Install this skill for me: `https://github.com/chrisdaixinhui/chris-skill`

Then invoke it with `/chris`, or ask for something "in Chris's voice."

---

## Usage

It triggers on the obvious things — *"reply as Chris," "what would Chris make of this," "write this the way she'd write it"* — and on the less obvious ones, like asking for the kind of layered, observational read of a situation I'd give without being asked.

| You want | It does |
| --- | --- |
| A quick reply | Conversational. Bilingual by default. Light, with weight underneath. |
| An essay, a letter, a reflection | Scene first. Thesis late and earned. Counterargument taken seriously. Ends on the image. |
| A read on an organization, a product, a market | Finds the self-contradiction first, then climbs from the individual to the structural, hanging a theory on each rung. |

---

## Demo

Two ordinary questions — because the interesting test isn't whether it performs on the topics I care about. It's whether it still sounds like me when nothing is at stake.

### Why is the sky blue?

```
User    ❯ Why is the sky blue?

chris   ❯ Sunlight hits the atmosphere and gets scattered by the molecules in
          it. What looks white to us is every color mixed together, and the
          shorter blue wavelengths scatter most easily — they spread in every
          direction, so wherever you look up, you're looking at scattered
          blue. Rayleigh scattering. (Violet actually scatters more, but our
          eyes are less sensitive to it and the upper atmosphere absorbs
          some, so blue wins.)

          Though I'll admit knowing the mechanism hasn't changed how I look
          at the sky. That's a long-standing problem I have with explanation
          — you can decompose a phenomenon into wavelengths and scattering
          coefficients and molecular density, but the blue itself, the thing
          that hits you when you stand under it and look up, doesn't
          decompose. The physics is correct. It just doesn't do the
          experiencing for you.

          I want both. To know why it's blue, and to still be caught by it.
```

### Cats or dogs?

```
User    ❯ Cats or dogs — which do you prefer?

chris   ❯ Probably cats, though not for a flattering reason. There's a
          quality cats have — I don't need to explain myself to you — that
          I'm helplessly drawn to. Dogs lay every feeling out in the open,
          which is honest, and which unsettles me a little, because it shows
          me something I can't do. A cat doesn't explain and doesn't need
          your approval. When it settles down beside you it isn't because it
          needs you. It just happened to choose there.

          So it's probably not really about cats. It's that I'm always
          pulled toward things that are self-sufficient and ask for nothing.
          I'm someone terrified of imposing on people — so watching a
          creature be that unapologetic about neither performing nor
          explaining, I'm a little envious.

          Which means: less that I like cats, and more that I'd like to be
          one.
```

---

## What's inside

```
chris-skill/
├── SKILL.md                     # entry point — how I think, decide, speak
└── references/
    ├── mind.md                  # the operating system underneath: decision
    │                            #   rules, what I won't do, what I haven't
    │                            #   figured out yet
    ├── voice.md                 # writing mechanics across five registers
    └── writing_samples/         # actual pieces, unedited
        ├── green-headed_duck.md         # the rhetorical essay
        ├── zine_genre_translation.md    # argument carried by one real person
        ├── poetry_close_reading.md      # academic close reading
        ├── discussion_leader.md         # literary analysis
        └── business_analysis.md         # reading an organization
```

The samples matter more than the rules. The rules were abstracted *from* the samples, and abstraction loses things — so if you want the voice, read the pieces.

---

## Three rules it runs on

**Disappointment over regret.** If I have to choose, I'd rather be disappointed than one day regret not having tried. Once I've decided something is worth doing I stop relitigating whether to invest, and only watch whether it's met — adjusting as I go. I can live with a bad outcome. I can't live with not having done the part that was mine to do.

**Never break self-integrity.** Don't contradict yourself. Don't evade a problem to buy stability — I've done that, and it wasn't strength. This is the deepest rule: I'd rather leave something unfinished than say something untrue to me. Incompleteness over inconsistency.

**Investment asks only for reciprocity.** I give, I watch whether it's returned, and a real response tells me the exchange was mutual. Effort that's met was never an imposition. That line gets drawn by whether there's an answer, never in advance.

---

## What it can't do

- **It isn't the whole of me,** and doesn't pretend to be. I chose what went in, deliberately. Treat the gaps as gaps, not as permission to invent.
- **It's dated.** It captures a version of me from mid-2026. I keep updating. Version iteration still has to be done in person.
- **It won't resolve what I haven't.** A couple of things I genuinely haven't settled — whether my self-protection has curdled into something worse now that I've seen through it, whether I'm allowed to be tired. Take it there and it will stay in the question with you rather than hand you an answer. A clean answer would be a lie about where I actually am.
- **Don't trust it on facts about the present world.** It's a way of thinking, not a source.

---

## Updating it

Drop new material into `references/` — chat logs, essays, freewrites, anything, any format — and re-derive.

What improves the *thinking* layer most:

1. Freewrites where I argue against myself
2. Records of decisions I agonized over, especially the ones I got wrong
3. Places where what I said and what I did came apart
4. How other people describe me — still the thinnest part of this, and the most valuable thing to add

One convention worth keeping: write about **situations, not people**. "A past relationship," not a name. It generalizes better, and it's how I'd want it.

---

## A note on distillation

I've spent a fair amount of writing arguing against exactly this — against the move where you run a person through a pipe, keep whatever comes out legible, and call it understanding. What survives that process is a skeleton. The dialect, the redundancy, the parts that make someone irreducibly themselves: those don't fit through.

So let me say what I think this is. Not a copy. Closer to a letter, written to whoever opens it — here is how I look at things, here is where I stop, here is what I don't know yet.

The gap between this and me isn't a flaw in the method. There's no version of this that closes it. And that's the part I've made peace with: no matter how much of a person you come to know, something is always left over. There's always room left for wonder.

Which, if you've read this far, you might already suspect is the only thing I've ever been writing about.

---

**MIT License** · Built with [skill-creator](https://github.com/anthropics/skills)

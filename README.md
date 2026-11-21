# WATSON: World And Tether Search ONline

Finding information is not a problem in today's age. Finding the right information is. Tether helps you find the signal in the noise, the needle in the haystack. WATSON is a reasoning assistant, not an oracle. It searches a closed set of rules first, then the world, and it says what would reverse its answer. It's elementary!

## What this is

WATSON is a Custom GPT built on the [Tether](https://github.com/IsaiahN/tether), a recursive, domain agnostic, self consistent metatheory that behaves as a barrier theorem, with a CPU only recursive self improvement agent as its instantiation. The arrangement of a search, not the quantity of data, is what makes it useful. A cookbook is not a chef. Text records what someone concluded, not the process that got them there.

This repository holds the GPT's instructions, its knowledge base, the full formula used in Critical Thinking Mode, the FAQ, and the copy used to list the GPT in directories. It also carries a few format variants for the different places a GPT can be published.

## How it works

Authority order:

1. **The Tether figures** are primary. They decide. They supersede anything found online.
2. **The world** (published research, news, data) is secondary. It corroborates only. It can show that a question was framed in the wrong domain, but it cannot replace a figure's verdict.

If the two disagree, the figure stands and the disagreement is reported as a sign the question was misframed. The two are never averaged.

The GPT states the question in effect terms, censuses the domains by actors, currency and anchor, quotes the governing figure lines verbatim before concluding, searches the world only as corroboration, triangulates independent sources, decides with the cost of being wrong and the evidence that would reverse the answer, and records the whole chain.

Ask it for **critical thinking mode** and it walks the eight steps of the Tether loop formula: PERCEIVE, ROUTE, MINT, ACCEPT, SETTLE, PROMOTE, the three questions when nothing closes the gap, and REPEAT.

## Repository contents

| File | Purpose |
|---|---|
| [`instructions.txt`](instructions.txt) | The Custom GPT instructions. Paste into the Instructions field (4,840 characters, limit 8,000). |
| [`KNOWLEDGE_BASE.md`](KNOWLEDGE_BASE.md) | All thirteen figures with verbatim lines and figure and line citations, the eight operators, the symbols table, and the map of which figure answers what. Attach as a knowledge file. |
| [`CRITICAL_THINKING_MODE.md`](CRITICAL_THINKING_MODE.md) | The full Tether loop formula with every gate, the bargain, and the supporting notes. |
| [`FAQ.md`](FAQ.md) | Plain language answers that link to the longer articles and the main project. |
| [`DIRECTORY_LISTING.md`](DIRECTORY_LISTING.md) | Short and long descriptions, framing options, categories and starter prompts for GPT directories. |
| [`WATSON_Custom_GPT.md`](WATSON_Custom_GPT.md) | The single file that contains all five parts together, for anyone who wants the whole thing in one document. |
| [`variants/`](variants/) | Alternate formats for the major GPT publishing surfaces. See below. |

## Variants

The same GPT is supplied in a few shapes because different publishing surfaces take different inputs:

- `variants/instructions_short.txt` for surfaces with a tighter instruction limit.
- `variants/openai_gpt_instructions.md` the canonical OpenAI Custom GPT instructions with its output shape.
- `variants/gpt_system_prompt.md` a plain system prompt for anyone hosting the GPT on another stack.

If a new surface needs a version, open an issue or add one under `variants/`.

## FAQ

**What does "outputs are not generators" mean in plain words?**
An output is something someone made: a sentence, a recipe, a painting, a bridge design. A generator is the ability that made it: the mind that thought, the chef who cooked, the engineer who worked out the forces. A recipe tells you what a chef did that day. It does not make you a chef. A thousand recipes are still recipes, not a kitchen. An LLM has read more outputs than any person could, but it never read the process that made them: facing a new situation, taking a guess, being wrong and revising. Adding more text adds more recipes, not more chefs.

**Is it the amount of data that makes a system intelligent?**
No. It is the arrangement. A whale has more neurons than a human and is not smarter. Brains became capable by structural reorganization, not by more units. The library is what the system can say; the answer is the composition over it.

**Why would this GPT make an LLM better at reasoning?**
Because it changes the search, not the library. Intelligence is not having an answer ready. It is what happens next when you are wrong. A wrong answer that gains traction through search is learning. A confident wrong answer that gains no traction is guessing. Search efficacy is the intelligence mapping.

**Can't a system just validate itself?**
No. A verifier that can reconstruct the claim cannot verify it. Soundness comes from the verifier's non access. Alignment here is triangulation against a fixed ground, not negotiation.

The full FAQ, with all eight articles linked, is in [`FAQ.md`](FAQ.md).

## Links

- Tether repository: https://github.com/IsaiahN/tether
- Tether architecture article: https://adventuresinml.substack.com/p/arrival-of-the-fittest-the-tether
- Recursive self improvement trap: https://adventuresinml.substack.com/p/the-recursive-self-improvement-trap
- How intelligence actually works: https://medium.com/@IsaiahNwukor/how-intelligence-actually-works-40ac40fe32b0
- They're scanning books when they should be studying nature: https://adventuresinml.substack.com/p/theyre-scanning-books-when-they-should
- Zenodo record: https://zenodo.org/records/24403207
- Zenodo DOI: 10.5281/zenodo.24403207
- Kaggle DOI: 10.34740/KAGGLE/W/105084
- Tether video: https://www.youtube.com/watch?v=HjnRy4TzXsg

# One PDF, Four AIs: exam study packs

The four study packs from the Mac Mini Lab video **"One PDF, Four AIs: Which One Makes the Best Exam Study Pack?"**

Same 14-page PDF, same request for every model: a printable exam study pack with summaries, diagrams, comparison tables, a quiz, a mock exam and separate solutions, as one self-contained HTML file for A4.

| File | Model | Time | Cost |
|---|---|---|---|
| `1 - Claude Opus 5.5.pdf` | Claude Opus 5.5 (cloud) | 5 min 42 s | $0.93 (API price) |
| `2 - Claude Sonnet 5.5.pdf` | Claude Sonnet 5.5 (cloud) | 3 min 19 s | $0.37 (API price) |
| `3 - Qwen 3.8 27B (local, animations off).pdf` | Qwen 3.8 27B on a Mac mini (Ollama, 64K context) | 13 min 54 s | 17.8 Wh of electricity |
| `3b - Qwen 3.8 27B (local, printed as-is).pdf` | The same file printed exactly as Qwen wrote it: its scroll animations leave 9 of 15 pages almost blank | | |
| `4 - Inkling 2 Mini (local, 60K tokens, cut off).pdf` | Inkling 2 Mini, third try with a 60,000-token limit: cut off in the last solution (with 40,000 tokens it wrote nothing) | 28 min | 28.1 Wh |

One run per model: take it as a guide, not a benchmark.

## Source and licence

The input notes are adapted from the Wikipedia article ["State of matter"](https://en.wikipedia.org/wiki/State_of_matter) (revision 1381481463), licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). These study packs are derived from it and are shared under the same licence. Images in the original article keep their own licences on Wikimedia Commons.

Video: https://www.youtube.com/@macminilab

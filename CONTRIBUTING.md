# Contributing

This started as a personal reading journal, but it's set up so anyone reading the same book can use or
extend it. Contributions are welcome, especially:

- **Exercise solutions** — if you solved one of the practice prompts in a chapter's `README.md` in an
  interesting way, open a PR adding your notebook cell (please keep the original TODO prompt intact above
  your solution, so others can still try it themselves first).
- **Better diagrams** — the Mermaid diagrams in each chapter README are intentionally simple. If you have a
  clearer visual for a concept, PRs welcome.
- **Corrections** — if a summary misrepresents something from the book, please open an issue with the page
  reference.
- **New appendix chapters** — the book's appendices (autodiff, quantization, SVMs, positional encoding,
  state-space models) aren't in the 30-day plan. If you write one up, add it under `chapters/appendix-x/`
  following the same `README.md` + notebook contract as the main chapters.

## Ground rules

1. Keep chapter README summaries **short** — the goal is "remind me what this chapter taught," not
   "reproduce the chapter." A few paragraphs + a diagram + a takeaway is the target length.
2. Don't paste large verbatim excerpts from the book itself — this repo is notes and original practice
   code, not a copy of copyrighted material.
3. One chapter/topic per PR, please — makes review much easier.
4. If you add a new practice exercise, add a matching TODO cell in the notebook so the structure stays
   consistent across chapters.

## Local setup

```bash
git clone https://github.com/<your-username>/ml-journey.git
cd ml-journey
python3 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

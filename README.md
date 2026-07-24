# 📘 My ML Journey — *Hands-On Machine Learning with Scikit-Learn and PyTorch*

> A public, 30-day reading + coding journal through Aurélien Géron's book — built so both **I** and anyone
> following along can actually retain what's in it, not just skim it.

![status](https://img.shields.io/badge/status-in%20progress-yellow)
![days](https://img.shields.io/badge/plan-30%20days-blue)
![chapters](https://img.shields.io/badge/chapters-19-informational)
![license](https://img.shields.io/badge/license-MIT-lightgrey)

---

## 📖 About the book

**Hands-On Machine Learning with Scikit-Learn and PyTorch** (1st edition, O'Reilly, 2026) by **Aurélien Géron**
is the PyTorch-based successor to the widely used *Hands-On ML with Scikit-Learn, Keras & TensorFlow* series
(nicknamed *homl1/2/3*; this edition is nicknamed **homlp**). It's a two-part book:

- **Part I — Fundamentals of Machine Learning:** the core ideas and classical algorithms (regression,
  classification, trees, ensembles, dimensionality reduction, clustering) built with **Scikit-Learn**.
- **Part II — Neural Networks & Deep Learning:** neural nets from first principles up through CNNs, RNNs,
  and — the book's real centerpiece — **Transformers**, LLMs, vision/multimodal models, diffusion models,
  and reinforcement learning, all built with **PyTorch** and the **Hugging Face** ecosystem.

I'm not affiliated with the author or O'Reilly, this is just my personal study log, structured so it's
useful to *anyone* reading the same book. 🙌

> 💡 **Not read the book yet?** Official info & code: [homl.info](https://homl.info) · author's repo:
> [ageron/handson-mlp](https://github.com/ageron/handson-mlp)

---

## 🗂️ Repo structure

```text
ml-journey/
├── README.md                     ← you are here: intro, plan, how-to
├── chapters/
│   ├── 01-the-machine-learning-landscape/
│   │   ├── README.md             ← short visual summary of the chapter
│   │   └── 01_the_machine_learning_landscape.ipynb   ← my coding practice
│   ├── 02-end-to-end-machine-learning-project/
│   │   ├── README.md
│   │   └── 02_end_to_end_machine_learning_project.ipynb
│   ├── ...
│   └── 19-reinforcement-learning/
│       ├── README.md
│       └── 19_reinforcement_learning.ipynb
├── progress/
│   └── PROGRESS.md               ← daily log / checklist, updated as I go
├── requirements.txt
└── .github/workflows/            ← optional: auto-runs notebooks / lints on push
```

**Every chapter folder follows the same contract:**
- `README.md` → a **short, visual** summary (concepts + a diagram + one key takeaway), enough to remind you
  what the chapter taught without re-reading it.
- `NN_chapter_name.ipynb` → a **starter notebook**: learning goals, a spot to re-implement the book's code,
  and a few practice exercises that push past what the book shows.

This means you can `cd` into any chapter, read a 2-minute README, and immediately start coding, no need to
read the whole repo top to bottom.

---

## 📚 Chapters

| # | Chapter | Folder | Day(s) |
|---|---------|--------|--------|
| 1 | The Machine Learning Landscape | [`chapters/01-...`](chapters/01-the-machine-learning-landscape/) | Day 1 |
| 2 | End-to-End Machine Learning Project | [`chapters/02-...`](chapters/02-end-to-end-machine-learning-project/) | Days 2–3 |
| 3 | Classification | [`chapters/03-...`](chapters/03-classification/) | Day 4 |
| 4 | Training Linear Models | [`chapters/04-...`](chapters/04-training-linear-models/) | Day 5 |
| 5 | Decision Trees | [`chapters/05-...`](chapters/05-decision-trees/) | Day 6 |
| 6 | Ensemble Learning and Random Forests | [`chapters/06-...`](chapters/06-ensemble-learning-and-random-forests/) | Day 7 |
| 7 | Dimensionality Reduction | [`chapters/07-...`](chapters/07-dimensionality-reduction/) | Day 8 |
| 8 | Unsupervised Learning Techniques | [`chapters/08-...`](chapters/08-unsupervised-learning/) | Day 9 |
| 9 | Artificial Neural Networks | [`chapters/09-...`](chapters/09-artificial-neural-networks/) | Day 10 |
| 10 | Neural Nets with PyTorch | [`chapters/10-...`](chapters/10-neural-nets-with-pytorch/) | Day 11 |
| 11 | Training Deep Neural Networks | [`chapters/11-...`](chapters/11-training-deep-neural-networks/) | Day 12 |
| 12 | Deep Computer Vision with CNNs | [`chapters/12-...`](chapters/12-deep-computer-vision-with-cnns/) | Days 13–14 |
| 13 | Processing Sequences Using RNNs and CNNs | [`chapters/13-...`](chapters/13-processing-sequences-using-rnns-and-cnns/) | Day 15 |
| 14 | NLP with RNNs and Attention | [`chapters/14-...`](chapters/14-nlp-with-rnns-and-attention/) | Day 16 |
| 15 | Transformers for NLP and Chatbots | [`chapters/15-...`](chapters/15-transformers-for-nlp-and-chatbots/) | Days 17–19 |
| 16 | Vision and Multimodal Transformers | [`chapters/16-...`](chapters/16-vision-and-multimodal-transformers/) | Day 20 |
| 17 | Speeding Up Transformers | [`chapters/17-...`](chapters/17-speeding-up-transformers/) | Day 21 |
| 18 | Autoencoders, GANs, and Diffusion Models | [`chapters/18-...`](chapters/18-autoencoders-gans-and-diffusion-models/) | Days 22–23 |
| 19 | Reinforcement Learning | [`chapters/19-...`](chapters/19-reinforcement-learning/) | Days 24–25 |

*(The book also has online-only appendices, autodiff, quantization, SVMs, positional encoding, state-space
models, not covered day-by-day here, but worth a skim on Day 26.)*

---

## 🗓️ The 30-Day Plan

The plan front-loads easier, foundational chapters and gives the hardest material (Transformers, generative
models, RL) two full days each, plus built-in buffer/review days so slipping a day doesn't wreck the schedule.

| Day | Focus | Goal for the day |
|-----|-------|-------------------|
| 1 | Ch 1 — ML Landscape | Understand the categories of ML; no heavy coding yet |
| 2–3 | Ch 2 — End-to-End Project | Build the full pipeline once: EDA → clean → train → tune → evaluate |
| 4 | Ch 3 — Classification | Precision/recall/ROC on MNIST; do real error analysis |
| 5 | Ch 4 — Training Linear Models | Implement gradient descent by hand; compare regularizers |
| 6 | Ch 5 — Decision Trees | Train + visualize a tree; see it overfit and rein it in |
| 7 | Ch 6 — Ensembles & Random Forests | Compare bagging vs. boosting on the same dataset |
| 8 | Ch 7 — Dimensionality Reduction | Visualize high-dimensional data in 2D with PCA |
| 9 | Ch 8 — Unsupervised Learning | Cluster unlabeled data with K-Means, DBSCAN, GMM |
| 10 | 🧩 **Buffer / Review** | Catch up, redo any weak exercise, mini end-to-end project using Part I only |
| 11 | Ch 9 — Artificial Neural Networks | Understand backprop conceptually; train your first MLP |
| 12 | Ch 10 — Neural Nets with PyTorch | Rewrite Ch. 9's MLP in raw PyTorch; learn the training loop |
| 13 | Ch 11 — Training Deep Neural Networks | Add BatchNorm, Dropout, Adam; fight vanishing gradients |
| 14–15 | Ch 12 — Deep Computer Vision (CNNs) | Fine-tune a pretrained CNN via transfer learning |
| 16 | Ch 13 — Sequences (RNNs/CNNs) | Forecast a real time series with an LSTM |
| 17 | Ch 14 — NLP with RNNs & Attention | Build a tiny encoder-decoder translator; visualize attention |
| 18 | 🧩 **Buffer / Review** | Consolidate Part II fundamentals before Transformers |
| 19–21 | Ch 15 — Transformers for NLP & Chatbots | Build self-attention from scratch; fine-tune & build a mini RAG chatbot |
| 22 | Ch 16 — Vision & Multimodal Transformers | Run ViT + CLIP zero-shot classification |
| 23 | Ch 17 — Speeding Up Transformers | Benchmark KV-caching and LoRA fine-tuning |
| 24–25 | Ch 18 — Autoencoders, GANs, Diffusion | Train an autoencoder + a small GAN; explore a diffusion model |
| 26–27 | Ch 19 — Reinforcement Learning | Train a PPO agent with Stable-Baselines3 on Atari |
| 28 | 🏆 **Capstone, Part 1** | Pick a real problem; frame it, get data, build a baseline |
| 29 | 🏆 **Capstone, Part 2** | Iterate on the model, evaluate honestly, write it up |
| 30 | 🎉 **Wrap-up & Share** | Polish READMEs, write a "what I learned" post, share the repo |

> Adjust freely, the point of a plan is to have a default, not a cage. If Transformers eat 4 days instead of
> 3, steal a day from the buffers, not from sleep.

---

## 🚀 How to use this repo

### If you just want to read along
Every chapter's `README.md` is short and self-contained, browse `chapters/` and read them in order.

### If you want to code along
```bash
git clone https://github.com/<your-username>/ml-journey.git
cd ml-journey

python3 -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate

pip install -r requirements.txt
jupyter lab
```
Then open any `chapters/<NN-...>/*.ipynb` and start from the top.

### If you want to fork this as *your own* reading journal
1. Fork the repo.
2. Delete the code cells' contents (keep the structure) if you want a truly blank slate.
3. Use the `progress/PROGRESS.md` checklist to track your own pace — update it daily, it's oddly motivating.
4. Open a PR back here if you write an exercise solution you're proud of — this repo is meant to grow with
   contributions from anyone else reading the book.

---

## ✅ Progress tracking

See [`progress/PROGRESS.md`](progress/PROGRESS.md) for the running daily log and a checklist of all 19
chapters. Each chapter's own README also ends with a mini progress checklist.

---

## 🤝 Contributing

Found a better way to explain a concept, a cleaner exercise, or a bug in a notebook? PRs and issues are
welcome — see [`CONTRIBUTING.md`](CONTRIBUTING.md).

## 📄 License

Code in this repo is under the [MIT License](LICENSE) — the book's own text and figures are **not**
included here and remain © Aurélien Géron / O'Reilly Media. This repo only contains my own notes,
diagrams, and practice code.

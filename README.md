# Mikołaj Pacek

## Research Engineer — large generative models & evaluation

I train large generative models and build the evaluation systems that make them
trustworthy. NeurIPS'23 author (Focused Transformer / LongLLaMA), MSc in Machine
Learning (University of Warsaw), ~5 years across Google, Pinterest, NVIDIA and
IDEAS NCBR. Open to research-engineer roles in music, robotics and evaluation.

Currently: fine-tuning a text-to-MIDI model on 200k (text, MIDI) pairs (Gemma,
JAX, TPU Research Cloud), and building agent / instruction-following evaluation
systems at Google.

**[Google Scholar](https://scholar.google.com/citations?user=eh6iEbQAAAAJ)** ·
**[LinkedIn](https://www.linkedin.com/in/mikolaj-pacek/)** ·
**[X / Twitter](https://twitter.com/MikolajPacek)** ·
**[Email](mailto:pacek.mik@gmail.com)**

## Selected research

- **Focused Transformer: Contrastive Training for Context Scaling** — *NeurIPS 2023*
  Identified the *distraction* issue in LLMs and introduced a contrastive
  training procedure that scales context up to 256k tokens. Released
  **LongLLaMA**. Led experiments; used Ray + FAISS for large-scale approximate
  KNN search. · [arXiv](https://arxiv.org/abs/2307.03170) ·
  [thread](https://twitter.com/s_tworkowski/status/1677125863429795840)

- **Planning and Learning Using Adaptive Entropy Tree Search** — *IJCNN 2022*
  Combined tree search and deep RL in a maximum-entropy framework, surpassing
  AlphaZero on Atari with better hyperparameter robustness. · [arXiv](https://arxiv.org/abs/2102.06808) ·
  [IEEE](https://ieeexplore.ieee.org/document/9892556) · [code](https://gitlab.com/awarelab/planning)

- **Curriculum and Decentralized Learning in Google Research Football** — *BayLearn 2020*
  Collaboration with Google Brain; a curriculum that trained 10× faster and
  reached a Kaggle silver medal. · [site](https://sites.google.com/view/rl-football/)

## Selected projects

- **Music Composing AI Assistant** — Gemma fine-tuned on 200k (text, MIDI)
  pairs, integrated with MIDI editing software. JAX/TPU. 
  [demo](https://www.youtube.com/watch?v=ZXVBDNE4XWM)
- **koryta.pl** — a multi-step production pipeline (crawl → score → fact-extract
  → dedup) over 100M+ crawled Polish articles, turning them into a structured
  NoSQL graph of political connections. Python, GCS/Firestore, VLLM.
  [site](https://koryta.pl) · [code](https://github.com/SzymonPajzert/koryta)
- **MBZIRC 2022–2024** — finalist; ML perception for an autonomous drone
  (vessel detection, identification and segmentation, sim + real world).
  [challenge](https://www.mbzirc.com/)

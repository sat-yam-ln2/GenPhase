# GenPhase

## 🧠 What you're trying to do — in plain English

Imagine you're a scientist who wants to understand how matter changes — like when ice melts into water, or when magnets stop being magnetic at high temperatures. These are called phase changes — and they happen in all kinds of materials.

Now, usually scientists have to run tons of experiments or super slow computer simulations to figure out where and how those changes happen.

## 🧩 Why it's cool

You're basically building a scientific discovery machine — a system that can find new physics patterns without needing humans to label or guess everything first.

It's like giving the AI a map of how materials behave, and letting it color in where the interesting stuff happens — the borders between different "worlds" of matter.

## 🌍 In even simpler terms

You're training a computer to be curious — it looks at data from materials and says, "Something's changing here! This might be a new discovery!"

That's your project: An AI scientist that finds hidden changes in physical systems all by itself.

## 📚 Curated Reading List

### Core motivating work (generative mapping / classifiers)

- **Arnold et al., Mapping Out Phase Diagrams with Generative Classifiers** (Phys. Rev. Lett., 2024) — the recent generative-approach demonstration that motivated your idea.  
  [Physical Review Link](https://link.aps.org/doi/10.1103/PhysRevLett.132.207301)

- **MIT News coverage summary** (non-technical, useful for motivation / outreach).  
  [MIT News](https://news.mit.edu/2024/ai-method-can-spot-patterns-in-phase-changes-0529)

### Unsupervised / autoencoder studies for phase transitions

- **K.-K. Ng & M.-F. Yang, Unsupervised learning of phase transitions via modified anomaly detection with autoencoders**, Phys. Rev. B (2023) — an example of autoencoder/anomaly approaches.  
  [Physical Review Link](https://link.aps.org/doi/10.1103/PhysRevB.107.205132)

- **S. J. Wetzel, Unsupervised learning of phase transitions: From PCA to VAEs** (review-style baseline reference cited widely).  
  [CERN Document Server](https://cds.cern.ch/record/2284424)

### Generative model methods you'll use

- **Kihyuk Sohn et al., Learning Structured Output Representation using Deep Conditional Generative Models** (the canonical conditional-VAE / cVAE paper).  
  [NeurIPS Papers](https://papers.nips.cc/paper/2015/hash/8d55a249e6baa5c06772297520da2051-Abstract.html)

- **Ivan Kobyzev, S. Prince & M. Brubaker, Normalizing Flows: An Introduction & Review** (survey) — use this as your flows primer.  
  [arXiv](https://arxiv.org/abs/1908.09257)

- **(Review) Normalizing Flows for Probabilistic Modeling and Inference** (JMLR) — thorough technical review.  
  [Journal of Machine Learning Research](https://jmlr.org/papers/v22/19-1028.html)

- Score/score-based & diffusion references are also recommended for later extensions (see review citations inside the flows/scores literature above).

### Physics-informed ML / constraints

- **Raissi, Perdikaris & Karniadakis, Physics-Informed Neural Networks (PINNs)** — how to add differential/physics constraints as losses.

### Uncertainty / calibration / OOD issues for generative models

- **Lakshminarayanan et al., Simple and scalable predictive uncertainty using deep ensembles** — ensemble UQ baseline.

- **Guo et al., On Calibration of Modern Neural Networks** — temperature scaling and calibration techniques.

- **Eric Nalisnick et al., Do deep generative models know what they don't know?** — cautionary paper about raw likelihoods for novelty detection.

### Finite-size scaling & physics validation

- **Classic finite-size scaling reference** (Privman et al., collection) and Barber review (useful for scaling analyses).  
  [World Scientific](https://www.worldscientific.com/worldscibooks/10.1142/1011)

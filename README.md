<div align="center">
<h1>Peter Alexander 捷虎 Graham</h1>
</div>

<img src="images/lofi-avatar.png" width="38%" align="right">

ML researcher and engineer working at the seam between biological and artificial neural computation. Brown — Cognitive Neuroscience and Data Science; honors thesis on EEG signal detection with wavelet decomposition and ROC analysis under varied noise regimes. I think the architectures we build are most interesting when read against the ones evolution already shipped, and most useful when that comparison is made quantitative.

---

### Tech stack

**Neural data & signal processing** — NumPy · SciPy · MNE · wavelets / STFT
**ML & deep learning** — PyTorch · JAX · Triton · HuggingFace · scikit-learn · W&B
**MLOps & cloud** — Docker · AWS · GCP · Postgres

---

### What I'm building

- **[cortex-engine](https://github.com/peterajhgraham/cortex-engine)** — transformer-based neural decoders as full-stack ML systems; what does a serious training/serving stack look like when the input modality is spikes, not tokens?
- **[neural-representation-explorer](https://github.com/peterajhgraham/neural-representation-explorer)** — simulated population activity through PCA/UMAP; where does the low-dimensional manifold story hold, and where does it quietly break?
- **[honors-thesis](https://github.com/peterajhgraham/honors-thesis)** — wavelet-based EEG band detection benchmarked across white, pink, and structured noise via ROC; signal detection theory as a sharp tool, not a slogan.

---

### What I'm thinking about

- The manifold hypothesis in neural data: when is "low-dimensional structure" a real claim about computation versus an artifact of the dimensionality reduction we reached for first?
- Transformer attention and hippocampal retrieval as variants of the same content-addressable lookup — what does each formalism predict that the other forbids?
- Signal detection theory (d′, ROC, criterion) as a more honest evaluation language for ML systems than accuracy on a held-out set.
- Sparse, structured priors from cortical circuits as inductive bias: what survives translation into a loss function, and what is just metaphor.

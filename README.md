<div align="center">
<h1>Peter Alexander 捷虎 Graham</h1>
<em>Bay Area native · Brown '25 · still mostly thinking about brains</em>
</div>

<img src="images/lofi-avatar.png" width="38%" align="right">

ML researcher and engineer working at the seam between biological and artificial neural computation. I studied Cognitive Neuroscience and Data Science at Brown, where my honors thesis pulled apart EEG signals with wavelets and ROC curves under different flavors of noise. The architectures we build feel most interesting to me when read against the ones evolution already shipped - and most useful when that comparison is made quantitative.

Outside of that: long runs in the hills, lo-fi on repeat, and a slowly growing pile of half-read papers on the desk.

---

### Tools

Most days I'm in PyTorch or JAX, dropping into Triton when the kernel matters and HuggingFace when it doesn't, with scikit-learn and W&B around for the unglamorous parts. Neural data lives in NumPy, SciPy, and MNE - wavelets and STFTs when the frequency axis is the interesting one. Everything ships through Docker onto AWS or GCP, with Postgres holding the things I don't want to lose.

---

### What I'm building

- 🧠 **[cortex-engine](https://github.com/peterajhgraham/cortex-engine)** - transformer-based neural decoders as full-stack ML systems. What does a serious training and serving stack look like when the input modality is spikes, not tokens?
- 🌀 **[neural-representation-explorer](https://github.com/peterajhgraham/neural-representation-explorer)** - simulated population activity pushed through PCA and UMAP. Where does the low-dimensional manifold story hold, and where does it quietly break?
- 🌊 **[honors-thesis](https://github.com/peterajhgraham/honors-thesis)** - wavelet-based EEG band detection benchmarked across white, pink, and structured noise via ROC. Signal detection theory as a sharp tool, not a slogan.

---

### What I'm thinking about

- The manifold hypothesis in neural data - when is "low-dimensional structure" a real claim about computation, and when is it an artifact of the dimensionality reduction we reached for first?
- Transformer attention and hippocampal retrieval as variants of the same content-addressable lookup. What does each formalism predict that the other forbids?
- Signal detection theory - d′, ROC, criterion - as a more honest evaluation language for ML systems than accuracy on a held-out set.
- Sparse, structured priors from cortical circuits as inductive bias. What survives translation into a loss function, and what is just metaphor.

<br>

<sub>🌄 if you read this far, go outside.</sub>



## Contents

- [Most-Read Foundational Papers (Mechanistic Interpretability Roots)](#most-read-foundational-papers-mechanistic-interpretability-roots)
- [Foundational Vision Concept-Learning Papers (the Classics)](#foundational-vision-concept-learning-papers-the-classics)
- [Latest Papers by Year & Conference](#latest-papers-by-year--conference)
  - [2023](#2023) · [2024](#2024) · [2025](#2025) · [2026](#2026)
- [Surveys & Benchmarks](#surveys--benchmarks)
- [Tag Index](#tag-index)
- [Contributing](#contributing)

---

## Most-Read Foundational Papers (Mechanistic Interpretability Roots)

These aren't vision papers — they're the LLM interpretability work that invented the sparse-autoencoder (SAE) / dictionary-learning approach to concept extraction now being ported into vision. Read these first; most of the vision-SAE work below builds directly on them.

1. **[Toy Models of Superposition](https://arxiv.org/abs/2209.10652)** — Elhage et al., Anthropic, 2022. `superposition` `LLM` `foundational`
2. **[Towards Monosemanticity: Decomposing Language Models with Dictionary Learning](https://transformer-circuits.pub/2023/monosemantic-features)** — Bricken et al., Anthropic, 2023. `SAE` `dictionary-learning` `LLM`
3. **[Sparse Autoencoders Find Highly Interpretable Features in Language Models](https://arxiv.org/abs/2309.08600)** — Cunningham et al., 2023 / ICLR 2024. `SAE` `LLM`
4. **[Scaling and Evaluating Sparse Autoencoders](https://arxiv.org/abs/2406.04093)** — Gao et al., OpenAI, 2024. `SAE` `scaling` `LLM`
5. **[Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet](https://transformer-circuits.pub/2024/scaling-monosemanticity/)** — Templeton et al., Anthropic, 2024. `SAE` `production-scale` `LLM`
6. **[Improving Dictionary Learning with Gated Sparse Autoencoders](https://arxiv.org/abs/2404.16014)** — Rajamanoharan et al., DeepMind, 2024. `SAE` `architecture` `LLM`
7. **[Jumping Ahead: Improving Reconstruction Fidelity with JumpReLU Sparse Autoencoders](https://arxiv.org/abs/2407.14435)** — Rajamanoharan et al., DeepMind, 2024. `SAE` `architecture` `LLM`
8. **[Gemma Scope: Open Sparse Autoencoders Everywhere All At Once on Gemma 2](https://arxiv.org/abs/2408.05147)** — Lieberum et al., DeepMind, 2024. `SAE` `open-source` `LLM`
9. **[SAEBench: A Comprehensive Benchmark for Sparse Autoencoders in Language Model Interpretability](https://arxiv.org/abs/2503.09532)** — Karvonen et al., ICML 2025. `SAE` `benchmark` `LLM`
10. **[Sparse Autoencoders Learn Monosemantic Features in Vision-Language Models](https://arxiv.org/abs/2504.02821)** — Pach et al., NeurIPS 2025. `SAE` `VLM` `vision` — the bridge paper into vision.

## Foundational Vision Concept-Learning Papers (the Classics)

The other lineage: concept-based interpretability that started directly in vision, independent of the SAE line above. This is the classic "concept learning" canon — concept bottlenecks, concept activation vectors, prototypes, and neuro-symbolic concepts.

- **[Network Dissection: Quantifying Interpretability of Deep Visual Representations](https://arxiv.org/abs/1704.05796)** — Bau et al., CVPR 2017. `concept-probing` `CNN`
- **[Interpretability Beyond Feature Attribution: Concept Activation Vectors (TCAV)](https://arxiv.org/abs/1711.11279)** — Kim et al., ICML 2018. `CAV` `foundational`
- **[This Looks Like That: Deep Learning for Interpretable Image Recognition](https://arxiv.org/abs/1806.10574)** — Chen et al. (ProtoPNet), NeurIPS 2019. `prototype` `interpretable-by-design`
- **[Towards Automatic Concept-based Explanations (ACE)](https://arxiv.org/abs/1902.03129)** — Ghorbani et al., NeurIPS 2019. `concept-discovery` `post-hoc`
- **[The Neuro-Symbolic Concept Learner](https://arxiv.org/abs/1904.12584)** — Mao et al., ICLR 2019. `neuro-symbolic` `VQA`
- **[Concept Bottleneck Models](https://arxiv.org/abs/2007.04612)** — Koh et al., ICML 2020. `CBM` `foundational`
- **[Concept Whitening for Interpretable Image Recognition](https://arxiv.org/abs/2002.01650)** — Chen, Bei & Rudin, *Nature Machine Intelligence*, 2020. `latent-space` `interpretable-by-design`

## Latest Papers by Year & Conference

Vision- and VLM-focused concept-learning papers, 2023–2026. Both lineages above (CBM/CAV and SAE) are represented — recent work increasingly merges the two.

### 2023

| Paper                                                        | Venue      | Tags                           |
| ------------------------------------------------------------ | ---------- | ------------------------------ |
| [Language in a Bottle (LaBo)](https://arxiv.org/abs/2211.11158) — Yang et al. | CVPR 2023  | `CBM` `LLM-guided` `zero-shot` |
| [Post-hoc Concept Bottleneck Models](https://arxiv.org/abs/2205.15480) — Yuksekgonul et al. | ICLR 2023  | `CBM` `post-hoc`               |
| [Label-Free Concept Bottleneck Models](https://arxiv.org/abs/2304.06129) — Oikarinen et al. | ICLR 2023  | `CBM` `zero-shot` `ImageNet`   |
| [Concept Bottleneck Generative Models](https://openreview.net/pdf?id=zFOdOChRPR) — Ismail et al. | ICLR 2023  | `CBM` `generative`             |
| [Probabilistic Concept Bottleneck Models](https://arxiv.org/abs/2306.01574) — Kim et al. | ICML 2023  | `CBM` `uncertainty`            |
| [Concept-based Explainable AI: A Survey](https://arxiv.org/abs/2312.12936) — Poeta et al. | arXiv 2023 | `survey` `taxonomy`            |

### 2024

| Paper                                                        | Venue        | Tags                         |
| ------------------------------------------------------------ | ------------ | ---------------------------- |
| [Incremental Residual Concept Bottleneck Models (Res-CBM)](https://arxiv.org/abs/2404.08978) — Shang et al. | CVPR 2024    | `CBM` `concept-completeness` |
| [Pre-trained Vision-Language Models Learn Discoverable Visual Concepts](https://arxiv.org/abs/2404.12652) | arXiv 2024   | `concept-discovery` `VLM`    |
| [VLG-CBM: Training Concept Bottleneck Models with Vision-Language Guidance](https://arxiv.org/abs/2408.01432) — Srivastava et al. | NeurIPS 2024 | `CBM` `VLM` `grounding`      |
| [Coarse-to-Fine Concept Bottleneck Models](https://arxiv.org/abs/2310.02116) — Panousis et al. | NeurIPS 2024 | `CBM` `hierarchical` `VLM`   |
| [Concept Complement Bottleneck Model for Interpretable Medical Image Diagnosis](https://arxiv.org/abs/2410.15446) | arXiv 2024   | `CBM` `medical-imaging`      |
| [Bayesian Concept Bottleneck Models with LLM Priors](https://arxiv.org/abs/2410.15555) | arXiv 2024   | `CBM` `Bayesian` `LLM-prior` |

### 2025

| Paper                                                        | Venue      | Tags                                     |
| ------------------------------------------------------------ | ---------- | ---------------------------------------- |
| [Sparse Autoencoders for Scientifically Rigorous Interpretation of Vision Models](https://arxiv.org/abs/2502.06755) — Stevens et al. | arXiv 2025 | `SAE` `vision` `methodology`             |
| [Archetypal SAE: Adaptive and Stable Dictionary Learning for Concept Extraction in Large Vision Models](https://arxiv.org/abs/2502.12892) — Fel et al. | arXiv 2025 | `SAE` `stability` `vision`               |
| [Sparse Autoencoders Reveal Selective Remapping of Visual Concepts During Adaptation (PatchSAE)](https://arxiv.org/abs/2412.05276) — Lim et al. | ICLR 2025  | `SAE` `CLIP` `adaptation`                |
| [Interpreting CLIP with Hierarchical Sparse Autoencoders (Matryoshka SAE)](https://arxiv.org/abs/2502.20578) — Zaigrajew et al. | ICML 2025  | `SAE` `CLIP` `hierarchical`              |
| [Concept Steerers: Leveraging K-Sparse Autoencoders for Test-Time Controllable Generation](https://arxiv.org/abs/2501.19066) | arXiv 2025 | `SAE` `diffusion` `steering`             |
| [Emergence and Evolution of Interpretable Concepts in Diffusion Models](https://arxiv.org/abs/2504.15473) | arXiv 2025 | `SAE` `diffusion` `generative`           |
| [SPARC: Concept-Aligned Sparse Autoencoders for Cross-Model and Cross-Modal Interpretability](https://arxiv.org/abs/2507.06265) | arXiv 2025 | `SAE` `cross-modal`                      |
| [Zero-shot Concept Bottleneck Models](https://arxiv.org/abs/2502.09018) — Yamaguchi et al. | arXiv 2025 | `CBM` `zero-shot`                        |
| [Counterfactual Concept Bottleneck Models](https://arxiv.org/abs/2402.01408) — Dominici et al. | ICLR 2025  | `CBM` `counterfactual`                   |
| [CLIP-Free, Label-Free, Unsupervised Concept Bottleneck Models](https://arxiv.org/abs/2503.10981) | arXiv 2025 | `CBM` `unsupervised` `label-free`        |
| [Hybrid Concept Bottleneck Models](https://openaccess.thecvf.com/content/CVPR2025/html/Liu_Hybrid_Concept_Bottleneck_Models_CVPR_2025_paper.html) — Liu et al. | CVPR 2025  | `CBM` `dynamic-concepts`                 |
| [Show and Tell: Spatially-Aware Concept Bottleneck Models](https://cvpr.thecvf.com/virtual/2025/poster/33212) | CVPR 2025  | `CBM` `spatial`                          |
| [Discovering Fine-Grained Visual-Concept Relations (Disentangled Optimal Transport CBM)](https://arxiv.org/abs/2505.07209) — Xie et al. | CVPR 2025  | `CBM` `optimal-transport` `fine-grained` |
| [A Comprehensive Survey on the Risks and Limitations of Concept-based Models](https://arxiv.org/abs/2506.04237) — Sinha & Zhang | arXiv 2025 | `survey` `risks`                         |
| [Flexible Concept Bottleneck Model](https://arxiv.org/abs/2511.06678) | arXiv 2025 | `CBM` `flexibility`                      |
| [A Geometric Unification of Concept Learning with Concept Cones](https://arxiv.org/abs/2512.07355) | arXiv 2025 | `theory` `geometric`                     |

### 2026

| Paper                                                        | Venue      | Tags                      |
| ------------------------------------------------------------ | ---------- | ------------------------- |
| [Interpretable and Steerable Concept Bottleneck Sparse Autoencoders](https://arxiv.org/abs/2512.10805) — Narayanaswamy et al. | CVPR 2026  | `SAE` `CBM` `steerable`   |
| [Learning Concept Bottleneck Models from Mechanistic Explanations (M-CBM)](https://arxiv.org/abs/2603.07343) — De Santis et al. | ICLR 2026  | `SAE` `CBM` `mechanistic` |
| [Hierarchical Concept-based Interpretable Models](https://arxiv.org/abs/2602.23947) | arXiv 2026 | `CBM` `hierarchical`      |
| [Explaining CLIP Zero-shot Predictions Through Concepts](https://arxiv.org/abs/2603.28211) | arXiv 2026 | `CBM` `CLIP` `zero-shot`  |
| [Matryoshka Concept Bottleneck Models](https://arxiv.org/abs/2605.20612) | arXiv 2026 | `CBM` `hierarchical`      |

> Note: 2026 is still in progress as of this writing (July 2026) — expect CVPR/ICML/ICCV 2026 additions throughout the year.

## Surveys & Benchmarks

Good starting points for orienting yourself in the field:

- **[Concept-based Explainable AI: A Survey](https://arxiv.org/abs/2312.12936)** — Poeta et al., 2023. Nine-category taxonomy of concept-based XAI methods.
- **[A Comprehensive Survey on the Risks and Limitations of Concept-based Models](https://arxiv.org/abs/2506.04237)** — Sinha & Zhang, 2025. Concept leakage, entanglement, adversarial vulnerabilities.
- **[SAEBench](https://arxiv.org/abs/2503.09532)** — Karvonen et al., ICML 2025. Eight-metric benchmark for SAE quality (LLM-focused, but the eval methodology transfers to vision SAEs).

## Tag Index

- `CBM` — Concept Bottleneck Model
- `SAE` — Sparse Autoencoder
- `CAV` — Concept Activation Vector
- `VLM` — Vision-Language Model
- `CLIP` — CLIP-specific
- `LLM` — Rooted in language-model interpretability (Most-Read section)
- `diffusion` / `generative` — Diffusion or other generative image models
- `zero-shot` / `label-free` — No labeled concept data required
- `post-hoc` — Interpretability added after training (vs. built-in)
- `interpretable-by-design` — Ante-hoc / inherently interpretable architecture
- `concept-discovery` — Unsupervised concept extraction
- `hierarchical` — Coarse-to-fine or multi-level concept structure
- `counterfactual` — Concept-based counterfactual reasoning/intervention
- `uncertainty` / `Bayesian` — Probabilistic concept modeling
- `steering` / `steerable` — Using concepts to control model output
- `cross-modal` — Cross-model or cross-modal alignment
- `medical-imaging` — Applied to clinical/medical images
- `survey` — Survey or taxonomy paper
- `benchmark` — Benchmark or evaluation suite
- `theory` / `geometric` — Theoretical or geometric analysis
- `mechanistic` — Built using mechanistic-interpretability tools (SAEs, circuits)

## Contributing

Favor papers with a public PDF/arXiv link and a clear concept-learning contribution (not just concept-adjacent XAI in general). To suggest an addition: title, authors, venue/year, link, and 2–4 tags from the index above.

## License

CC0 1.0 (public domain) 

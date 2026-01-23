# YOTO — You Only Touch Once

Mechanism-Aware Magnetoelastic Multimodal Haptic Learning Framework

YOTO (You Only Touch Once) is a mechanism-aware learning framework for robust,
cross-domain haptic perception using magnetoelastic multimodal signals. By embedding
physical signal formation principles directly into the learning architecture, YOTO
extracts domain-generalizable representations from a single physical interaction,
rather than relying on repeated exploration or domain-specific retraining.

This repository releases the full learning framework described in the accompanying
manuscript, which is currently under active development and preparation.

---

## What This Repository Contains

This codebase provides a complete implementation of the YOTO learning architecture,
including:

- Energy-gated node descriptor construction based on displacement-current energy
- Symmetry-regularized metric adjacency learning for adaptive graph topology
- Cross-finger SE-Attention for heterogeneous channel integration
- A physically aligned network sequence from multi-scale convolution to graph
  reasoning and attention fusion
- Training routines for analyzing convergence behavior, gradient flow, and loss
  landscape geometry

All core architectural components and learning mechanisms described in the manuscript
are explicitly implemented.

---

## Reproducibility Statement

This repository is released to support reproducibility at the conceptual and
architectural level.

The provided code enables independent researchers to:

- Verify the formulation and interaction of each mechanism-aware module
- Reproduce learning dynamics, optimization stability, and convergence trends
- Re-implement the framework on custom haptic sensing platforms following the
  described design principles

---

## Important Scope Clarification

This repository is **not a plug-and-play application**.

The following components are intentionally excluded:

- Raw multimodal haptic datasets
- Sensor-specific preprocessing and calibration pipelines
- Hardware-dependent signal conditioning parameters

Exact numerical replication of reported performance requires reproducing the entire
sensing system and data acquisition process described in the manuscript, including
the magnetoelastic multimodal haptic sensing system.

The absence of these elements reflects the physical coupling between the learning
framework and the sensing hardware, rather than a limitation of the software release.

---

## Reproducibility vs. Direct Usability

YOTO is designed as a research framework, not as a turnkey tactile classification tool.

The code is sufficient to reproduce the scientific claims of the work, including
mechanism-aware representation learning, stable optimization behavior, and
cross-domain generalization trends. Direct reuse without re-implementation of the
sensing pipeline is neither expected nor recommended.

---

## Intended Audience

This repository is intended for researchers working on:

- Physics-informed machine learning
- Graph-based and relational representation learning
- Multimodal tactile or haptic sensing systems
- Cross-domain generalization in embodied intelligence

---

## Citation

If you use this framework or build upon the ideas presented here, please cite:
@unpublished{YOTO,
  title  = {Deep-Learning-Assisted Magnetoelastic Multimodal Intelligent Haptic Perception System},
  author = {Du, Yifei and others},
  note   = {Manuscript in preparation}
}

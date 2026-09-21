# Baremetal Bioinformatics

<p align="center">
  <img src="https://raw.githubusercontent.com/Baremetal-Bioinformatics/.github/main/assets/logo.svg" width="160" alt="Baremetal Bioinformatics DNA processor logo">
</p>

**Correctness-first bioinformatics systems for modern heterogeneous hardware.**

We build and measure open tools that make genomics workflows faster, more reproducible, and more hardware-aware—without weakening scientific output contracts.

## Principles

- **Outputs are the contract.** Replacements are compared with the tools and pipelines they claim to reproduce.
- **Measure end to end.** Kernel speedups matter only when they improve the complete workflow against a named comparator.
- **Evidence travels with claims.** Benchmarks record versions, inputs, commands, checks, and limitations.
- **Optimize the dataflow.** Avoid repeated parsing, serialization, copying, and memory movement before reaching for specialized hardware.

## Projects

- [**umseq**](https://github.com/Baremetal-Bioinformatics/umseq) — a Rust/CUDA pressure test of unified-memory RNA-seq processing on DGX Spark and Apple silicon.
- [**Research Roadmap**](https://github.com/orgs/Baremetal-Bioinformatics/projects/1) — cross-repository milestones, experiments, and dependencies.

More coordinated projects will be added as their contracts and reproduction paths are ready.

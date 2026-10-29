# Baremetal Bioinformatics

<p align="center">
  <img src="https://raw.githubusercontent.com/Baremetal-Bioinformatics/.github/main/assets/logo.svg" width="160" alt="Baremetal Bioinformatics DNA processor logo">
</p>

**Correctness-first bioinformatics systems for modern heterogeneous hardware.**

We reimplement established genomics workflows as purpose-built applications, then check every stage against the pinned reference they claim to reproduce. [baremetalbio.dev](https://baremetalbio.dev/)

## Principles

- **Outputs are the contract.** Replacements are compared with the tools and pipelines they claim to reproduce.
- **Measure end to end.** Kernel speedups matter only when they improve the complete workflow against a named comparator.
- **Evidence travels with claims.** Benchmarks record versions, inputs, commands, checks, and limitations.
- **Optimize the dataflow.** Avoid repeated parsing, serialization, copying, and memory movement before reaching for specialized hardware.

## Projects

- [**nomics**](https://github.com/Baremetal-Bioinformatics/nomics): the nf-core/sarek germline pipeline, FASTQ to VCF, reimplemented from scratch as one Rust process on CPU and CUDA. Same records as sarek 3.10.0 at every stage boundary; a 30× HG002 genome in 1 h 00 min against 11 h 24 min for sarek on one DGX Spark. Research software, not clinically validated. [Results](https://github.com/Baremetal-Bioinformatics/nomics/blob/main/RESULTS.md) · [Reproduce](https://github.com/Baremetal-Bioinformatics/nomics/blob/main/REPRODUCE.md)
- [**umseq**](https://github.com/Baremetal-Bioinformatics/umseq): an earlier experiment in unified-memory RNA-seq processing on DGX Spark, now superseded by nomics. Kept for reference.
- [**Research Roadmap**](https://github.com/orgs/Baremetal-Bioinformatics/projects/1): cross-repository milestones, experiments, and dependencies.

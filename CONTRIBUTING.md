# Contributing

Thanks for contributing to Baremetal Bioinformatics.

## Before opening a change

1. Read the target repository's `README.md`, `CONTRIBUTING.md`, and development instructions.
2. Open an issue for changes that alter public outputs, compatibility policy, architecture, or benchmark interpretation.
3. Keep changes scoped and include tests for observable behavior.

## Scientific and performance claims

- Name the exact comparator, input, hardware, software versions, and command.
- Preserve raw measurements or a durable evidence reference; never reconstruct missing timings.
- Treat output compatibility as an explicit gate. Do not weaken, filter, or normalize a comparison merely to make it pass.
- Separate correctness, performance, and biological-equivalence claims.
- Report negative results and limitations plainly.

## Pull requests

A pull request should explain:

- what changed and why;
- which outputs or interfaces may change;
- tests and validation performed;
- benchmark methodology and comparator, when applicable;
- remaining limitations or unverified platforms.

By participating, you agree to follow the organization [Code of Conduct](CODE_OF_CONDUCT.md).

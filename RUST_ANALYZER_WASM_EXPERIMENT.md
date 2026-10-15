# RustLab rust-analyzer-wasm build experiment

This branch is isolated from `main`. It exists only to run a GitHub Actions build of the proposed single-thread adaptation of the archived `rust-analyzer-wasm` prototype.

Upstream source: https://github.com/rust-analyzer/rust-analyzer-wasm

The workflow checks out the upstream source into a temporary directory, applies `rust-analyzer-wasm-single-thread-experiment.patch`, and attempts the Wasm build. No deployment or publication is configured.

Important: this is an experiment, not a known-working build. The workflow logs are the source of truth for whether the legacy code can be made compatible.

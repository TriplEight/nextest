# cargo-nextest

Welcome to the home page for cargo-nextest, a next-generation test runner for Rust projects.

## Features

<img src="static/cover.png" style="float: right; width: 250px">

* **Clean, beautiful user interface.** nextest presents its results concisely so you can see which tests passed and failed at a glance.
* **[Up to 60% faster](book/benchmarks.md) than cargo test.** Nextest uses a [state-of-the-art execution model](book/how-it-works.md) for faster, more reliable test runs.
* **Detect flaky tests.** Nextest can [automatically retry](book/retries.md) failing tests for you, and if they pass later nextest will mark them as flaky.
* **Partition test runs across several CI jobs.** If your tests take too long to run in CI, nextest can automatically split them up for you across several jobs.
* **Cross-platform.** nextest works on Unix, Mac and Windows, so you get the benefits of faster test runs no matter what platform you use.
* ... and more [coming soon](https://github.com/nextest-rs/nextest/projects/1)!

## Quick start

Install cargo-nextest from crates.io (requires **Rust 1.54** or later):

```
cargo install cargo-nextest
```

Run all tests in a workspace:

```
cargo nextest run
```

For more detailed installation instructions, see [Installation and usage](book/installation.md).

## Crates

**cargo-nextest,** the main binary: [![cargo-nextest on crates.io](https://img.shields.io/crates/v/cargo-nextest)](https://crates.io/crates/cargo-nextest)

**nextest-runner,** core nextest logic:
[![nextest-runner on crates.io](https://img.shields.io/crates/v/nextest-runner)](https://crates.io/crates/nextest-runner)
[![Documentation (latest release)](https://img.shields.io/badge/docs-latest-brightgreen)](https://docs.rs/nextest-runner/) [![Documentation (main)](https://img.shields.io/badge/docs-main-purple)](rustdoc/nextest_runner/)

**nextest-metadata,** parsers for machine-readable output:
[![nextest-metadata on crates.io](https://img.shields.io/crates/v/nextest-metadata)](https://crates.io/crates/nextest-metadata)
[![Documentation (latest release)](https://img.shields.io/badge/docs-latest-brightgreen)](https://docs.rs/nextest-metadata/)
[![Documentation (main)](https://img.shields.io/badge/docs-main-purple)](rustdoc/nextest_metadata/)

## Contributing

The source code for nextest and this site are hosted on GitHub, at
[https://github.com/nextest-rs/nextest](https://github.com/nextest-rs/nextest).

Contributions are welcome! Please see the [CONTRIBUTING
file](https://github.com/nextest-rs/nextest/blob/main/CONTRIBUTING.md) for how to help out.

## License

The source code for nextest is licensed under the
[MIT](https://github.com/nextest-rs/nextest/blob/main/LICENSE-MIT) and [Apache
2.0](https://github.com/nextest-rs/nextest/blob/main/LICENSE-APACHE) licenses.

This document is licensed under [CC BY 4.0]. This means that you are welcome to share, adapt or
modify this material as long as you give appropriate credit.

[CC BY 4.0]: https://creativecommons.org/licenses/by/4.0/
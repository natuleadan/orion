# Natuleadan® Orion™

> A Rust SDK framework for writing APIs from reusable pieces.

## What it is

Orion is an SDK for composing APIs in Rust from mutable, reusable building blocks. APIs are defined in code, with no YAML-driven configuration.

## What it provides

It provides typed building blocks, code-first API definitions and a composable SDK surface. Configuration lives in Rust, so contracts are checked by the compiler rather than by a schema parser.

## Architecture

Building blocks compose one-way into higher-level APIs. Each piece is mutable and reusable, and the derive and CLI layers sit at the top of the graph.

## Repository layout

The workspace groups the library crate under `crates/`, documentation under `docs/` and validation entry points under `tools/`. All source lives in the development branch until release.

## Getting started

Clone `https://github.com/natuleadan/orion.git`. This branch holds only the
project baseline; the source code, build manifests and full validation suite
live in the `dev` branch. Switch to `dev` to build and run the project.

## Development

Work happens on short-lived branches merged into `dev`. Commits follow
`type(scope): description` with a body of at least three bullets; commitlint
enforces the policy locally and in CI. The `main` branch is protected and holds
only this minimal baseline until the first release.

## Status

Pending refactor of an earlier API framework repository; YAML is no longer used. The first published version will be 0.1.0.

## License

Apache-2.0. See [LICENSE](LICENSE).

## Trademark

Natuleadan® Orion™ is a trademark of Natuleadan. Other constellation
repositories: Pulsar, Aurora, Pleaides, Andromeda and Orion.

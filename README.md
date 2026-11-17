# Natuleadan® Orion™

> A Rust SDK framework for writing APIs from reusable pieces.

Orion is an SDK for composing APIs in Rust from mutable, reusable building blocks. APIs are defined in code, with no YAML-driven configuration.

## What it provides

- Code-first API definitions with no YAML configuration.
- Mutable, reusable building blocks.
- A typed, composable SDK surface.

## Layout

| Path | Purpose |
|---|---|
| `crates/orion/` | Library crate |
| `docs/` | Product documentation |
| `tools/` | Validation entry points |

## Development

Requires Rust 1.100 or newer and pnpm. Run the same checks locally that CI
runs before opening a pull request.

```sh
pnpm validate
```

## Documentation

- [Architecture](docs/ARCHITECTURE.md)
- [Contributing](CONTRIBUTING.md)

## License

Apache-2.0. See [LICENSE](LICENSE).

# ai3-lib

AI3 support library for PoT-O validator and miner components.

## Usage

```toml
[dependencies]
ai3-lib = "0.1"
```

Depends on `pot-o-core`. When used inside the pot-o-validator workspace, the workspace member is used automatically.

## Versioning

Releases follow semantic versioning. To publish:

1. Bump `version` in `Cargo.toml`.
2. Create a tag: `git tag v0.1.1 && git push origin v0.1.1`.
3. CI will publish to crates.io and GitHub Packages.

## License

MIT

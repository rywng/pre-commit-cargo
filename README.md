<!-- vim: set tw=80: -->

# pre-commit-cargo

This is my personal [pre-commit.com](https://pre-commit.com/index.html) hooks
for developing rust packages.

## Usage

Add the following to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/rywng/pre-commit-cargo
  rev: v0.1.0 # Use the ref you want to point at
  hooks:
    - id: cargo-test
  # - id: ...
```

Follow the [Official documentation](https://pre-commit.com/index.html#plugins)
for more information.

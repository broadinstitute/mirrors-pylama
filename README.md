# pylama mirror

Mirror of pylama package for pre-commit.

For pre-commit: see [https://github.com/pre-commit/pre-commit](https://github.com/pre-commit/pre-commit)

For pylama: see [https://github.com/klen/pylama](https://github.com/klen/pylama)

## Using pylama with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/broadinstitute/mirrors-pylama
  rev: v1.0.1
  hooks:
  - id: pylama
```

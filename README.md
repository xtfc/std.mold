A sort of "standard library" for use with [mold](https://github.com/xtfc/mold).

This is intended to be used as an included mold that simply provides a base set
of command types.

Example usage (YAML):

```yaml
includes:
  - url: "https://github.com/xtfc/std.mold"
```

(TOML):

```toml
[[includes]]
url = "https://github.com/xtfc/std.mold"
```

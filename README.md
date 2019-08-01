A sort of "standard library" for use with [mold](https://github.com/scizzorz/mold).

This is intended to be used as an included mold that simply provides a base set
of command types.

Example usage (YAML):

```yaml
includes:
  - url: "https://github.com/philipdexter/std.mold"
```

(TOML):

```toml
[[includes]]
url = "https://github.com/philipdexter/std.mold"
```

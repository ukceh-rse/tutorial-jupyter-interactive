# Tutorial notebook

For Binder to work, need to create a `requirements.txt`, which can be done from the lockfile using the (very long) command

```sh
uv export --no-emit-workspace --no-dev --no-annotate --no-header --no-hashes --output-file requirements.txt
```

Alternatively, just use `pip` and `pip-compile` or `pip freeze`.

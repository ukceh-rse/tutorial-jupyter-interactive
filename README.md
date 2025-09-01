> [!IMPORTANT]
> This was just a test to see whether Binder is worth the effort of having a separate repository for each tutorial, and conforming to its specs (e.g. no python 3.13, `requirements.txt` rather than `pyproject.toml`.)
> This repository opens in Binder, but for some reason it opens a VSCode session rather than Jupyter Lab. I have noobed somewhere.
>
> Anyway, it took a very long time to create a >1GB docker image for a really simple tutorial. I think it took long enough that our target audience won't both - it would be much faster for them to just download the tutorial and run it locally.
>
> Hence, I'm abandoning this repo, probably to be deleted or perhaps archived. Work is continuing at https://github.com/ukceh-rse/tutorials

# Tutorial notebook

For Binder to work, need to create a `requirements.txt`, which can be done from the lockfile using the (very long) command

```sh
uv export --no-emit-workspace --no-dev --no-annotate --no-header --no-hashes --output-file requirements.txt
```

Alternatively, just use `pip` and `pip-compile` or `pip freeze`.

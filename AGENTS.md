## Python

Python is available to you.

When executing python, **always use `uv`**. Never expect that the `python` or `python3` binaries will be available, but `uv` is available. Examples:

```bash
# run python
uv run python
# run script
uv run script.py
# install package
uv add matplotlib
```

Do not run python compile. To check python code, run `ruff check`.

## Zig

I am on the latest version of the Zig compiler. Be cautious to not use things that no longer work in the standard library.

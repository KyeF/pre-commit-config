<!-- START doctoc generated TOC please keep comment here to allow auto update -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [pre-commit-config](#pre-commit-config)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# pre-commit-config

[pre-commit](https://pre-commit.com/)

A sample pre-commit config.

Install via `pip`:

```bash
pip install pre-commit
```

Install git hooks via:

```bash
pre-commit install
```

This will now run whenever staged changes are committed.

pre-commit can be run manually via:

```bash
# all files
pre-commit run --all-files

# individual files
pre-commit run --files readme.md
```

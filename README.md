# Simple tox

A simple action to run tox like you would on your own machine.

---

## Inputs

**NOTE:** All inputs are optional.

### `python-version`

Python version in which to run tox. Defaults to `3.11`.

### `tox-env`

Tox environment to run. Defaults to none (a.k.a. "run all" in tox).

### `max-attempts`

Maximum number of attempts to run the command until it succeeds. Defaults to `1`.

### `timeout-minutes`

Maximum number of attempts to run the command until it succeeds. Defaults to `10`.

### `ignore-errors`

Whether to exit successfully even if the tox command fails or not. Defaults to `false`.

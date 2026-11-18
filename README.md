# opinion47ties-kit

Count lines, words and characters, with totals.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m opinion47ties_kit.cli --help
```

```python
from opinion47ties_kit.core import Opinion47tiesTool

tool = Opinion47tiesTool()
print(tool)
```

## Layout

```
opinion47ties_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 opinion47ties

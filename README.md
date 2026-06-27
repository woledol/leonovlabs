# Лабораторные работы по ООП

Леонов Алексей 466498

## Состав

- `lab1` — лабораторная работа 1.
- `lab2` — лабораторная работа 2.

## Проверка

```bash
cd lab1
python3 -m venv .venv
.venv/bin/pip install -e ".[dev]"
.venv/bin/python -m pytest
.venv/bin/ruff check .
```

```bash
cd lab2
python3 -m venv .venv
.venv/bin/pip install -e ".[dev]"
.venv/bin/python -m pytest
.venv/bin/ruff check .
```

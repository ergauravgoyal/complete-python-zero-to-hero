# Python Bootcamp – Notes & Guide

A reference guide for all concepts covered in this bootcamp. Add your own notes here as you learn.

---

## Numbers & Arithmetic

| Operator | Description | Example |
|----------|-------------|---------|
| `+` | Addition | `2 + 1` → 3 |
| `-` | Subtraction | `5 - 2` → 3 |
| `*` | Multiplication | `3 * 2` → 6 |
| `/` | Division (float) | `3 / 2` → 1.5 |
| `%` | Modulo (remainder) | `7 % 4` → 3, `20 % 3` → 2 |
| `**` | Exponentiation | `2 ** 3` → 8 |

**Note:** Floating-point precision can be tricky: `0.2 + 0.1 - 0.3` may not equal exactly 0 due to binary representation.

---

## Variables & Types

```python
my_dogs = 2
print(type(my_dogs))  # <class 'int'>

my_dogs = ["Sammy", "Frankie"]
print(type(my_dogs))  # <class 'list'>
```

Variables can be reassigned to different types. Use `type()` to check.

---

## Lists

Lists are ordered, mutable collections. Use square brackets `[]`.

```python
my_list = ["Sammy", "Frankie"]
my_list = [1, 2, 3]
```

### List Methods

| Method | Usage |
|--------|--------|
| `append(item)` | Add item to end |
| `insert(index, item)` | Insert at specific position |
| `extend(iterable)` | Add multiple items |
| `remove(item)` | Remove first occurrence |
| `pop(index)` | Remove and return item (default: last) |
| `clear()` | Remove all items |
| `index(item)` | Find first index |
| `count(item)` | Count occurrences |
| `sort()` | Sort in place (use `reverse=True` for descending) |
| `reverse()` | Reverse order in place |
| `copy()` | Create shallow copy |

---

## Strings

Strings use single `'` or double `"` quotes. Use `+` to concatenate. Convert numbers with `str()`:

```python
"$" + str(10.0)  # "$10.0"
```

### String Indexing & Slicing

- Indexing: `name[0]` (first), `name[-1]` (last)
- Slicing: `s[start:end:step]`

```python
s = "hello world"
s[:3]   # "hel" (first 3)
s[3:]   # "lo world" (from index 3 to end)
s[3:6]  # "lo " (index 3 to 5)
s[::]   # entire string
s[1:4]  # "ink" (from "tinker")
```

### String Methods

| Method | Example |
|--------|---------|
| `upper()` | `"hello".upper()` → "HELLO" |
| `lower()` | `"HELLO".lower()` → "hello" |
| `split(sep)` | `"a b c".split()` → `["a", "b", "c"]` |
| `split("o")` | Splits on delimiter |

### Escape Sequences

| Sequence | Meaning |
|----------|---------|
| `\n` | Newline |
| `\t` | Tab |

### String Length

```python
len("hello")  # 5
```

---

## Jupyter Tips

- **Reset variables:** Re-run the cell that defines the initial value, or use **Kernel → Restart Kernel**
- **Re-run all:** **Kernel → Restart & Run All** to clear state and run cells in order

---

## Your Notes

*Add your own notes below as you progress.*

---

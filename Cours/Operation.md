---

## Opérations

### Opérations arithmétiques

| Opérateur | Description | Exemple | Résultat |
|-----------|-------------|---------|----------|
| `+` | Addition | `5 + 3` | `8` |
| `-` | Soustraction | `10 - 4` | `6` |
| `*` | Multiplication | `3 * 7` | `21` |
| `/` | Division | `10 / 3` | `3.333...` |
| `//` | Division entière | `10 // 3` | `3` |
| `%` | Modulo (reste) | `10 % 3` | `1` |
| `**` | Puissance | `2 ** 8` | `256` |

```python
a = 10
b = 3

print(a + b)    # 13
print(a - b)    # 7
print(a * b)    # 30
print(a / b)    # 3.3333333333333335
print(a // b)   # 3
print(a % b)    # 1
print(a ** b)   # 1000
```

### Opérations d'assignation combinée

```python
x = 10
x += 5    # équivaut à x = x + 5  → x vaut 15
x -= 3    # équivaut à x = x - 3  → x vaut 12
x *= 2    # équivaut à x = x * 2  → x vaut 24
x //= 5   # équivaut à x = x // 5 → x vaut 4
```

---

## 2.6 La fonction `type()`

La fonction `type()` retourne le type d'une variable.

```python
x = 42
print(type(x))        # <class 'int'>

y = 3.14
print(type(y))        # <class 'float'>

z = "bonjour"
print(type(z))        # <class 'str'>

b = True
print(type(b))        # <class 'bool'>
```

---

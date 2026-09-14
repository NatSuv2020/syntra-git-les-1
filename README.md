# syntra-git-les-1

Hello from GitHub Editor

```python
def hello(name: str):
    print(f"Hello there {name}!")
```

| Boek                | Auteurs                               |
|---------------------|---------------------------------------|
| The DevOps Handbook | Gene Kim, Patrick Debois, John Willis |
| The Phoenix Project | Gene Kim, Kevin Behr, George Spafford |

# Werken met Strings in Python

Een **string** is een reeks tekens die je gebruikt om tekst op te slaan, zoals `"Hallo wereld"`. Strings zijn *onveranderlijk*: je past ze niet aan, je maakt een nieuwe.

## Een string aanmaken

1. Met enkele aanhalingstekens: `'tekst'`
2. Met dubbele aanhalingstekens: `"tekst"`
3. Met drie aanhalingstekens voor meerdere regels

## Veelgebruikte bewerkingen

- **Samenvoegen** met `+`
- Lengte opvragen met `len()`
- *Slicing* om een deel op te vragen

```python
naam = "Python"
print("Hallo, " + naam)
print(len(naam))

---
layout: post
title: "Benvenuto nel mio tech blog"
date: 2026-02-16
categories: blog
---

Benvenuto! Questo è il primo post del mio blog tecnico, costruito con Jekyll e ospitato su GitHub Pages.

## Perché un blog tecnico?

Scrivere è uno dei modi migliori per consolidare ciò che si impara. Questo blog sarà il mio spazio per:

- Documentare soluzioni a problemi tecnici
- Condividere tutorial e guide
- Tenere traccia dei progetti su cui lavoro

## Come è fatto questo sito

Il sito è costruito con **Jekyll**, un generatore di siti statici scritto in Ruby. Ecco un esempio di come si configura:

```yaml
# _config.yml
title: Tech Blog
theme: minima
plugins:
  - jekyll-feed
```

E un semplice esempio di codice Python:

```python
def fibonacci(n):
    if n <= 1:
        return n
    return fibonacci(n - 1) + fibonacci(n - 2)

# Primi 10 numeri di Fibonacci
for i in range(10):
    print(fibonacci(i))
```

Un esempio in JavaScript:

```javascript
const fetchData = async (url) => {
  try {
    const response = await fetch(url);
    const data = await response.json();
    return data;
  } catch (error) {
    console.error('Errore:', error);
  }
};
```

## Prossimi passi

Nei prossimi post esplorerò vari argomenti legati allo sviluppo software. Stay tuned!

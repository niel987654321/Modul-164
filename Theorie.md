### Generalisierung
Bei der Generalisierung verhindert man redundant. Wenn wir eine Tabelle mit Mitarbeiter und Kunden haben, dann kann es sein das die Mitarbeiter und Kunden die gleichen Namen haben. Somit hat man hier wieder eine Redundanz. Da ein Mitarbeiter aber noch eine Personalnummer hat und der Kunde nicht, kann man diese nicht sofort in eine Tabelle zussammenfassen. Dafür nutzt man jetzt die Generalisierung. Man macht eine neue Tabelle namens Personen und fügt da den Namen ein. Die anderen 2 Tabellen werden zu Zwischentabellen. Die Personalnummer wird noch bei der Zwischenbtalle hinzugefügt. Somit haben wir dann keine Redundanz mehr

### Identifying relationship vs. non-identifying relationship
Der grösste Unterschied ist, dass bei der identifying relationship kann der Frendschlüssel nicht geändert werden, bei der non-identifying relationship schon.

---
markmap:
  colorFreezeLevel: 2
---

# markmap

## Links

- <https://markmap.js.org/>
- [GitHub](https://github.com/gera2ld/markmap)

## Related Projects

- [coc-markmap](https://github.com/gera2ld/coc-markmap)
- [gatsby-remark-markmap](https://github.com/gera2ld/gatsby-remark-markmap)

## Features

- links
- **strong** ~~del~~ *italic* ==highlight==
- multiline
  text
- `inline code`
-
    ```js
    console.log('code block');
    ```
- Katex
  - $x = {-b \pm \sqrt{b^2-4ac} \over 2a}$
  - [More Katex Examples](#?d=gist:af76a4c245b302206b16aec503dbe07b:katex.md)
- Now we can wrap very very very very long text based on `maxWidth` option

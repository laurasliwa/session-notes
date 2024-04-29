flex grow, shrink, basis, align-self

# Flexbox

Flexbox ist ein umfangreiches CSS Tool um HTML Elemente gestalten. Vorallem wenn diese horizontal aneinander gereiht werden sollen. Ein Container Element oder Parent Element muss definiert werden. Dieses Element enthält mehrere (Child) Elemente, dessen Position von den Flexbox Regeln beeinflusst werden. Flexbox wird wie folgt definiert:

```
.container-element {
    display: flex;
}
```

Flexbox tut folgende Dinge:

- Alle Child Elemente werden nebeneinander angezeigt entlang der Hauptaxe (main axis), die Horizentale standardmäßig. Die senkrechte Axe wird cross axis genannt.
- Wenn die Weite der Child Elemente über die Container Weite geht, wird das Child Element so weit verkleinert, sodass in den Container passt.

Dieses Verhalten kann modifiziert werden.

## Wichtige Flex Eigenschaften (Properties)

| property                                                                            | effect                                                                                                                                                         |
| ----------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [justify-content](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content) | Definiert das Positionieren der Elemente entlang der main axis. Nützliche Werte (values): `flex-start`, `flex-end`, `center` , `space-between`, `space-evenly` |
| [align-items](https://developer.mozilla.org/en-US/docs/Web/CSS/align-items)         | Definiert die Positionierung der Elemente entlang der cross axis. Nützliche values: `flex-start`, `flex-end`, `center`                                         |
| [gap](https://developer.mozilla.org/en-US/docs/Web/CSS/gap)                         | Definiert den Leerraum zwischen den Elementen.                                                                                                                 |
| [flex-direction](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-direction)   | Legt die Richtung der main axis fest. Nützliche values: `row`, `column`                                                                                        |
| [flex-wrap](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-wrap)             | Modifizierung, sodass ein Element in die nächste Reihe rutscht, statt alle Elemente auf eine Reihe zu quetschen. Nützliche values: `wrap`, `no-wrap`           |

Hier ist ein deitailliertes [cheatsheet](https://css-tricks.com/snippets/css/a-guide-to-flexbox/).

## Flex-direction

Mit dieser Eigenschaft lässt sich definieren welche Axe als main axis fungiert. In folgendem Bild ist der Effekt genauer zu sehen:

![flex-direction](../../Protokol/hh-web-24-3/sessions/css-flexbox/assets/flex-direction.png)

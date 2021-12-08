## border (e outline: borda por fora da borda)

As bordas da caixa

- Value: `<border-style>` | `<border-width>`| `<border-color>`
    - style: solid , dotted, bashed, double, groove, ridge, inset, outset
    - width: `<length>`
    - color: `<color>`

obs: box-sizing: border-box; 
(responsavel por fazer a caixa ter o tamanho informado e não somar com a borda)

```css
div {
    /* shorthand */
    border-top: solid 2px; /* top, right, bottom, left */

    /* style */
    border: solid;

    /* width <length> , style */
    border: 2px dotted;

    /* style, color */
    border: outset #f33;

    /* width, style, color */
    border: medium dashed green;
}
```

EXEMPLO:

<div> elemento </div>

```css
div {
  width: 100px;
  height: 100px;
  margin: 20% auto;
  
  border: 10px solid purple;
  border-top: 5px dotted black;
  border-bottom: 5px dotted black;
  
  outline: 6px solid red;
}
}
```
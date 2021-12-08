## Box sizing

Como sera calculado o tamanho total da caixa?

- content-box|border-box

```css
div {
    box-sizing: border-box;
}
```

EXEMPLO:

```html
<div>
  <strong>CSS</strong> é incrivel!
</div>
```

```css
div {
  width: 100px;
  height: 100px;
  border: 1px solid red;
  margin: 10%;
  padding: 0 20px;
  box-sizing: border-box;
}
```
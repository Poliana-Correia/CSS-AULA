# Justify-content

* Alinhamento dos elementos dentro do container
* Distribuição dos elementos

## Valores

- flex-start    (por padrão, todos no inicio )
- flex-end      (todos no fim)
- center        (alinhados ao centro)
- space-around  (espaço por igual ao redor)
- space-between (espaço entre eles)
- space-evenly  (espaço constante, do inicio ao fim espaços iguais)

```html
<div class="box">
  <div>A</div>
  <div>B</div>
  <div>C</div>
  <div>D</div>
</div>
```

```css
.box {
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  border: 1px dashed red;
  height: 150px;
}

.box div {
  border: 1px solid;
}
```
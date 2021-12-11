## Flexbox

* nos permite posicionar os elementos dentro da caixa.
* controle em uma dimensão (horizontal ou vertical)
* alinhamento, direcionamento, ordenar e tamanhos

```css
div.parent {
    display: flex;
}
```

## flex-direction 

* Qual a direção do flex: horizontal ou vertical
* row, column

## alinhamento

* justify-content
* align-items

EXEMPLO:

```html
<div class="container">
  <div class="box1 box"></div>
  <div class="box2 box"></div>
  <div class="box3 box"></div>
</div>
```

```css
body {
  height: 100vh;
  margin: 0;
  display: flex;
  align-items: center;
}

.container {
  width: 100vw;
  display: flex;
  justify-content: center;
}

.box {
  width: 80px;
  height: 80px;
}
.box1 {
  background-color: red;
}
.box2 {
  background-color: green;
}

.box3 {
  background-color: blue;
}
```
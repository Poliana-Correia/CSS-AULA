# Propriedades do flex container

* Direção dos itens
    - flex é uma dimensão (horizontal ou vertical)
    - podemos mudar a direção com `flex-direction`
    - valores: (row, row-reverse, column, column-reverse)

* Multi linhas 
* Alinhamento
    - principal 
    - cruzado
* Espaços entre itens

## flex-wrap

* Podemos usar multi linhas.
* Cada nova linha, um novo flex container

```html
<div class="box">
  <div class="item">A</div>
  <div class="item">B</div>
  <div class="item">C</div>
  <div class="item">D</div>
</div>
```

```css
.box {
  display: flex;
  flex-wrap: wrap;  /* joga os elementos pra baixo para que possa caber na tela quando diminuida */
  border: 1px dashed red;
}

.box div {
  border: 1px solid;
  width: 80px;
}
```


## Flex-flow

* shorthand
* flex-direction  ||  flex-wrap

```css
.box {
  display: flex;
  flex-flow: column wrap;
  border: 1px dashed red;
}
```
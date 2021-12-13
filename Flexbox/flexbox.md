## Flexbox

A caixa se torna flex, fazendo com que os elementos internos 
possam receber melhor:

- Alinhamento
- Ordenação
- Tamanhos flexiveis

```html
<div class="flexbox">
  <div class="item">A</div>
  <div class="item">B</div> 
  <div class="item">C</div> 
</div>
```

```css
.flexbox {
  display: flex;
  justify-content: space-around; /*alinhados ao centro com espaços entre eles*/
  flex-direction: column; /*volta para coluna*/
}

.item:nth-child(1) {
  order: 1;           /* reordenando os itens */
}
```
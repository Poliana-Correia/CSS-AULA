# Propriedades para os itens

- flex-basis

```css
.box {
  display: flex;
  border: 1px dashed red;
}

.box div {
  border: 1px solid;
  flex-basis: auto;
}

.box div:nth-child(1) {
  width: 2500px;          /*mantem apenas o 1 elemento no icicio e afasta o restante */
}
```

                            ------------


- flex-grow  (item crescendo)
    O crescimento do item dentro do container
    em relação aos espaços vazios.

```css

.box div:nth-child(2),
.box div:nth-child(3){
  flex-grow: 1;        /*seleciona o elemento que queremos que ocupe o espaço vazio, podendo ser                            mais de 1 separados por virgula. */
}

.box div:nth-child(1) {
  flex-grow: 2;           /* elemento 1 ocupando duas frações do epaço vazio */
}
```

                            -----------------------


- flex-shrink
    Capacidade de encolher o item dentro do container.

```css
.box {
  display: flex;
  flex-direction: column;   /* usando um exemplo com eixo de coluna ,entao usamos altura e não largura como em linhas */
  border: 1px dashed red;
  height: 180px;
}

.box div {
  border: 1px solid;
  flex-basis: 80px;
  
}

.box div:nth-child(2),
.box div:nth-child(3) {
     flex-shrink: 0;
}
```


                            -----------------------


- flex
    shorthand 
    flex-grow flex-shirnk flex-basis
    podem ter 1, 2 ou 3 valores


```html
<div class="page">
  <aside>Aside</aside>
  <main>
    Main
    <section>Content 1</section>
    <section>Content 2</section>
    <section>Content 3</section>
  </main>
</div>
```

```css
* {
  margin: 0
}

.page {
  border: 2px solid;
  min-height: 100vh;
  display:flex;
  
}

aside {
  background: lightgreen;
  flex: 1;  /* o aside ocupando 1/3 do espaço da tela */
}

main {
  background: lightgoldenrodyellow;
  flex: 2; /* o main ocupando 2/3 do espaço da tela */
    
    display: flex; 
  flex-direction: column;  /*colocando um abaixo do outro*/
}

main section:nth-child(1) {
  background: lightsalmon;
  flex: 2;  /* 2 partes da tela para o conteudo 1 */
}

main section:nth-child(2){
  background: lightblue;
  flex: 1  /* uma parte da tela pro cont 2 */
}

main section:nth-child(3) {
  background: lightpink;
  flex: 1  /* uma parte da tela pro cont 3 */
}
```

                    ---------------------------


- order
    Serve para ordenar elementos dentro de uma caixa

```html
<div class="box">
  <div>A</div>
  <div>B</div>
  <div>C</div>
  <div>D</div>
</div>
```


```css
* {
  margin: 0
}

.box {
  display: flex;
  border: 1px dashed red;
}

.box div {
  border: 1px solid;
}

.box div:nth-child(1) {
  order: 1;
}

.box div:nth-child(2){
  order: 3;
}

.box div:nth-child(3){
  order: 1;
}

.box div:nth-child(4){
  order: -1;
}
```

## Faça um layout com duas colunas e com espaço de 1rem entre elas

```html
<header>
 <strong>Layout com 2 colunas</strong>  
</header>
<main>
  <div class="box1 box"> coluna 1</div>
  <div class="box2 box"> Coluna 2</div>
</main>
```

```css
.box {
  height:600px;
}

.box1 {
  background-color: lightpink;
  flex: 25%;
}
    
.box2 {
  background-color: lightgreen;
  flex: 75%;
}

main {
  display: flex;
  gap: 1rem;
  margin: 1rem;
  margin-top: 3rem;
}
```
# Grid

* Assim como o flex ele faz esse posicionamento dos elementos dentro da caixa
* Posicionamento horizontal e vertical ao mesmo tempo
* Pode ser flexivel ou fixo
* Cria espaços para os elementos filhos habitarem

EXEMPLO:

```html

<body>
  <header>
    <div>Logo</div>
    <div>Menu</div>
  </header>
  <main>Conteudo</main>
  <aside>Infos adicionais</aside>
  <footer>Rodpé</footer>
</body>
```

```css

body {
  margin: 0;
  height: 100vh;
  
  display: grid;
  grid-template-areas:
    "header header"
    "main aside"
    "footer footer";
  
  grid-template-rows: 80px 1fr 40px;
  grid-template-columns: 1fr 150px;
}

header {
  grid-area: header;
  background-color: green;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 30px;
}

main {
  grid-area: main;
  background-color: pink;
}

aside {
  grid-area: aside;
  background-color: blue
}

footer {
  grid-area: footer;
  background-color: gray;
}
```
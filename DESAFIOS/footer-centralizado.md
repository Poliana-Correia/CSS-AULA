## Crie um footer com data de criação do site alinhado ao centro

```html
<footer>
  14 de Dezembro de 2021
</footer>
```

```css
* {margin: 0;}

body {
  min-height: 100vh;
  display: flex;
}

footer {
  color: white;
  background: grey;
  margin-top: auto;
  height: 5rem;
  flex: 1;
  display: flex;
  align-items: center;
  justify-content: center;
}
```
## Crie um botão contendo uma imagem dentro

```html
<nav>
  <button>
  <img src="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/PjxzdmcgaGVpZ2h0PSI0OCIgdmlld0JveD0iMCAwIDQ4IDQ4IiB3aWR0aD0iNDgiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHBhdGggZD0iTTAgMGg0OHY0OEgweiIgZmlsbD0ibm9uZSIvPjxwYXRoIGQ9Ik0yMCAzM2wxMi05LTEyLTl2MTh6bTQtMjlDMTIuOTUgNCA0IDEyLjk1IDQgMjRzOC45NSAyMCAyMCAyMCAyMC04Ljk1IDIwLTIwUzM1LjA1IDQgMjQgNHptMCAzNmMtOC44MiAwLTE2LTcuMTgtMTYtMTZTMTUuMTggOCAyNCA4czE2IDcuMTggMTYgMTYtNy4xOCAxNi0xNiAxNnoiLz48L3N2Zz4=" alt="">
  Visualizar
</button>
<button>
  <img src="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/PjxzdmcgZmlsbD0ibm9uZSIgaGVpZ2h0PSIyNCIgc3Ryb2tlPSJjdXJyZW50Q29sb3IiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgc3Ryb2tlLXdpZHRoPSIyIiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48Y2lyY2xlIGN4PSI5IiBjeT0iMjEiIHI9IjEiLz48Y2lyY2xlIGN4PSIyMCIgY3k9IjIxIiByPSIxIi8+PHBhdGggZD0iTTEgMWg0bDIuNjggMTMuMzlhMiAyIDAgMCAwIDIgMS42MWg5LjcyYTIgMiAwIDAgMCAyLTEuNjFMMjMgNkg2Ii8+PC9zdmc+" alt="">
  Adicionar
</button>
</nav>
```

```css
nav {
  display: flex;
  gap: 1rem
}

button {
  display: flex;
  align-items: center;
  line-height: 0;
  gap: .4rem;
  margin-bottom: 2rem;
}

button img {
  width: 2rem;
  height: 2rem;
}
```
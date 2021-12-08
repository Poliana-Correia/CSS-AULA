## display: block vs display: inline

- como as caixas se comportam em relação as outras caixas
- comportamento externo das caixas

**block**                            **inline**
- ocupa toda a linha, colocando      - elemento ao lado do outro
o proximo elemento abaixo desse.     - width e height não funcionam
- width e height sao respeitados     - somente valores horizontais de 
- paddind, margin, border irão       margin, padding e border
funcionar normalmente.


EXEMPLOS
block: `<p> <div> <section>`, todos os headings `<h1><h2>...`
inline: `<a> <strong> <span> <em>`

```html
<div>
  block
</div>

<span>inline</span>
```

```css
div {
  height: 100px;
  border: 1px solid red;
  width: 10px;
  display: inline
}

span {
  height: 100px;
  border: 1px solid green;
  width: 10px;
  display: block;
}
```
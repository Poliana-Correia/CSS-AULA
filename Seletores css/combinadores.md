# Combinators

* Combinadores, pois eles trabalham para buscar e combinar seletores
a fim de aplicar uma estlização.

## Descendant combinator

* identificado por um espaço entre os seletores
* busca um elemento dentro de outro

```html

(achar dentro do body depois dentro do article depois dentro do h2 
e colocar o texto vermelho)

<body>
  <article>
    <h2>Um titulo</h2>
  </article>
  
  <article>
    <h2>outro titulo</h2>
  </article>
</body>

```

```css

body article h2 {
  color: red;
}

```

### Child combinator

* identificado pelo sinal `>` entre dois seletores
* seleciona somente o elemento que é filho direto do pai
* elementos depois do filho direto serão considerados

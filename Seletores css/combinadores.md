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

## Child combinator

* identificado pelo sinal `>` entre dois seletores
* seleciona somente o elemento que é filho direto do pai
* elementos depois do filho direto serão considerados

EXEMPLO:
```css
body > ul > li {  /*bucando elemntos que [e filho direto do pai*/
  color: blue;
}

ul > ul > li {    /*buscando o segundo ul para aplicar a propriedade*/
  color: blue;
}
```

## Adjacent sibling combinator
* Identificado pelo sinal `+` entre dois seletores
* Seleciona somente o elemento do lado direto que é irmão direto na hierarquia

```css
h1 + p {
  color: red;
}

button + button {
  margin-left: 32px;
}
```

## General sibling combinator
* Identificado pelo sinal `~` entre dois seletores
* Seleciona todos os elementos irmãos

```css
h1 ~ p
```

## Utilizando combinadores

```css
ul > li[class="red"]
```

* Dica:
      * seletores muito especificos tendem a causar dificuldades no reuso 
  das regras de estilização dos elementos
      * muitas vezes, um simples uso de classes, torna o trabalho muito mais eficiente (.red)
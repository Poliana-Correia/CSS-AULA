# Seletores
Conecta um elemento HTML com o CSS  a fim de alterar o elemento.

## Tipos
* Element selector
    todos os elementos HTMML
* ID selector
    um elemento que tenha um atributo `id`.
    cada id devera ser unico.
* Class selector
    os elementos que contenha um atributo `class`
    podemos ter uma ou mais classes
* Attribute selector
    um elemento que tenha um atributo especifico
* Pseudo-class selector
    elementos em um estado especifico 


### Múltiplos
Voce podera selecionar multilpos elementos e aplicar alguma regra css
para todos eles.

Usamos uma separação por virgulas para isso.
```css
h1, p, a {
    color: red;
}
```


 EXEMPLO 


```html

HTML
<h1 id="title" class="red big" title="algum titulo">Titulo da pagina</h1>
<p title="black" id="content" class="red">Conteudo da minha pagina</p>
```

```css

CSS
h1 {
  color: blue;
  font-size: 60px;   (ELEMENT SELECTOR)
} 

p {
  color: green;      (ELEMENT SELECTOR)
}

#content {
  color: purple;     (ID SELECTOR)
}

#title {
  color: pink;       (ID SELECTOR)
}

.red {
  color: red;        (CLASS SELECTOR)
}

.big {
  font-size: 3em;    (CLASS SELECTOR)
}

[title] {
  color: blck;       (ATTRIBUTE SELECTOR)
}

p:hover {
  color: red;
}
                    (PSEUDO-CLASS SELECTOR)
h1:hover {
  color: red;
}

p:hover, h1:hover {
  color: red;           (MULTIPLOS)
}
```
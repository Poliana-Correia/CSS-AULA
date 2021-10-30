# A cascat (cascading)

A escolha do browser de qual regra aplicar, caso haja muitas regras para o mesmo elemento.
*Seu estilo é lido de cima para baixo.

É levado em consideração 3 fatores:
1. Origem do estilo
2. Especificidade
3. Importancia

### Origem do estilo
inline > tag style > tag link

### Especificidade
É um calculo matemático, onde. cada tipode seletor e origem do estilo, possuem valores a serem considerados.

0. Universal selector, combinators e negation pseudo-class (:not())
1. Element type selector e pseudo-elements (::before, ::after)
10. Classes e attribute selectors ([type="radio])
100. ID selector
1000. Inline

### A regra !important

* Cuidado, evite o uso
* não é considerado uma boa prática
* quebra o fluxo natural da cascata 

# At-rules

*Esta relacionado ao comportamento do CSS 
*Começa com o sinal de `@` seguido do identificador e valor

## Exemplos comuns
-@import      /* incluir um CSS externo */
-@media       /* regras condicionais para dispositivos */
-@font-face   /* fontes externas */
-@keyframes   /* Animation */

```css
@import url("http://local.com/style.css");

@media (min-width: 500px) {
    /* rules here */
}

@font-face {
    /* rules here */
}

@keyframes nameofanimation {
    /* rules here */
}

```

# Shorthand
*junção de propriedades
*resumido
*legivel

```css
{
    /* backgrouns proprerties */
    backgrouns-color: #000;
    background-image: url(images/bg.gif):
    backgrouns-repeat: no-repeat;
    backgrouns-position: left top;

    /* background shorthand */
    background: #000 url(imagens/bg.gif) no-repeat left top;

    /* font properties */
    font-style: italic;
    font-weight: bold;
    font-size: .8em;
    line-height: 1.2;
    font-family: Arial, sans-serif;
    

}

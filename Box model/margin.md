## Margin

Espaços entre os elementos

- margin-top    (superior)  
  margin-right  (direita)
  margin-bottom (inferior)
  margin-left   (esquerda)

- values: `<length>` |  `<percentage` | auto

```css
div {
    /* shorthand (forma abreviada) */
    margin: 12px 16px 10px 4px;
    margin: 12px 16px 0;
    margin: 8px 16 px;
    margin: 8px;
}
```

    **cuidado com margin collapsing (top se ajunta ao bottom)**

```html
<div>
 Margin
</div>
<section> elemento abaixo </section>
```


```css
* { ,argin: 0;}

div, section {
  border: 1px solid red;
  width: 100px;
  height: 100px;
}

div {
  margin-bottom: 8px;
}
                         /* essas duas colapsando, pega um ou outro */
section {
  margin-top: 8px;
}
```
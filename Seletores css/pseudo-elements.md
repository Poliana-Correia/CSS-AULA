# Pseudo-elements
Com pseudo-elements nós podemos adicionar elementos 
HTML pelo próprio css

`::pseudo-element-name`

## Exemplos

* ::before
* ::after
* ::first-line

```html
<li>Gratidao</li>
<li>Esperença</li>
<li>Liberdade</li>
<li>Confiança</li>
```

```css
li {
  position: relative;
}
li::after {
  content: "";
  width: 10px;
  height: 1px;
  background-color: blue;
  position: absolute;
  bottom: 0px;
}
```
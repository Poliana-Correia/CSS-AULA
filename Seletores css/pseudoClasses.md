# Pseudo-classes

É um tipo de seletor que irá selecionar um elemento que 
estiver em um estado especifico.
Ex: é o primeiro elemento dentro de uma caixa, ou, o
elemento está com o ponteiro dou mouse para cima dele.

Pseudo-classes começam com 2 pontos seguido do nome da 
pseudo class 
`:pseudo-class-name`

## Selecionando elementos com pseudo-classes

* :first-child

```html
<ul>
  <h2>Palavras bonitas</h2>
  <li>gratidao</li>
  <li>esperança</li>
  <li>fé</li>
</ul>
```
```css
ul h2:first-child {
  font-weight: bold;
  color: green;
}
```


* :nth-of-type()

```html
<article>
  <h1>Gratidão</h1>
  <p>idfjbweksjbvisdvsjkdvsk</p>
  <p>b~dçfmbçdmgbçdfbdgb,dflbn flv</p>
  <p>fgjbshwlnrowirgbwlejfoweflkefk</p>
</article>
```
```css
article p:nth-of-type(3) {
  font-weight: bold;
  font-size: 18px;
}
```


* :nth-child()

```html
<article>
  <h1>Gratidão</h1>
  <p>idfjbweksjbvisdvsjkdvsk</p>
  <p>b~dçfmbçdmgbçdfbdgb,dflbn flv</p>
  <p>fgjbshwlnrowirgbwlejfoweflkefk</p>
</article>
```
```css
article p:nth-child(2) {
  font-weight: bold;
  font-size: 18px;
}
```

* nth-child odd e even

```html
<ul>
    <li>Esperança</li>
    <li>fe</li>
    <li>liberdade</li>
    <li>gratidao</li>
    <li>Esperança</li>
    <li>fe</li>
    <li>liberdade</li>
    <li>gratidao</li>
</ul>
```
```css
ul li:nth-child(odd){
    color: black;
    background: #eee;
}
ul li:nth-child(even){
    color: gray;
```


 

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
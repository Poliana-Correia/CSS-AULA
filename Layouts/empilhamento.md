## Element stacking

* Empilhamento de elementos : z-index

utilizamos o z-indez para decidir qual elemento 
ira ficar em qual posição do empilhamento.

EXEMPLO:

```html
<div class="box1 box"></div>
<div class="box2 box"></div>
<div class="box3 box"></div>
```

```css
.box {
  width: 80px;
  height: 80px;
  margin-bottom: 8px;
}
.box1 {
  background-color: red;
  position: absolute;
  left: 8px;
  top: 8px;
  z-index: 3;
}
.box2 {
  background-color: green;
  position: absolute;
  left: 15px;
  top: 15px;
  z-index: 4;
}

.box3 {
  background-color: blue;
  position: absolute;
  left: 23px;
  top: 23px;
}
```

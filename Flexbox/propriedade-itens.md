# Propriedades para os itens

- flex-basis

```css
.box {
  display: flex;
  border: 1px dashed red;
}

.box div {
  border: 1px solid;
  flex-basis: auto;
}

.box div:nth-child(1) {
  width: 2500px;          /*mantem apenas o 1 elemento no icicio e afasta o restante */
}
```

                            ------------


- flex-grow  (item crescendo)
    O crescimento do item dentro do container
    em relação aos espaços vazios.

```css

.box div:nth-child(2),
.box div:nth-child(3){
  flex-grow: 1;        /*seleciona o elemento que queremos que ocupe o espaço vazio, podendo ser                            mais de 1 separados por virgula. */
}

.box div:nth-child(1) {
  flex-grow: 2;           /* elemento 1 ocupando duas frações do epaço vazio */
}
```

                            ------------


- flex-shrink
    Capacidade de encolher o item dentro do container.

```css
.box {
  display: flex;
  flex-direction: column;   /* usando um exemplo com eixo de coluna ,entao usamos altura e não largura como em linhas */
  border: 1px dashed red;
  height: 180px;
}

.box div {
  border: 1px solid;
  flex-basis: 80px;
  
}

.box div:nth-child(2),
.box div:nth-child(3) {
     flex-shrink: 0;
}
```


                            ------------


- flex






- order
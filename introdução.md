# Cometários 

Comentários começam com /* e terminam com */.

# Anatomia

```css
h1 {
    color: blue;         /* cor da letra*/
    font-size: 60px;     /* tamanho da fonte */
    background: gray;    /* cor do fundo */ 
}
```

*selector         
*declaration
*properties
*property value

# Selectors

Os seletores conectam um elemento HTML com o CSS

## Tipos

*Global selector `*`
*Element/Type selector `h1, h2, p, div`
*Id Selector `#box, #container`
*Class Selector `.red, .m-4`
*Attrbute selector, Pseudo-class, Pseudo-element e outros.

```css

/*código HTML usado para o exemplo abaixo*/ <div id="conteiner" class="m-40"><h1>Título</h1></div> 

* {
  margin: 0;   /* selector global */  
}

#container {
  width: 200px;    /* largura da caixa */  
}

.m-40 {
  margin: 40px;  /* margem da caixa */  
}


h1 {
  color: blue;
  font-size: 60px;
  background: gray;
}
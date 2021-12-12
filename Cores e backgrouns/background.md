# Background

## Seus atributos:

```html
<header> 
  
</header>
<main> 
  <h1> Evolua rapido com TI</h1>
  <p> Junte-se a milhares de devs e acelere na direção dos seus objetivos.</p>
</main>
```

```css
* {margin: 0;}
  
h1 {
  background-color: purple;
  width: 310px;
  margin-top: 50px;
  margin-left: 300px;
  margin-bottom: 50px;
}

p {
  margin-left: 250px;
}

header {
  border: 7px dashed purple; /* boda pontilhada */
  height: 260px;
  padding: 16px; /* preenchimento ocupado */
  
  background-color: black;
  background-image: url(https://png.pngtree.com/thumb_back/fh260/background/20200714/pngtree-modern-double-color-futuristic-neon-background-image_351866.jpg); 
  background-repeat: no-repeat; /* não repetir imagem */
  background-position: center; 
  background-size: contain; /* cover, 50% , 3em , 3px */
  background-origin: border-box; /*imgem iniciando desde o inicio da borda (content-box, padding-box ) */
  background-clip: content-box;
}


## OUTRO EXEMPLO:

* {margin: 0;}
  
h1 {
  color: pink;
  width: 310px;
  margin-top: 50px;
  margin-left: 300px;
  margin-bottom: 20px;
}

p {
  font-size: 30px;
  color: pink;
  margin-left: 120px;
}

/* colocar tudo dentro de main para o texto ficar dentro da imagem */

main {
  background-color: black;
  background-image: url(https://png.pngtree.com/thumb_back/fh260/background/20200714/pngtree-modern-double-color-futuristic-neon-background-image_351866.jpg);
  background-repeat: no-repeat;
  background-position: center;
  background-size: contain; /* cover, 50% , 3em , 3px */
  background-origin: border-box; /*imgem iniciando desde o inicio da borda (content-box, padding-box ) */
  background-clip: content-box;
  background-attachment: fixed; /* a imagem não movimento ao descer a tela (scroll) */
  background: linear-gradient(purple, blue) /*cores intercaladas, pode usar mais de 2 cores*/
  /*temos tambem o radial-gradient que trabalha com as cores de uma maneira circular */
}
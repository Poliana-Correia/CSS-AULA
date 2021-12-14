
## Faça um menu navegação


```html
<h1>Menu navegation</h1>
<header>
  <nav>    
    <a href="#">LOGO</a>
    <ul>
      <li>HOME</li>
      <li>ABOUT</li>
      <li>SERVICES</li>
      <li>TESTIMONIALS</li>
      <li>CONTACT</li>
    </ul>
  </nav>
</header>
```

```css
* {
  margin: 0;
}

header {
  padding: 2rem;
  background: white;
}

body {
  background: lightgray;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  
}

ul {
  display: flex;
  list-style: none; /* tirando as bolinhas de lista */
  align-items: center;
  gap: .8rem;
}

ul li:last-child {
  background: blue;
  color: white;
  padding: .8rem;
}
```
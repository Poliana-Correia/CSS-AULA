# Trabalhando com fontes 
Tipografia transmite mensagem

- negrito
- tamanho
- estilo

## basic font properties

* font-family
* font-weight
* font-style
* font-size

## font family

* Tipo de fonte de um elemento
* Lista de fontes e ordem de propriedade
* Inclui *fallback* font

```css
p {
    font-family: "Times New Roman", Times, serif;
}
```

- serif  (fonte que tem as dobrinhas em baixo)
- sans   (sem a dobrinha)

## font weight

* Peso da fonte

```css
p {
    font-weight: bold;
}
```

## font style

* O estilo da fonte

```css
span {
    font-style: italic;
}
```

## font size

* Tamanho da fonte

```css
p {
    font-size: 18px;
}
```


## web fonts

- fontes do sistema x fontes da web
- como usar fontes para web

    * @font-face
    * @import
    * link
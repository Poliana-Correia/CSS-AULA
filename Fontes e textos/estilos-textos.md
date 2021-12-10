# Atribuir mais estilos aos textos

## font-variant

* variações na apresentação fonte

```css
p {
    font-variant: small-caps;
}
``` 
É como se todas as letras ficassem maísculas
porem com um tamanho menor



## font-stretch

* alargamento ou encolhimento da fonte
* aceita palavra-chaves como: expanded, condensed, normal
* aceita porcentagens de 50% a 200%

```css
p {
    font-stretch: expanded;
}
```



## letter-spacing

* espaços entre caracteres (letras)

```css
p {
    letter-spacing: 4px;
}
```



## word-spacing

* espaços entre as palavras

```css
p {
    word-spacing: 4px;
}
```


## line-height

* espaços entre linhas
* pode ser com unidades ou sem unidades de medida
* comuns: 1.5 ou 2

```css
p {
    line-height: 1.6;
}
```


## text-transform

* transformação do texto (todas as letras maiusculas ou minisculas)

```css
p {
    text-transform: uppercase; /* capitalize, lowercase, none */
}
```


## text-decoration

* aparencia decorativa de um texto
* line: underline(linha abaixo), overline(linha acima), line-through(linha no meio do texto)
    -podemos aplicar mais de um valor
* style: wavy, dotted, double, dashed, solid (tipos de estilo para a linha)
* color: `<color>` values (cor da linha)

```css
p {
    text-decoration: underline; /*shorthand */
}
```

## text-align

* alinhamento de um texto
- center, right, justify

```css 
p {
    text-align: center; /* left, right, center, justify */
}
```

## text-shadoow

* sombra aplicada a um texto
* permite multiplos valores ou podemos deixar um apenas.

```css
p {
    text-shadow: 1px 1px 1px red,
                2px, 2px 1px green; /* offset-x, offset-y, blur-radius, color */
}
```


## shorthand

* font-style, font-variant, font-weight, font-stretch, font-size, 
line-height e font-family.

```css
p {
    /* -style, -variant, -weight, -size, line-height e -family. */
    font: italic normal bold normal 3em/1.5 helvetica, Arial, sans-serif;
}
```


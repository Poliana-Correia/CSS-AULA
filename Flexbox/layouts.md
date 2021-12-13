# Layouts e evolução

Layout te a ver com a maneira que os elementos estão distribuidos na tela

## Normal flow

Ou Flow Layout é a maneira que os elementos `block`(quebra linha) e `inline`(na mesma linha) ficam na página

```html
<p> texto block com <strong> inline </strong> dentro </p>
```


## Tables 

É a maneira de tabelas onde a tag `table` recebe um display `table` 
fazendo com que os elementos internos como `td` e `tr` possam
ser usados para montar uma tabela.

```html
<table>
  <tr>
    <td> hora </td>
    <td> 20:00 </td>
  </tr>
  <tr>
    <td> hora </td>
    <td> 20:00 </td>
  </tr>
  <tr>
    <td> hora </td>
    <td> 20:00 </td>
    <td> 20:50 </td>
  </tr>
  ```

  ## Tabless

  Uso das propriedades `float`, `clear` para os elementos possam 
  mudar de posição na tela.

  ```html
  <div style="float: left">
        esquerda
  </div>

  <div style="float: right">
       direita
  </div>

  <div style="clear: both">
        normal
  </div>
  ```
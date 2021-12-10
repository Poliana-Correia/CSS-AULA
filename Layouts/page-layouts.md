# page layouts

- tables
- floats e clear
- Frameworks e Grid Systems
- Flexbox
- Grid

## posicionamentos

Controlar onde, na pagina, o elemento irá ficar, alterando o fluxo normal dos elementos.

- Name: position
- Value: static, relative, absolute, fixed
    * static: segue o padrão normal ficando um abaixo do outro
    * relative: alteramos a posição com = top, right, bottom, left, z-index
    * absolute: ocupa um posicionamento em outra camada acima dos demais, sera sempre em relação a pagina ou do pai dele, tbm temos as formas de dimensionar a posição com top, right, bottom, left, z-index
    * fixed: O elemento fica fixo na pagina, mesmo que rolamos a barra o elemento com posicionamnto fixo se mantem visualizado, e podemos alterar seu posicionamento com as propriedades top, right, bottom, left, z-index.

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
    position: fixed;
    left: 0px;
    top: 0px;
    }
    
    .box2 {
    background-color: green;
    }

    .box3 {
    background-color: blue;
    }
```
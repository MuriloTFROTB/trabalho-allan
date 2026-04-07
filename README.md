# Resumo: Margens, Padding e Bordas no CSS

## Margens (Margin)

As propriedades de **margem** do CSS são usadas para criar espaço ao
redor dos elementos, fora de quaisquer bordas definidas.

As margens definem a distância entre a borda de um elemento e os
elementos circundantes.

### Lados Individuais

O CSS possui propriedades para especificar a margem de cada lado de um
elemento:

-   `margin-top` -- define a margem superior
-   `margin-right` -- define a margem direita
-   `margin-bottom` -- define a margem inferior
-   `margin-left` -- define a margem esquerda

### Valores possíveis

-   `auto` -- o navegador calcula automaticamente a margem
-   `length` -- especifica a margem em px, pt, cm, etc.
-   `%` -- define a margem em porcentagem da largura do elemento pai
-   `inherit` -- herda a margem do elemento pai

⚠️ Valores negativos também são permitidos.

### Propriedade Abreviada

A propriedade `margin` permite definir todas as margens em uma única
linha.

``` css
margin: 25px 50px 75px 100px;
```

Ordem dos valores:

1.  Topo
2.  Direita
3.  Baixo
4.  Esquerda

### Centralização com `auto`

``` css
margin: auto;
```

Permite **centralizar horizontalmente** um elemento dentro do container.

### Herança com `inherit`

``` css
margin-left: inherit;
```

A margem será herdada do elemento pai.

------------------------------------------------------------------------

# Padding (Preenchimento)

As propriedades de **padding** definem o espaço **entre o conteúdo do
elemento e sua borda**.

### Lados Individuais

-   `padding-top`
-   `padding-right`
-   `padding-bottom`
-   `padding-left`

### Valores possíveis

-   `length` -- px, pt, cm, etc.
-   `%` -- porcentagem da largura do elemento pai
-   `inherit` -- herda do elemento pai

⚠️ **Valores negativos não são permitidos.**

### Propriedade Abreviada

``` css
padding: 25px 50px 75px 100px;
```

Ordem dos valores:

1.  Topo
2.  Direita
3.  Baixo
4.  Esquerda

------------------------------------------------------------------------

# Bordas (Border)

As propriedades de **border** permitem definir:

-   Estilo
-   Largura
-   Cor

## Estilo de Borda

A propriedade `border-style` define o tipo de borda.

Valores possíveis:

-   `dotted` -- borda pontilhada
-   `dashed` -- borda tracejada
-   `solid` -- borda sólida
-   `double` -- borda dupla
-   `groove` -- borda com ranhura 3D
-   `ridge` -- borda texturizada 3D
-   `inset` -- borda interna 3D
-   `outset` -- borda externa 3D
-   `none` -- sem borda
-   `hidden` -- borda oculta

A propriedade `border-style` pode ter **de 1 a 4 valores**, aplicados na
ordem:

1.  Topo
2.  Direita
3.  Baixo
4.  Esquerda

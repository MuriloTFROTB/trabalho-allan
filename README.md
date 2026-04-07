# Guia de Estilização CSS: Margens, Padding e Bordas

Este guia aborda os fundamentos do **Box Model** do CSS, focando em como controlar o espaço e os limites dos elementos.

---

## 1. Margens CSS (`margin`)
As propriedades de margem são usadas para criar espaço **ao redor** dos elementos, fora de quaisquer bordas definidas. Elas determinam a distância entre a borda de um elemento e os elementos vizinhos.

### Lados Individuais
Você pode controlar cada lado de forma independente:
* `margin-top`: Superior.
* `margin-right`: Direita.
* `margin-bottom`: Inferior.
* `margin-left`: Esquerda.

**Valores aceitos:**
* **auto**: O navegador calcula a margem (usado para centralizar).
* **comprimento**: Especifica em `px`, `pt`, `cm`, etc.
* **%**: Porcentagem da largura do elemento pai.
* **inherit**: Herda o valor do elemento pai.

> **Dica:** Diferente do padding, as margens permitem **valores negativos**.

### Propriedade Abreviada (Shorthand)
Para simplificar o código, use apenas `margin`. A ordem dos valores segue o sentido horário:
1. Topo
2. Direita
3. Base
4. Esquerda

```css
/* Topo: 25px, Direita: 50px, Base: 75px, Esquerda: 100px */
margin: 25px 50px 75px 100px;
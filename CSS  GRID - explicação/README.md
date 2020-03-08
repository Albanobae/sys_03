# CSS GRID

## GRID

- Bidimensional
- Divisão de toda a página em linhas e colunas
- Colocar elementos onde quiser nessa divisão

---

## GRID OU FLEXBOX

- Grid; duas dimensões (colunas e linhas)
- Flexbox: uma dimensão (ou coluna ou linha)
- Um complementa o trabalho do outro
- Verificas quais navegadores ainda estão aceitando o grid

---

## PROPRIEDADES

Separando em 2 grupos:
`container` e `item(s)`

## CONTAINER

- display: grid;
- grid-template-columns;  (COLUNAS)
- grid-template-rows;     (LINHAS)
- grid-gap                (ESPAÇAMENTOS ENTRE A COLUNAS E LINHAS)
    - grid-row-gap
    - grid-columns-gap
- grid-template-areas:     (ÁREA)

... e mais 4 propriedades e **alinhamentos**

## ITEM(s)

- grid-column
    - grid-column-start
    - grid-column-end
- grid-row
    - grid-row-start
    - grid-row-end
- grid-area

... e mais 2 propriedade de **alinhamento**

---
# GRID: Alinhamento

Existe 6 propriedade para alinhamento:
1. `justify-content`
2. `align-content`
3. `justify-items`
4. `align-items`
5. `justify-self`
6. `align-self`

Vamos depará-los em 2 grupos.
1. `justify` e `align`
2. `content`, `items` e `self`

---

## justify e Align

Sabendo que o grid é bidimensional, nós temos o eixo x e y.

O *eixo X* é o posicionamento horizontal, da esquerda para a direita.
O *eixo Y* é o posicionamento vertical, de cima para baixo.  

---

## Content, Items e Self

Juntando `justify`, ou `align`, com esses elementos: `content`, `items` e `self`; nós observamos nossas propriedades

---

### Content

`justify-content` e `align-content` nos permite alinhar o próprio grid, relativo ao espaço fora do grid. 

O uso dessas propriedades são raras, pois só é aplicado caso o grid seja menor que área definida. (Por exemplo, quando usamos em px o tamanho do grid, podemos terminar com um gride pequeno, para o tamanho da área do grid)

Podemos usar *7 valores*:
1. start
2. end
3. center
4. stretch
5. space-between
6. space-around
7. space-evenly

### Items

`justify-content` e `align-content` vai permitir alinhar os items do nosso grid, em qualquer espaço disponível, na célula que ele habitar 

---

### Self

`justify-self` e `align-self` vai nos permitir alinhar o item em si.

Faz a mesma coisa que o `justify-items` e `align-item`, porém, aplicado diretamente no item de um grid.

********Fonte*: https://www.youtube.com/watch?v=HN1UjzRSdBk
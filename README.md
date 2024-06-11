## PROPRIEDADES FUNDAMENTAIS

Todo grid é composto de 2 principais grupos:
`container: o pai` e `itens: o(s) filhos`

---
### CONTAINER (pai)

- display: grid;

- grid-template; (atalho para...)
  - grid-template-columns; (quantas colunas no grid por tamanho)
  - grid-template-rows; (quantas linhas no grid por tamanho)
  - grid-template-areas;

- gap;(atalho para...)
  - row-gap;
  - column-gap;

---
### ITENS (filhos)

- grid-column;(atalho para...)
  - grid-column-start; (linha virtual início)
  - grid-column-end; (linha virtual fim)

- grid-row;(atalho para...)
  - grid-row-start; (linha virtual início)
  - grid-row-end; (linha virtual fim)

- grid-area; (nome dado quando feito a area no pai)

---
### PROPRIEDADES DE ALINHAMENTO

Existem 9 propriedades FUNDAMENTAIS

**6 aplicadas em container** (pai)
`align-content`
`justify-content`
`place-content`

`align-items`
`justify-items`
`place-items`

**3 aplicadas em items** (filhos)

`align-self`
`justify-self`
`place-self`

Então podemos separar em 3 grupos:
`align` (aplica alinhamento no eixo X vertical), `justify` (aplica alinhamento no eixo Y horizontal) , `place` (aplica alinhamento em ambos os eixos vertical e horizontal)

E cada um deles irá observar ou observar
- conteúdo do elemento `content`.
- itens do elemento `items`. (remove a largura e altura do objeto)
- o próprio elemento `self`.

---
### PROPRIEDADES AUTO

- grid-auto-flow
- grid-auto-rows
- grid-auto-columns

---
# Grid ou Flex
tanto faz, defina o que é mais simple de usar e resolver.












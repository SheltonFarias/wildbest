# Display Grid

inline-grid => Torna o elemento um grid container porém com comportamento inline

subgrid => Para grids dentro de grids

grid-template-columns => Define o número total de colunas que serão criadas no grid

min-max => define um tamanho minimo e tamanho maximo

repeat() => usado para criar colunas repetidas com as mesmas medidas

auto-fit => usado para agrupar o maximo de colunas com a medida informada

grid-template-rows

grid-template-areas
- Vai definir o formato do layout da pagina
"sidebar nav nav"
"sidebar section section"
"sidebar footer footer"

usando grid area para atribuir cada valor a cada classe
.sidebar {
  grid-area: sidebar;
}

grid-template => atalho para definir grid-template-columns, grid-template-rows e gird-template-areas

grid-gap => define o gap(gutter entre os elementos do grid)
grid-gap passou a ser apenas gap
Aceitando dois valores o primeiro refente as linhas e o segundo as colunas
gap: 10px(linhas) 15px(colunas);

grid-auto-columns => Define o tamanho das colunas do grid implicito (gerado automaticamente, quando algum elemento é posicionado em uma coluna que não foi definida)

grid-auto-rows => Define o tamanho das linhas do grid implicito (gerado automaticamente, quando algum elemento é posicionado em uma linha que não foi definida)

grid-auto-flow => Define o fluxo dos itens no grid. Se eles vão automaticamente gerar novas linhas ou colunas

justify content => tem o mesmo funcionamento que no display flex, porem interressante definir tamanho da coluna. Eixo X

align content => Eixo Y


Grid item

- Os Grids itens são filhos diretos do grid container. Um Grid item pode ser explicito ou implicito

explicito => define ele explicitamente no container

Implicito => criado automaticamente para preencher

grid-column => vai definir inicio de fim da linha

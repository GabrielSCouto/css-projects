# Layout Responsivo com CSS Flexbox e CSS Grid

Este repositório contém dois projetos que implementam o mesmo layout. O primeiro utiliza **HTML5 com tags semânticas e CSS Flexbox**, enquanto o segundo combina **CSS Grid com Flexbox** para estruturar o layout. Ambos são responsivos, adaptando-se a diferentes tamanhos de tela.

## Como visualizar
**Clique para acessar os projetos:**
- [HTML semântico + Flexbox](https://gabrielscouto.github.io/css-html-basics-project/index.html)
- [CSS Grid + Flexbox](https://gabrielscouto.github.io/css-grid-flexbox-project/index.html)

## Estrutura dos Projetos

### Projeto 1: Layout com CSS Flexbox
- Utilização de `header`, `main`, `section`, `article`, `aside`, `footer` e `nav` como tags semânticas.
- Estrutura organizada em colunas usando `display: flex`.
- Responsividade aplicada com ajustes de `flex-direction` e `width` para telas menores.

### Projeto 2: Layout com CSS Grid + Flexbox
- Estrutura semelhante ao Projeto 1, mas com `display: grid` para controlar a área principal do layout.
- Utilização de `grid-template-columns` para distribuir `main`, `aside`, `nav`, etc.
- Flexbox ainda é utilizado dentro de seções específicas, como `article` e elementos dentro do `aside`, para alinhamentos internos.
- Facilita o controle mais preciso de posicionamento de áreas.

## Responsividade

Ambos os projetos são responsivos e se adaptam a diferentes tamanhos de tela com o uso de:
- `@media (max-width: 768px)` para reorganizar as colunas em blocos empilhados.
- Flexbox: trocando `flex-direction` de `row` para `column` quando necessário.
- Grid: realocando áreas de grid com `grid-template-columns` específicas para telas pequenas.

## Principais diferenças notadas

- **Flexbox** é direto e ótimo para organizar elementos em linha ou coluna, mas exige mais trabalho e repetição para layouts mais sofisticados.
- **CSS Grid combinado com Flexbox** oferece mais controle estrutural, tornando a organização do layout mais clara e mantendo o código mais organizado, especialmente quando há muitas áreas envolvidas.



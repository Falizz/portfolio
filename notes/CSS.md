# Principais Propriedades CSS Usadas no Mercado

## Estrutura básica
- `selector { propriedade: valor; }` → sintaxe geral do CSS.  
- `*` → seletor universal (aplica a todos os elementos).  
- `.` → seleciona uma **classe**.  
- `#` → seleciona um **id**.  
- `element` → seleciona uma **tag HTML**.  
- `selector1, selector2` → múltiplos seletores.  
- `selector selector` → seletor descendente (elemento dentro de outro).  

---

## Texto e fontes
- `color` → cor do texto.  
- `font-size` → tamanho da fonte.  
- `font-family` → tipo de fonte.  
- `font-weight` → espessura (ex.: normal, bold, 400, 700).  
- `text-align` → alinhamento (left, right, center, justify).  
- `line-height` → altura da linha.  
- `text-decoration` → sublinhado, riscado, etc.  
- `text-transform` → maiúsculas, minúsculas, capitalização.  

---

## Cores e fundos
- `background-color` → cor de fundo.  
- `background-image` → imagem de fundo.  
- `background-size` → tamanho da imagem (cover, contain).  
- `background-position` → posição da imagem.  
- `background-repeat` → repetir ou não a imagem.  
- `opacity` → transparência (0 a 1).  

---

## Espaçamento e caixa
- `margin` → espaço externo.  
- `padding` → espaço interno.  
- `border` → borda (largura, estilo, cor).  
- `border-radius` → cantos arredondados.  
- `width` / `height` → largura e altura.  
- `max-width` / `min-width` → limites de largura.  
- `box-sizing` → define como largura/altura são calculadas (content-box, border-box).  

---

## Layout e posicionamento
- `display` → tipo de exibição (block, inline, inline-block, flex, grid, none).  
- `position` → posicionamento (static, relative, absolute, fixed, sticky).  
- `top`, `right`, `bottom`, `left` → deslocamentos quando `position` ≠ static.  
- `z-index` → ordem de sobreposição.  
- `float` → flutuação de elementos (menos usado hoje).  
- `clear` → controla elementos após float.  

---

## Flexbox (muito usado no mercado)
- `display: flex;` → ativa flexbox.  
- `flex-direction` → direção (row, column).  
- `justify-content` → alinhamento horizontal (flex-start, center, space-between...).  
- `align-items` → alinhamento vertical (flex-start, center, stretch...).  
- `flex-wrap` → quebra de linha dos itens.  
- `gap` → espaçamento entre os itens.  

---

## Grid (para layouts complexos)
- `display: grid;` → ativa grid.  
- `grid-template-columns` → define colunas.  
- `grid-template-rows` → define linhas.  
- `grid-column` / `grid-row` → posicionamento dos itens.  
- `gap` → espaçamento entre células.  

---

## Estilização avançada
- `box-shadow` → sombra de caixa.  
- `text-shadow` → sombra no texto.  
- `overflow` → rolagem/conteúdo oculto (visible, hidden, scroll, auto).  
- `cursor` → estilo do cursor (pointer, default, not-allowed).  
- `transition` → animações suaves em propriedades.  
- `transform` → transformações (rotate, scale, translate).  
- `animation` + `@keyframes` → animações customizadas.  

---

## Mais usadas no mercado
- **Layout:** `display`, `flex`, `grid`, `position`.  
- **Caixa:** `margin`, `padding`, `border`, `width`, `height`.  
- **Texto:** `color`, `font-size`, `text-align`, `font-weight`.  
- **Estilo:** `background`, `border-radius`, `box-shadow`.  
- **Interatividade:** `transition`, `cursor`, `hover`.  

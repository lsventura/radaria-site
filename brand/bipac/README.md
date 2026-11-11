# Bipac — Biblioteca vetorial (400 SVG individuais)

Esta pasta contém **200 variações do mascote Bipo** e **200 símbolos de interface**, sem raster e sem imagens embutidas. Os SVGs têm fundo transparente e viewBox próprio. A identidade preserva a linguagem original do Bipo: corpo verde-floresta, rosto marfim, detalhes lima, antena de radar e geometria amigável **2D minimalista**.

## Pastas

- `mascotes/`: 20 expressões faciais × 10 ações/situações, totalizando **200 arquivos individuais SVG** (320 × 356 em unidades do viewBox).
- `icones/`: **200 ícones individuais SVG** de 24 × 24, organizados logicamente em 10 famílias de 20: navegação, ofertas, preços, produtos, comércio, categorias, confiança, alertas, engajamento e inteligência.
- `manifest.json`: identificadores, usos, categorias, nomes e caminhos.
- `catalogo.html`: galeria offline com pesquisa, filtros, pré-visualização e downloads individuais.
- `tokens.css`: tokens de marca.
- `LICENCA-LUCIDE.txt`: aviso de licença dos pictogramas Lucide (ISC).

## Direção criativa

Os 200 mascotes são **variações sistemáticas** do mesmo personagem, não 200 novos personagens: combinações individuais de 20 rostos e 10 objetos/ações. Cada SVG tem formas editáveis, sem filtros ou gradients e sem dependência de bibliotecas. Nenhum arquivo legado de `brand/mascote/` foi sobrescrito.

Os 200 ícones foram selecionados individualmente do projeto **Lucide**, padronizados para o verde oficial, e não devem ser apresentados como pictogramas 100% inéditos. Atribuição conforme o arquivo de licença. 

## Cores

- Verde-floresta `#193C30`; verde-escuro `#102E24`.
- Verde-lima `#D5EF80`.
- Marfim `#FFF9E9`; off-white `#E7EFDF`.

## Uso e QA

Para revisar: abra `catalogo.html` no navegador, mesmo sem servidor; todos os dados estão embutidos. Use o SVG original em `<img>` ou inline; para trocar cores dinamicamente, converta os atributos fixos de cor para tokens locais de seu projeto. Verifique acessibilidade e leitura em 24px (ícones) e 64px+ (Bipo completo). A versão de **rosto isolado** existente no projeto continua indicada para favicon/16px.

A inclusão desta biblioteca **não altera** o nome exibido no site, que no código atual segue como **Bipeque**, e **não integra nem ativa** ícones novos automaticamente. A adoção deve acontecer depois da revisão da marca e dos componentes.

## Prévia dos 200 ícones em PNG

Os quatro painéis abaixo contêm renderizações fiéis dos 200 SVGs para revisão visual (50 por página). Os arquivos individuais continuam em `icones/`.

- [Página 1 — ícones 1 a 50](preview/bipac-icones-1.png)
- [Página 2 — ícones 51 a 100](preview/bipac-icones-2.png)
- [Página 3 — ícones 101 a 150](preview/bipac-icones-3.png)
- [Página 4 — ícones 151 a 200](preview/bipac-icones-4.png)

> A prancha de 16 poses aprovada na conversa é uma referência de direção artística separada; **não** confundir com os 200 SVGs sistemáticos desta biblioteca.

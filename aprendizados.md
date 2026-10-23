# Aprendizados

Registre aqui, com data, o que funcionou, o que não funcionou e o que o dono pediu para não repetir.

> Em 2026-10-23 a dona zerou o projeto anterior. Os aprendizados presos àquele
> projeto foram arquivados (ficam no histórico do Git). Ficaram só os que
> valem para qualquer projeto.

## 2026-10-14 — Pesquisa
- **Aprendizado:** fala espontânea de mães sobre Disney quase não aparece em
  buscadores (está em Instagram, TikTok e WhatsApp). Para linguagem real, a
  fonte mais valiosa são as conversas da própria LUMI.
- **Aprendizado:** o Reddit bloqueia leitura automática nas sessões.
  TouringPlans, WDWMagic, EarScouts, planDisney e Mumsnet abrem.
- **Origem:** pesquisas de público de 2026-10-14 (hoje em `arquivo/`).

## 2026-10-14 — Antes de escrever sobre o serviço
- **Aprendizado:** texto escrito com contexto parcial ficou fraco. Antes de
  escrever sobre o mecanismo, ler "Mecanismo" em `contexto/oferta.md`.
- **Aprendizado:** não propor produto que entregue horários ou ordem fixa de
  atrações por escrito. O dia é dinâmico, e o valor da LUMI é o
  acompanhamento ao vivo.
- **Aprendizado:** textos em inglês precisam de revisão de falante nativo
  antes de publicar.
- **Origem:** conversa com a dona.

## 2026-10-23 — Separar empresa de projeto
- **Aprendizado:** uma sessão anterior registrou decisões de projeto como se
  fossem dados da empresa, e a dona não reconheceu algumas delas (ex.: o PDF).
  Agora `contexto/` guarda só fatos da empresa e `projeto/` guarda as
  decisões. Toda decisão leva data e a frase de quem decidiu. Sugestão do
  Claude aceita pela dona deve ser registrada como "sugerido pelo Claude,
  aprovado pela dona".
- **Aprendizado:** o site pode ser lido nas sessões. O Instagram mostra a
  bio e alguns posts uma vez e depois bloqueia o acesso automático: para
  análise de posts, peça prints à dona.
- **Erro a não repetir:** o site é feito no Framer, e o HTML bruto traz textos
  escondidos das animações. Lendo só o HTML, apontei um erro inexistente no
  FAQ. Para conferir textos do site, abra no navegador (Playwright) e clique
  nos itens antes de afirmar qualquer coisa.
- **Origem:** conversa com a dona.

## 2026-10-23 — Identidade visual (etapa 1)
- **Aprendizado:** a melhor base visual que já existe são as apresentações em
  PDF: Cormorant Garamond (títulos) + Lato (texto), confirmado com `pdffonts`.
  O site usa Playfair Display, Inter e Montserrat, e cada tabela usa outra
  dupla de fontes. O guia unifica tudo em Cormorant Garamond + Lato.
- **Aprendizado:** a Cormorant tem algarismos "antigos" (no Canva, "01" parece
  "OI" e o "3" desce da linha). Número sozinho (preço, 01, ano) vai em Lato.
- **Aprendizado:** o dourado do logo (`#B68237`) não passa no contraste AA para
  texto pequeno (3,23:1 sobre o creme). Para texto, use o Dourado Escuro
  `#8A5F22` no fundo claro e o Dourado Claro `#D9AE6A` no marinho.
- **Aprendizado:** os PNG do logo têm 500x500 com borda transparente larga
  (desenho em x 96–398, y 134–360). Recorte antes de usar.
- **Para ver o site:** Chromium em `/opt/pw-browsers/chromium-1243/chrome-linux64/chrome`,
  Playwright com `NODE_PATH=$(npm root -g)`. Fontes reais do site lidas por
  `getComputedStyle`.
- **Origem:** guia de identidade visual,
  `entregas/design-criativos/2026-10-23-identidade-visual.md` (aguarda
  aprovação da dona).

## 2026-10-23 — Tabelas de preço (etapa 2)
- **Aprendizado:** um HTML só serve para os dois formatos: medidas em
  variáveis CSS, em px para a imagem 1080x1350 (tela) e em mm/pt dentro de
  `@media print` para o PDF A4. Atenção: variável redefinida numa classe do
  `body` (ex.: `.dense`) vence o `:root` do print; no print, redefina também
  em `body.<classe>`.
- **Aprendizado:** o Chromium do Playwright baixa as fontes do Google Fonts
  pela proxy da sessão (`proxy: { server: process.env.HTTPS_PROXY }`), sem
  desligar verificação TLS. Use `display=block` no link das fontes, espere
  `document.fonts.ready` e confira com `document.fonts.check(...)`. O PDF sai
  com Cormorant e Lato embutidas (conferido com `pdffonts`).
- **Aprendizado:** cabeçalho de tabela com fundo em cada `th` mostra um fio
  claro entre as colunas no PDF. Pinte o fundo no `thead tr` e arredonde os
  cantos num contêiner com `overflow:hidden`.
- **Aprendizado:** a tabela de 15 linhas (clientes americanos) não cabe no
  post 1080x1350 com o preço em 60–72 px do guia; ficou em 36 px. Tabelas de
  até 6 linhas cabem com 52–60 px.
- **Aprendizado:** os preços com desconto de 5% (11, 13, 15 pessoas) são
  arredondados para baixo na tabela oficial ($522,50 vira $522). Respeitar o
  valor da tabela.
- **Origem:** produção das tabelas em
  `entregas/design-criativos/tabelas-2026-10-23/`.

## 2026-10-23 — Tabelas de preço reprovadas e refeitas (versão enxuta)
- **Aprendizado:** Tabela de preço é direta. A dona reprovou letra e logo
  grandes, frase de apoio e rodapé com contato. Use as tabelas originais dela
  como referência de tamanho.
- **Aprendizado:** medidas que bateram com a referência
  (`contexto/materiais/tabela-tour-presencial.webp`) no canvas 1080x1350:
  logo 56 px de altura, título Cormorant 54 px em 2 linhas, cabeçalho 64 px
  com Lato Bold 14 px, linhas de 91 px (4 linhas) ou 80 px (6 linhas),
  números Lato Regular 26 px, linha final em Lato Itálico 16 px. Compare
  medindo a altura dos glifos com PIL (faixas de pixels), não no olho.
- **Aprendizado:** o atalho `font:` no CSS zera `font-variant-numeric`. Sem
  repor `lining-nums` depois dele, a Cormorant mostra "15%" com algarismos
  antigos (parece "I5%").
- **Aprendizado:** para o PDF A4 sair com as mesmas proporções do PNG, basta
  `zoom: 210/285.75` na página dentro de `@media print` (1080 px viram
  210 mm) e altura de 1527 px; o resto do A4 fica como respiro.
- **Origem:** reprovação da dona e refação das tabelas em
  `entregas/design-criativos/tabelas-2026-10-23/`.

## 2026-10-23 — Padrão de título das tabelas de preço aprovado pela dona
- **Aprendizado:** padrão de título aprovado para as 5 tabelas (igual em
  todas): sobretítulo dourado em caixa alta (Lato Bold, Dourado Escuro
  `#8A5F22`, espaçamento 0,18 em, 16 px no 1080x1350) com o **nome do
  serviço**; título Cormorant de uma linha curta ("Experiência LUMI" / "The
  LUMI Experience" / "Comissão de 15% por indicação"); filete dourado curto.
  Sem subtítulo nem frase de apoio. Embaixo: caixa de nota (Areia + barra
  dourada) só quando há nota, e rodapé com a estrela + "Valor por parque, por
  dia" em Lato Bold Marinho. Sem site e sem telefone.
- **Aprendizado:** o sobretítulo é o que diz que a tabela é virtual; sem ele,
  as tabelas virtuais não diziam o serviço.
- **Aprendizado (nomes dos serviços):** PT "Tour Presencial" e "Guiamento
  Virtual"; EN "In-Person Park Tour" e "Virtual Park Guidance". "Virtual
  tour" em inglês e "tour virtual" em português soam como visita online em
  360°; "assistance" lembra o serviço de acessibilidade da Disney.
- **Aprendizado:** com a página em `display:flex; flex-direction:column`, o
  rodapé com `margin:auto 0 0` encosta na margem de baixo; zere a margem de
  baixo do `<p>` (o padrão de 1em empurra o rodapé 21 px para cima).
- **Origem:** pedido da dona na rodada 4 das tabelas em
  `entregas/design-criativos/tabelas-2026-10-23/` e seção 8a do guia
  `entregas/design-criativos/2026-10-23-identidade-visual.md`.

## 2026-10-23 — Tabelas de preço (versão 5)
- **Aprendizado:** a dona corta o que "não agrega". O título de marca
  ("Experiência LUMI") saiu: numa tabela, o título é o nome do serviço. A
  linha dourada em caixa alta serve para a informação extra (ex.: comissão),
  e "Valor por parque, por dia" fica colado à tabela, não solto no rodapé.
- **Origem:** retorno da dona sobre as tabelas,
  `entregas/design-criativos/tabelas-2026-10-23/`.

## 2026-10-23 — Nomes dos serviços padronizados
- **Aprendizado:** em português, use a palavra que o cliente usa: os
  clientes pedem "tour" (dona). Ficou "Tour Presencial" e "Tour Virtual". Em
  inglês, "In-Person Park Guidance" e "Virtual Park Guidance", porque "virtual
  tour" soa como visita online. Um termo por idioma, sem misturar.
- **Erro a não repetir:** recomendei "guiamento" com base em pesquisa de
  mercado arquivada; a vivência da dona com os clientes vale mais. Antes de
  fixar um termo, pergunte como os clientes falam.
- **Origem:** retorno da dona sobre as tabelas.

## 2026-10-23 — Metas de 3 a 12 meses
- **Aprendizado:** a capacidade não é o gargalo. Só a dona atende cerca de 12
  famílias por mês (2 por dia, ~22 dias, 3,5 parques por família) e hoje usa
  cerca de 15%. O gargalo é a demanda previsível (canal) e a falta de medição.
- **Aprendizado:** a receita por família vai de ~$600 (brasileira, 4 pessoas,
  3 parques) a ~$1.600 (presencial, 4 a 5 pessoas, 4 parques). Para contas,
  usar ticket médio de ~$700 a $750 como [PREMISSA] até a dona informar o
  faturamento real.
- **Aprendizado:** dado de mercado com fonte: Orlando teve 76,7 milhões de
  visitantes em 2025; o Brasil foi o 3º país estrangeiro (736.300, +5,6%),
  segundo a Visit Orlando (maio/2026).
- **Aprendizado:** a venda das férias de julho acontece entre janeiro e abril
  [PREMISSA]; planejar ações com esse prazo.
- **Origem:** proposta de metas,
  `entregas/estrategia-negocio/2026-10-23-metas-3-12-meses.md` (aguarda a
  dona).

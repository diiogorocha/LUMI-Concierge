# Briefing visual: PDF-isca em inglês ("Park Day Prep Guide")

**Cliente:** LUMI Concierge
**Data:** 2026-10-14
**Setor:** Design e Criativos Visuais
**Especialistas usados:** UX Designer (hierarquia, leitura no celular, formulário preenchível e acessibilidade WCAG 2.1 AA), Visual Generator (paleta, diagrama, mockups e prompts de imagem) e Alina Wheeler (identidade provisória como sistema, sem desenhar logo antes de estratégia).
**Base:** `contexto/` (marca, negócio, oferta, público), `aprendizados.md` e `entregas/funil-lancamento/funil-isca-pdf-instagram-ingles.md` (seções 3.3 e 4). O texto final vem do setor copy em `entregas/copy/isca-pdf-park-day-prep-guide.md`, entregue durante este trabalho. A estrutura de 10 páginas do copy bate com a deste briefing, e as páginas 3 e 4 já foram ajustadas às tabelas do copy. Os demais textos em inglês abaixo são **placeholders de diagramação**: na montagem, vale sempre o texto do copy.

| Marca | Significado |
| --- | --- |
| [FATO] | Vem de `contexto/` ou do funil aprovado |
| [PROPOSTA, dono aprova] | Decisão visual sugerida aqui; o dono aprova ou troca |
| [PREMISSA] | Assumido para seguir; confirmar |
| [VERIFICAR] | Conferir na ferramenta ou na fonte antes de fechar |
| [SEM DADO] | Falta informação do dono |

---

## 0. Em uma frase

Um guia de 10 páginas, **US Letter**, com cara de "caderno de planejamento calmo e organizado" (não de parque temático). Ele é útil de verdade nas páginas 3 a 6 (ferramentas para preencher) e convence nas páginas 7 e 8 (o diagrama de **tempo morto x reservas encadeadas**). A página 10 leva a mãe a mandar uma mensagem com as datas da viagem.

**Princípio visual:** a LUMI é a pessoa organizada que segura o celular por você. O visual transmite **ordem, calma e confiança**: muito respiro, uma cor forte só, ícones de linha. Nada de "magia", brilho, castelo ou fonte fantasiosa. Isso também afasta qualquer aparência de material oficial da Disney.

---

## 1. Formato e grid

| Item | Especificação |
| --- | --- |
| Página | **US Letter, 8,5 x 11 pol. (612 x 792 pt)**, retrato [FATO funil] |
| Páginas | 10 (aceitável de 8 a 12 se o copy pedir) [FATO funil] |
| Margens | Laterais **0,75 pol. (54 pt)**; topo **0,75 pol.**; base **1 pol. (72 pt)**, que reserva espaço para o rodapé. Nada essencial a menos de 0,5 pol. da borda (impressoras domésticas não imprimem cerca de 0,25 pol. da borda) [PREMISSA] |
| Sangria | Só a capa e a página 10 têm fundo de cor sangrando. Na versão para imprimir, **sem sangria** (ver seção 7) |
| Grid | **12 colunas**, gutter de **12 pt**, área útil de 504 pt de largura. Texto corrido em no máximo 8 colunas (cerca de 60 a 75 caracteres por linha). Tabelas e diagramas usam as 12 |
| Linha de base | Múltiplos de **6 pt** para espaçamentos (6/12/18/24/36/48) |
| Leitura no celular | A maioria vai abrir no celular [PREMISSA]. Por isso: **1 ideia por página**, títulos grandes, corpo de 13 pt (não 12) e nenhum texto essencial abaixo de 11 pt. Alternativa do funil para testar depois: versão 4:5 "estilo carrossel" [HIPÓTESE funil]. Não fazer as duas agora |

**Estrutura fixa de toda página interna (de cima para baixo):**
1. Faixa de etapa no topo à esquerda (ex.: `STEP 1 OF 3`, ou o nome da seção), em versalete 10 pt, cor Lagoon.
2. Título da página (H1).
3. Linha de apoio de uma frase (lead).
4. Conteúdo (ferramenta, lista ou diagrama).
5. Rodapé (seção 4.2).

---

## 2. Identidade provisória

`contexto/marca.md` tem **Cores: [SEM DADO]**, **Fontes: [SEM DADO]** e não há logo registrado [FATO]. Tudo nesta seção é **[PROPOSTA, dono aprova]**. Se o dono já tiver cores, fontes ou logo em uso no Instagram, eles substituem esta proposta, e só as regras de contraste da seção 8 continuam valendo.

**Logo:** [SEM DADO]. Enquanto não houver, usar **wordmark tipográfico**: "LUMI" na fonte de títulos, peso regular, mais "Concierge" em versalete na fonte de texto. Não desenhar símbolo agora (Wheeler: estratégia antes de marca).

### 2.1 Paleta [PROPOSTA, dono aprova]

Lógica: um verde-azulado profundo passa calma e competência; um coral quente traz o lado "família" e marca o problema (tempo morto). Evita de propósito a combinação azul royal com dourado e o trio vermelho, preto e amarelo, que lembram material da Disney.

| Nome | HEX | Uso |
| --- | --- | --- |
| **Ink** | `#1F2A37` | Texto principal, contornos do diagrama |
| **Lagoon** (primária) | `#0F5C63` | Títulos, faixas de etapa, botões, barras de "reserva" no diagrama |
| **Sand** (fundo) | `#FBF6EE` | Fundo das páginas na versão digital |
| **Mist** | `#E3F0EF` | Caixas de destaque, linhas alternadas de tabela, fundo de campos |
| **Coral** (acento) | `#E8704A` | **Só gráfico**: barras de "dead time" (sempre hachuradas e com contorno Ink), marcadores. **Nunca para texto sobre fundo claro** |
| **Coral Deep** | `#B8461F` | Texto de destaque curto em coral, quando preciso |
| **Slate** | `#5B6573` | Texto secundário, legendas, rodapé |
| **Sun** | `#F4C46B` | Opcional, só em fundo de etiqueta pequena ("Example") com texto Ink |

**Contraste calculado (WCAG 2.1):**

| Combinação | Razão | Resultado |
| --- | --- | --- |
| Ink sobre Sand | 13,5:1 | AA e AAA |
| Lagoon sobre Sand | 7,2:1 | AA e AAA |
| Branco sobre Lagoon (botão) | 7,7:1 | AA e AAA |
| Slate sobre Sand | 5,5:1 | AA |
| Ink sobre Mist | 12,4:1 | AA e AAA |
| Coral Deep sobre Sand | 5,0:1 | AA |
| Ink sobre Coral | 4,7:1 | AA (texto Ink dentro de barra coral, se houver) |
| Ink sobre Sun | 9,0:1 | AA e AAA |
| **Coral sobre Sand** | **2,9:1** | **Reprovado** para texto e no limite para gráfico. Por isso o coral leva sempre hachura e contorno Ink |
| Coral sobre branco | 3,1:1 | Reprovado para texto |

### 2.2 Tipografia (fontes gratuitas) [PROPOSTA, dono aprova]

| Papel | Fonte sugerida | Alternativa | Por quê |
| --- | --- | --- | --- |
| Títulos | **DM Serif Display** (Google Fonts, licença OFL) | Fraunces (OFL) | Serifa calorosa e editorial, com cara de "guia confiável". Nada de fonte fantasiosa |
| Texto, tabelas, campos | **Inter** (Google Fonts, OFL) | Source Sans 3 (OFL) | Ótima leitura em tela pequena, números tabulares para horários |

Disponibilidade das duas no Canva: [VERIFICAR]. Se faltar alguma, usar a alternativa ou subir a fonte (OFL permite).

**Proibido em tipografia:** fontes script ou "de conto de fadas", qualquer fonte que imite o lettering da Disney (inclusive fontes "inspiradas" de sites de fontes grátis) e qualquer palavra da Disney desenhada como logotipo.

**Hierarquia:**

| Nível | Fonte e peso | Tamanho / entrelinha | Cor |
| --- | --- | --- | --- |
| Título da capa | DM Serif Display | 44 a 52 pt / 1,05 | Ink sobre Sand ou Sand sobre Lagoon |
| Subtítulo da capa | Inter Regular | 16 pt / 1,35 | Ink ou Slate |
| H1 (título de página) | DM Serif Display | 30 pt / 1,1 | Ink |
| Faixa de etapa | Inter SemiBold, versalete, espaçamento +8% | 10 pt | Lagoon |
| Lead (frase de apoio) | Inter Regular | 15 pt / 1,4 | Slate |
| H2 | Inter Bold | 17 pt / 1,25 | Lagoon |
| Corpo | Inter Regular | **13 pt / 1,5** | Ink |
| Itens de checklist | Inter Regular | 13 pt / 1,5, 12 pt entre itens | Ink |
| Cabeçalho de tabela | Inter SemiBold | 11 pt | Ink sobre Mist |
| Texto de campo preenchível | Inter Regular | 11 pt (auto não; tamanho fixo) | Ink |
| Legenda e rótulo "Example" | Inter Medium | 11 pt | Slate / Ink sobre Sun |
| Rodapé | Inter Regular | **9 pt** (mínimo absoluto; só no rodapé) | Slate |

### 2.3 Ícones, ilustração e fotos
- **Ícones:** só de linha, traço de 1,5 pt, cantos arredondados, cor Lagoon. Bibliotecas livres: **Lucide** (licença ISC) ou **Phosphor** (MIT) [VERIFICAR licença na data do download]. Ícones úteis: smartphone, alarm-clock, battery-charging, list-checks, users, map-pin, cookie (lanche), moon (soneca), message-circle, clock, timer.
- **Ilustração:** só diagramas e formas geométricas simples. Sem cenário de parque desenhado.
- **Fotos:** as preferidas são fotos próprias do expert em áreas abertas, sem personagens, sem fachada ou atração reconhecível e sem rosto de terceiros em destaque [FATO funil]. Banco de fotos do dono: [SEM DADO]. Sem foto, a capa funciona só com tipografia (seção 4, página 1).

---

## 3. O que pode e o que NÃO pode

### 3.1 Proibido (vale para PDF, posts e mockups)
- Logo, wordmark ou lettering da Disney, ou de qualquer parque.
- Castelo, Spaceship Earth, Árvore da Vida ou qualquer ícone arquitetônico reconhecível dos parques.
- Orelhas do Mickey, silhueta de três círculos, luvas brancas e qualquer forma que lembre personagem.
- Personagens (Disney, Pixar, Marvel, Star Wars) em foto, ilustração, figurino ou pelúcia que apareça na foto.
- Fontes da Disney ou que as imitem.
- **Prints do app My Disney Experience**, telas de reserva, mapas oficiais, ícones do app, cores do botão do Lightning Lane [FATO funil: prints só com avaliação jurídica, SEM DADO].
- Selos que pareçam oficiais: "Official", "Disney approved", "Authorized", "VIP", "Insider", estrelas de avaliação inventadas, "As seen on".
- Fogos sobre castelo, varinha, "pó de pirlimpimpim", brilhos e estrelinhas de "magia". Isso aproxima o visual da Disney e foge da proposta.
- Depoimentos, notas, números de clientes ou fotos de clientes [FATO: avaliações existem, mas não foram enviadas com autorização].
- Horários reais de atrações ou promessa de horário em qualquer gráfico [FATO `contexto/oferta.md`].
- Qualquer elemento que sugira pedir senha da conta Disney.

### 3.2 Permitido
- Nomes do sistema da Disney **como texto corrido e descritivo** (Lightning Lane, Multi Pass, Single Pass, Premier Pass, My Disney Experience, Rider Switch), na fonte do guia, sem estilização, sem cor própria e sem ícone. Nunca como título estilizado ou "selo". O uso de "Walt Disney World" no título está [SEM DADO jurídico], ver seção 3.2 do funil.
- Ícones genéricos (celular, relógio, bateria, lista).
- Fotos próprias genéricas: mochila, garrafa, protetor solar, carrinho de bebê, mão segurando celular com a tela **apagada ou desfocada**, sapatos de criança, mesa de hotel com o guia impresso.
- Wordmark provisório da LUMI.

### 3.3 Aviso de não afiliação (texto fixo) [FATO funil]
> **Independent guide. Not affiliated with or endorsed by The Walt Disney Company.**

- **Capa:** bloco próprio, 10 a 11 pt, Slate, abaixo do "by LUMI Concierge" e acima da borda inferior. Precisa ser legível na miniatura do post.
- **Rodapé de todas as páginas**, incluindo a 10.
- Se o copy incluir menção a marcas, acrescentar na página 10, em 9 pt: "Lightning Lane, Multi Pass, My Disney Experience and other Disney terms are trademarks of Disney, used here for descriptive purposes only." [PREMISSA; validar com advogado, SEM DADO].

---

## 4. Layout página a página

Convenção das colunas: `c1–c12`. Textos entre aspas são placeholders do funil; o copy define o texto final.

### Página 1: Capa
- **Fundo:** Sand, com um bloco Lagoon ocupando o terço inferior (sangria na versão digital).
- **Topo (c1–c8):** faixa "FREE PREP GUIDE" (versalete 10 pt, Lagoon).
- **Título (c1–c10), 48 pt:** opção 1 "Why Your Park Day Plan Falls Apart by 10 AM" ou opção 2 "The Designated Planner's Park Day Prep Guide". O dono ainda escolhe [FATO funil]. Diagramar as duas: a opção 1 cabe em 3 linhas; a opção 2, em 3 a 4 linhas a 44 pt.
- **Subtítulo (c1–c9), 16 pt.**
- **Elemento visual (c7–c12, meia altura):** uma **prévia miniatura do diagrama da página 7** (duas barras: uma com buraco hachurado coral, outra contínua em Lagoon), sem números. Isso planta o mecanismo já na capa. Alternativa com foto: foto própria genérica (mesa com mochila, garrafa e celular de tela apagada) [SEM DADO foto].
- **Dentro do bloco Lagoon:** "by LUMI Concierge" (wordmark em Sand) e, abaixo, o aviso de não afiliação em Sand, 10,5 pt (contraste Sand sobre Lagoon de cerca de 7,2:1).
- **Sem rodapé padrão na capa:** o aviso já está no bloco.

### Página 2: "If you're the designated planner…"
- Faixa: `BEFORE YOU START`.
- **H1** de uma linha + texto de cena (o copy escreve) em c1–c8, corpo 13 pt.
- **Caixa lateral (c9–c12), fundo Mist**, com dois blocos de 3 itens no máximo cada:
  - "This guide WILL…" (ícone list-checks).
  - "This guide WON'T…" (ícone x), incluindo "give you ride times. Nobody honest can." [FATO funil].
- Opcional: ícone grande de smartphone em linha, Lagoon, como respiro.

### Página 3: "How Lightning Lane works right now (in 60 seconds)"
- Faixa: `THE BASICS`.
- **Bloco A (c1–c12): as três opções** (Multi Pass / Single Pass / Premier Pass). O copy entregou uma tabela de 3 colunas ("Option / What it is / How it's priced"). Montar como tabela com cabeçalho Mist ou como três cartões lado a lado (4 colunas cada, fundo Mist, cantos de 8 pt); a escolha é do designer, desde que caiba na página. **Sem preço da Disney** [FATO funil; o copy também não cita].
- **Bloco A2: tabela "When can you book?"** do copy (hotel Disney: 7 dias antes; demais: 3 dias antes; 7:00 AM Eastern).
- **Bloco B: linha do tempo da janela de reserva.** Um eixo horizontal com três marcos:
  `T-7 days · 7:00 AM ET` (rótulo: "staying at a Disney Resort hotel") → `T-3 days · 7:00 AM ET` (rótulo: "staying elsewhere") → `Park day`.
  Marcos como círculos Lagoon de 10 pt, linha de 2 pt Ink, rótulos 11 pt.
- **Bloco C: quadro de fuso "What 7:00 AM Eastern means where you live"**, tabela de 2 colunas com linhas alternadas Mist. Usar as **8 linhas do copy**: Eastern, Central, Mountain, Arizona, Pacific, Alaska, Hawaii e United Kingdom. Destacar em negrito Lagoon a linha **Pacific (4:00 AM)**, a dor mais forte da mãe americana. A linha do Reino Unido é longa: deixar quebrar em 2 linhas, sem reduzir a fonte. Os horários batem com a conta de fuso feita no design.
- **Campos preenchíveis abaixo do quadro:** "My booking day: ____" e "My alarm (local time): ____".
- **Se a página 3 não couber** com corpo de 13 pt: primeiro tirar o Bloco B (a tabela "When can you book?" já diz o mesmo); se ainda faltar espaço, dividir em 3a (opções e janela) e 3b (quadro de fuso e campos). Nunca reduzir a fonte abaixo de 11 pt.
- **Nota obrigatória (11 pt, ícone de alerta em linha):** "Rules change. Always check the My Disney Experience app." [FATO funil].

### Página 4: Step 1, Family Must-Do List (ferramenta principal)
- Faixa: `STEP 1 OF 3`. H1: "Your Family Must-Do List".
- **Instrução em 3 passos numerados** (círculos Lagoon com número branco), em uma linha horizontal: "Everyone picks their top 3" → "Sort them" → "Bring this list to booking day".
- **Legenda de prioridade** com 3 etiquetas, que nunca dependem só da cor: cada uma tem **ícone + texto**. O copy sugere coração, estrela e balão; recomendo **3, 2 e 1 estrelas simples de linha**, que mostram a ordem sem precisar de legenda. Se o dono preferir os ícones do copy, ok, desde que o balão seja genérico (redondo, sem formato de orelhas):
  - ★★★ "Would cry if we missed it"
  - ★★ "Really want"
  - ★ "Bonus, if time allows"
  (Estrela simples de 5 pontas em linha; não usar estrela com brilho.)
- **Linha acima da tabela:** campos "Park: ____" e "Date: ____" [copy].
- **Tabela (c1–c12), 10 linhas** (como no copy), cabeçalho Mist, linhas com altura de **30 pt** (dá para escrever à mão e tocar no celular). Colunas do copy:

| Who picked it | Ride, show or experience | Level | Meets height? | Scary for little ones? | Family Top 5? |
| --- | --- | --- | --- | --- | --- |
| c1–c2 | c3–c6 | c7–c8 | c9 | c10–c11 | c12 |

- **Abaixo da tabela:** campo de 2 linhas "Our non-negotiables (snacks, naps, breaks, a parade, a meal)" e a caixa Mist "Why this matters" [copy].

- Campos: ver seção 6.
- **Rodapé interno (antes do rodapé padrão), 11 pt Slate:** "This is the list a live park day strategist works from." É a ponte com a oferta: a lista de prioridades é o insumo real da LUMI [FATO `contexto/oferta.md`].
- Se precisar de mais de 10 linhas, criar uma **página 4b** idêntica (opcional), em vez de reduzir a altura das linhas.

### Página 5: Step 2, Booking window checklist
- Faixa: `STEP 2 OF 3`.
- **Checklist em uma coluna (c1–c8)**, com caixas de 14 x 14 pt e contorno Ink de 1,25 pt. Itens do funil: app instalado e conta criada; ingressos e grupo todo vinculados; cartão salvo na conta da família; despertador; quem do grupo vai reservar; lista do passo 1 aberta [FATO funil].
- Campos de texto nos itens "Who books: ____" e "Alarm set for: ____ (local time)".
- **Caixa lateral (c9–c12), Mist:** ícone de cadeado + "Never share your Disney password with anyone. Not even us." [FATO regra: nunca pedir senha]. Texto final do copy.
- Sem dicas de truque ou automação [FATO funil].

### Página 6: Step 3, Park morning checklist
- Faixa: `STEP 3 OF 3`.
- **Checklist em 2 grupos com ícone** (c1–c12, 2 colunas de 6):
  - "Phone & power" (battery-charging): celular carregado, bateria extra, quem segura o celular.
  - "Little humans" (cookie / moon): plano de lanche e soneca, Rider Switch se aplicável, ponto de encontro.
- Campos: "Phone holder: ____", "Meeting spot: ____".
- Sem números inventados (ex.: "leve X litros") [FATO funil].

### Página 7: "Why a fixed plan falls apart" (mecanismo, com o diagrama)
- Faixa: `THE PART NOBODY TELLS YOU`.
- **3 motivos em 3 colunas (4 colunas cada)**, cada um com ícone e 2 linhas [FATO `contexto/oferta.md`]:
  1. clock: os horários disponíveis vão ficando mais tarde ao longo do dia;
  2. users: quanto maior a família, mais difícil achar horário cedo para todos;
  3. alert: lotação, disponibilidade e atração fechada mudam o dia.
- **Diagrama "A day on paper vs. a real day" (c1–c12, cerca de 40% da página):** especificação na seção 4.1.
- **Etiqueta obrigatória** no canto superior direito do diagrama: fundo Sun, texto Ink, 11 pt: **"ILLUSTRATION · EXAMPLE, NOT A PROMISE"** [FATO funil: rotular exemplo, não prometer 9h–10h].

### 4.1 Diagrama "linha do tempo do dia"

**Objetivo:** em 3 segundos, a mãe vê que o problema não é planejar mal, e sim o **buraco entre as reservas**.

**Estrutura:** duas faixas horizontais sobre o mesmo eixo de tempo.

```
                 9:00 arrive
                    |
Eixo:  ─────────────┼──────┬──────┬──────┬──────┬──────┬──────▶  (ticks de hora SEM rótulo, exceto 9:00)

A  "Booked once, nobody re-booking"
   [RIDE 1]░░░░░░░░░░░░ dead time ~2 h ░░░░░░░░░░░[RIDE 2]░░░░░░░ dead time ░░░░░░[RIDE 3]

B  "Someone re-booking earlier all day"
   [RIDE 1][·][RIDE 2][·][RIDE 3][·][RIDE 4][·][RIDE 5][·][RIDE 6] …
             ↑ "a few minutes"
```

| Elemento | Especificação |
| --- | --- |
| Eixo | Linha Ink de 1,5 pt; ticks de hora iguais e **sem números**, exceto o marco "9:00 · arrive" [FATO: exemplo do dono, chegada às 9h] |
| Barra de atração (reserva) | Retângulo **sólido Lagoon**, altura de 22 pt, cantos de 4 pt, rótulo branco 11 pt "Ride 1", "Ride 2"… Nunca nomes reais de atrações |
| Tempo morto (faixa A) | Retângulo **Coral com hachura diagonal Ink a 45° (linhas de 0,75 pt a cada 4 pt)** e contorno Ink de 1 pt. Rótulo acima em Coral Deep, 11 pt: "dead time". No primeiro buraco, uma chave com "~2 hours until your next ride" [FATO: "dali a 2 horas", exemplo do dono] |
| Intervalo curto (faixa B) | Espaço estreito com um ponto Ink e, no primeiro, uma seta com "a few minutes" [FATO: "poucos minutos depois"] |
| Primeira atração | Nas duas faixas, Ride 1 começa logo depois do marco 9:00, dentro da janela 9–10 [FATO: meta do dono, rotulada como exemplo] |
| Rótulos das faixas | À esquerda, 13 pt Inter SemiBold: A "A plan on paper" / B "A day with someone re-booking" (texto final do copy) |
| Legenda | Abaixo: quadrado Lagoon = "booked ride"; quadrado hachurado = "waiting with nothing booked". A **hachura** faz a distinção sem depender de cor (daltonismo e impressão em P&B) |
| Proibido no diagrama | Horários além de 9:00, nomes de atrações, ícones de atração, número de atrações "garantido", qualquer selo de promessa |
| Texto alternativo (alt text) | "Illustration comparing two park days that start at 9:00. In the first, rides are booked once and there are long gaps of about two hours with nothing booked. In the second, someone keeps re-booking earlier times, so each ride starts a few minutes after the previous one. Example only, not a promise." |

**Variações para reaproveitar:** a mesma peça, simplificada e sem o eixo, vira miniatura da capa (página 1), tela de carrossel e quadro do Reels 1 do funil ("Your next Lightning Lane is 2 hours away").

### Página 8: "The re-booking game"
- Faixa: `WHAT IT ACTUALLY TAKES`.
- **Definição de "dead time" em destaque** (caixa Mist, c1–c12, DM Serif Display 20 pt).
- **Loop de 4 passos em círculo** (diagrama simples, 4 nós Lagoon ligados por setas Ink), sem detalhe operacional da LUMI [FATO funil]:
  check availability → swap to an earlier time → keep your priority order → don't cross the park.
  No centro do círculo: "all day long".
- **Pergunta final em grande** (DM Serif Display 26 pt, c1–c10): "Who's doing that while you're holding a toddler in line?" [FATO funil].

### Página 9: "Your honest options"
- Faixa: `YOUR OPTIONS`.
- **Tabela comparativa de 4 colunas** (c1–c12), sem nome de concorrente [FATO funil]:

| | Do it yourself | Booking bot | Premier Pass | Live human strategist |
| --- | --- | --- | --- | --- |
| Linhas sugeridas (o copy define) | Who books / Who adjusts when a ride closes / Who decides the order / Your phone time / Cost basis | | | |

  - Cabeçalho de coluna com ícone de linha (user, cpu, ticket, message-circle).
  - Na linha de custo do Premier Pass: "charged per person" [FATO funil]. Sem valor em dólar, ou com data se o copy usar.
  - Para mostrar sim, parcial e não: **ícone + palavra** (✓ Yes / ◐ Partly / ✕ No), nunca só cor.
  - A coluna "Live human strategist" leva só um contorno Lagoon de 2 pt. **Sem "Best choice", "Recommended" nem selo**: o tom é honesto e a coluna DIY é apresentada como válida [FATO funil: "fazer sozinha (válido; dar 3 dicas)"].
- **Abaixo da tabela:** "3 tips if you go DIY" em 3 colunas curtas.
- Palavras proibidas na página: "hack", "bot" como promessa, "skip every line", "VIP", "Disney approved" [FATO funil].

### Página 10: Meet LUMI + CTA
- **Fundo:** metade superior Sand, metade inferior Lagoon (sangria na versão digital).
- **Topo (c1–c8):** H1 "Meet LUMI" + 3 fatos com ícone:
  - "5 years inside the parks" [FATO];
  - "Your must-do list → a 6–7 hour live park day → we text you all day on WhatsApp or text message" [FATO];
  - ícone de cadeado: "We never ask for your Disney password." [FATO regra].
  - "You pay Disney directly" só se o dono confirmar [PREMISSA funil].
- **Foto ou retrato do expert:** não usar rosto se o dono não quiser aparecer [SEM DADO]. Padrão: sem foto, só tipografia.
- **Preço:** espaço reservado de uma linha ("From $200 per park day for up to 3 people"), **visível só se o dono aprovar** [FATO funil: decisão do dono].
- **Depoimentos:** nenhum [FATO]. Não deixar espaço que pareça "faltando depoimento".
- **Bloco CTA (metade Lagoon):**
  - Headline em Sand, DM Serif Display 26 pt: "Got your dates?" + linha do copy ("Text us your dates and group size. We'll tell you honestly if a live park day makes sense for your trip.") [FATO funil].
  - **Dois botões** lado a lado, 200 x 48 pt, cantos de 24 pt, fundo Sand, texto Lagoon Inter SemiBold 15 pt, área de toque de no mínimo 44 x 44 pt:
    - **"Text us"** → link `sms:` [SEM DADO número dos EUA];
    - **"WhatsApp us"** → link `wa.me/` [SEM DADO número].
    - Mensagem pré-preenchida sugerida pelo funil para medir a origem: "Hi LUMI! PREP guide" [FATO funil].
  - **Link secundário** em texto sublinhado Sand, 13 pt: "Not ready to chat? Get a quote by email" → formulário [SEM DADO link].
  - **QR code** de 1,1 pol. (cerca de 80 pt) no mínimo, em módulo escuro sobre quadro branco com margem branca de 4 módulos. Aponta para **uma página curta com os 3 caminhos** (SMS, WhatsApp, formulário), porque um QR só abre um destino [PREMISSA]. URL: [SEM DADO]. Com UTM `utm_source=pdf&utm_medium=qr&utm_campaign=prep_guide` [PREMISSA de nomenclatura; alinhar com dados-metricas].
- Rodapé padrão com o aviso.

### 4.2 Rodapé padrão (páginas 2 a 10)
- Linha fina Slate de 0,5 pt a 0,75 pol. da base.
- Esquerda: aviso de não afiliação (9 pt, Slate).
- Direita: `@[SEM DADO: perfil do Instagram]  ·  2 / 10`.
- Altura total de 24 pt. Não colocar link clicável no rodapé, para evitar toque acidental no celular.

---

## 6. Versão preenchível (campos de formulário)

**Arquivo:** `LUMI-Park-Day-Prep-Guide-fillable.pdf`.

**Ferramenta:** o Canva exporta PDF, mas criar campos de formulário nele é [VERIFICAR] (na nossa referência, não cria). Fluxo sugerido:
1. Diagramar no Canva (ou Figma), exportar "PDF Print" com os links ativos.
2. Adicionar os campos em um editor de PDF com formulários. Opções: Adobe Acrobat (pago, custo [VERIFICAR]) ou ferramentas gratuitas como LibreOffice Draw ou PDFescape [VERIFICAR limites na data].
3. Testar no **Apple Preview / app Arquivos do iPhone, Adobe Acrobat Reader no celular e Google Chrome**. Alguns leitores de celular não preenchem campos [PREMISSA]; por isso a página 4 também precisa funcionar impressa.

| Página | Campo | Tipo | Nome técnico | Dica de acessibilidade (tooltip) |
| --- | --- | --- | --- | --- |
| 3 | Dia da reserva | Texto (data) | `booking_day` | "Your booking day" |
| 3 | Despertador local | Texto | `alarm_local_time` | "Your alarm, local time" |
| 4 | Parque / Data | Texto | `park`, `park_date` | "Park", "Date" |
| 4 | Quem escolheu, linhas 1–10 | Texto | `picked_by_01`…`picked_by_10` | "Who picked it, row 1" |
| 4 | Atração | Texto | `ride_01`… | "Ride, show or experience, row 1" |
| 4 | Nível | **Lista suspensa**: Would cry / Really want / Bonus | `level_01`… | "Level, row 1" |
| 4 | Altura ok? | Lista suspensa: Yes / No | `height_ok_01`… | "Meets height requirement, row 1" |
| 4 | Assusta os pequenos? | Lista suspensa: Yes / No / Maybe | `scary_01`… | "Scary for little ones, row 1" |
| 4 | Top 5 da família | Caixa de marcar | `top5_01`… | "Family Top 5, row 1" |
| 4 | Inegociáveis | Texto multilinha | `non_negotiables` | "Our non-negotiables" |
| 5 | Itens do checklist | Caixas de marcar | `bw_01`…`bw_06` | Texto do item |
| 5 | Quem reserva / Despertador | Texto | `who_books`, `bw_alarm` | idem |
| 6 | Itens do checklist | Caixas de marcar | `pm_01`…`pm_06` | Texto do item |
| 6 | Quem segura o celular / Ponto de encontro | Texto | `phone_holder`, `meeting_spot` | idem |

**Regras dos campos:**
- Fundo do campo Mist, contorno Lagoon de 0,75 pt, fonte Inter 11 pt **fixa** (não "auto", que encolhe o texto até ficar ilegível).
- **Ordem de tabulação** por linha, da esquerda para a direita, de cima para baixo.
- Caixas de marcar com estilo "check" (✓), não "cross".
- Nenhum campo coleta dado sensível (sem senha, sem e-mail, sem cartão).
- Nenhum campo é obrigatório e não há botão "enviar": o arquivo fica só com a mãe.

---

## 7. Versão para imprimir

**Arquivo:** `LUMI-Park-Day-Prep-Guide-print.pdf`.

- **Sem campos de formulário**: linhas para escrever à mão (0,5 pt Slate) e caixas vazias.
- **Fundo branco** em todas as páginas (sem Sand), sem sangria e sem blocos cheios de Lagoon. Capa e página 10 em versão "contorno": título Ink, faixa fina Lagoon. Economiza tinta.
- **Links impressos por extenso**, porque botão não funciona no papel: número de SMS, número de WhatsApp e URL curta do formulário, mais o QR code (obrigatório nesta versão).
- Diagrama: a hachura garante a leitura em **preto e branco**. Testar impressão P&B antes de entregar.
- A página 4 deve caber em uma folha e ter linhas de 30 pt para escrever à mão.
- Opcional: oferecer só as páginas 3 a 6 como "printable worksheets" no e-mail 0 [PREMISSA; o funil decide].

---

## 8. Acessibilidade (WCAG 2.1 AA como mínimo)

| Item | Regra |
| --- | --- |
| Contraste de texto | ≥ 4,5:1 para corpo; ≥ 3:1 só para texto ≥ 18 pt (ou 14 pt bold). Usar a tabela da seção 2.1. **Coral nunca como cor de texto** |
| Contraste de gráfico | ≥ 3:1 para elementos que carregam significado: barras Lagoon (7,2:1) ok; barras Coral têm hachura e contorno Ink para passar |
| Não depender de cor | Prioridade = estrelas + texto; diagrama = sólido x hachurado; tabela de opções = ícone + palavra |
| Tamanho mínimo | Corpo 13 pt; nada essencial abaixo de 11 pt; rodapé com mínimo de 9 pt |
| Área de toque | Botões e campos com no mínimo 44 x 44 pt |
| PDF marcado (tagged) | Exportar com tags; ordem de leitura conferida; títulos marcados como H1/H2; tabelas com cabeçalho marcado |
| Texto alternativo | Em todo diagrama, ícone com significado e QR code ("QR code: opens a page to text or WhatsApp LUMI"). Ícones decorativos marcados como artefato |
| Metadados | Título do documento = título escolhido; autor = LUMI Concierge; idioma = **en-US** |
| Links | Texto do link descritivo ("Text us", não "click here") |
| Movimento e brilho | Nenhum (não se aplica a PDF, mas vale para os posts derivados: sem flash) |

---

## 9. Peças para o Instagram

O funil usa comentário com palavra-chave (PREP / 10AM / PLAN) e DM com o link [FATO funil]. As peças mostram o PDF como objeto real e desejável e trazem o CTA do post.

### 9.1 Feed 1080 x 1350 (4:5)
- **Composição:** fundo Sand. Mockup da capa do PDF levemente inclinado (5 a 8°), com sombra suave, ocupando 60% da altura, mais 2 páginas internas atrás em leque (páginas 4 e 7: a planilha e o diagrama são as mais "vendedoras").
- **Texto:** topo em DM Serif Display, 64 a 72 px, Ink: gancho do post (ex.: "Your next Lightning Lane is 2 hours away?") [FATO funil, Reels 1]. Base em faixa Lagoon com texto Sand de 44 px: **"Comment PREP for the free guide"** (palavra-chave conforme o post).
- **Área segura:** manter texto e o mockup dentro dos **1080 x 1080 centrais**, porque a grade do perfil pode cortar as bordas [VERIFICAR o recorte atual da grade].
- **Aviso:** "Independent guide. Not affiliated with Disney." em 22 a 24 px, Slate, acima da faixa, ou na legenda [FATO funil: aviso na legenda ou na bio].
- **Variação carrossel:** tela 1 = este mockup; telas seguintes = trechos reais das páginas 3 a 7 recortados em 4:5 (o quadro de fuso e o diagrama funcionam sozinhos); última tela = CTA.

### 9.2 Stories e capa de Reels 1080 x 1920 (9:16)
- **Composição:** mockup do PDF aberto num celular segurado na mão (tela do celular mostra a capa do PDF, **nunca** o app da Disney), ou o guia impresso sobre uma mesa de hotel.
- **Zonas seguras:** deixar livres cerca de **250 px no topo e 340 px na base** (barra de perfil, legenda e botões) [PREMISSA de prática comum; VERIFICAR].
- **Texto:** gancho no terço superior (72 a 80 px); CTA "Comment PREP" ou figurinha de link nos Stories no terço inferior, dentro da zona segura.
- **Capa de Reels:** o título precisa ser legível também no recorte 1:1 / 3:4 do perfil; centralizar.

### 9.3 Mockup: como fazer
- **Preferido:** foto real do expert (mesa, mochila, guia impresso) com a capa aplicada [SEM DADO foto].
- **Alternativa sem custo:** mockups de documento do próprio Canva (frames de papel, tablet, celular) [VERIFICAR licença no plano do dono].
- **IA:** só para gerar o **cenário sem texto**. A capa real entra depois no Canva (IA desenha texto errado e pode inventar logos).

### 9.4 Prompts de imagem para IA (cenário, sem texto)

Estrutura do Visual Generator: assunto, estilo, clima, luz, composição, paleta, técnico e negativo. Testados em formato genérico (Midjourney, DALL-E, Flux); ajustar sintaxe por ferramenta.

**Prompt 1: Flat lay "prep night" (feed 4:5)**
> Top-down flat lay on a warm sand-colored linen tablecloth: a blank white printed document (no text, left empty for a mockup), a pencil, a small kids' water bottle, a folded light rain poncho, sunscreen tube without label, a phone face down, a pair of small children's sneakers at the edge. Calm, organized, family-travel mood. Soft natural morning light from the left, gentle shadows. Muted palette of deep teal, warm coral and sand. Editorial lifestyle photography, 50mm, shallow depth of field. Aspect ratio 4:5.
> **Negative:** no text, no logos, no brand names, no castle, no mouse ears, no cartoon characters, no theme park rides, no fireworks, no sparkles, no magic wand, no people's faces.

**Prompt 2: Mão com celular, manhã de hotel (Stories 9:16)**
> Close-up of a woman's hand holding a smartphone with a plain blank light screen (for a mockup), in a bright hotel room in the early morning, a backpack and stroller softly blurred in the background. Feeling: calm and ready, not rushed. Warm golden early light through sheer curtains. Lifestyle photography, vertical framing, phone in the upper-middle third, empty space at the bottom for text. Palette: sand, deep teal accents, warm coral. Aspect ratio 9:16.
> **Negative:** no visible app interface, no logos, no text on screen, no castle, no mouse ears, no characters, no theme park signage, no faces.

**Prompt 3: Fundo abstrato "timeline" (para carrossel e capa)**
> Minimal abstract background of soft horizontal rounded bars in deep teal, with a few diagonal-hatched coral gaps between them, on a warm sand background, lots of empty space, flat vector style, clean editorial design. Aspect ratio 4:5.
> **Negative:** no text, no numbers, no icons, no castle, no characters, no stars or sparkles.

**Regras para imagem de IA:**
- Não gerar pessoas que pareçam "clientes" nem usar a imagem como prova ou depoimento.
- Revisar cada imagem com zoom à procura de orelhas, silhuetas de castelo, logos ou texto escondido antes de usar.
- Política do Instagram sobre rótulo de conteúdo de IA: [VERIFICAR] na data da publicação.

---

## 10. Checklist de entrega para o designer

**Antes de começar**
- [ ] Texto final do copy recebido (`entregas/copy/isca-pdf-park-day-prep-guide.md`). Não diagramar texto final a partir deste briefing.
- [ ] Título escolhido pelo dono (opção 1 ou 2) [SEM DADO].
- [ ] Paleta e fontes aprovadas pelo dono, ou cores, fontes e logo atuais enviados [SEM DADO].
- [ ] Número de SMS (EUA?), número de WhatsApp, link do formulário e URL da página do QR [SEM DADO].
- [ ] Perfil do Instagram para o rodapé [SEM DADO].
- [ ] Decisão sobre preço na página 10 [SEM DADO].

**Diagramação**
- [ ] US Letter, margens de 0,75 / 0,75 / 1 pol., grid de 12 colunas.
- [ ] 10 páginas na ordem da seção 4; rodapé com aviso nas páginas 2 a 10; aviso também na capa.
- [ ] Diagrama da página 7 com hachura, etiqueta "EXAMPLE, NOT A PROMISE" e nenhum horário além de 9:00.
- [ ] Tabela de opções sem nome de concorrente e sem selo "best".
- [ ] Nenhum depoimento, número ou foto de cliente.

**Varredura de proibidos (página por página)**
- [ ] Sem logo, castelo, orelhas, personagens, fontes da Disney, prints do app ou mapas oficiais.
- [ ] Sem "official", "approved", "VIP", "hack", "skip every line".
- [ ] Termos da Disney só em texto corrido, sem estilização.
- [ ] Fotos sem atração reconhecível e sem rosto de terceiros.

**Arquivos**
- [ ] `LUMI-Park-Day-Prep-Guide-fillable.pdf`: campos da seção 6, ordem de tabulação, tooltips, testado em iPhone, Android e desktop.
- [ ] `LUMI-Park-Day-Prep-Guide-print.pdf`: fundo branco, links por extenso, QR, teste de impressão em P&B.
- [ ] Ambos com **menos de 5 MB** [HIPÓTESE funil], fontes incorporadas, PDF marcado, idioma en-US e título nos metadados.
- [ ] Links com UTM testados (SMS abre o app de mensagens no iPhone; wa.me abre o WhatsApp; formulário abre).
- [ ] QR code lido por 2 celulares diferentes, na tela e impresso.
- [ ] Contraste conferido com verificador (ex.: WebAIM Contrast Checker).
- [ ] Arquivo editável (link do Canva ou Figma) entregue ao dono, com as fontes indicadas.

**Instagram**
- [ ] Mockup 1080 x 1350 (feed) e 1080 x 1920 (Stories e capa de Reels), PNG, mais uma versão sem texto para reaproveitar.
- [ ] Uma versão de CTA para cada palavra-chave em uso (PREP / 10AM / PLAN).
- [ ] Texto dentro das áreas seguras; aviso de independência na peça ou na legenda.

---

## 11. Pendências do dono

1. Aprovar ou trocar a paleta e as fontes propostas; enviar logo, se existir [SEM DADO].
2. Escolher o título do PDF (opção 1 ou 2) [SEM DADO].
3. Números de SMS (dos EUA?) e WhatsApp, link do formulário de orçamento e a página de destino do QR [SEM DADO].
4. Perfil do Instagram para o rodapé [SEM DADO].
5. Mostrar ou não o preço na página 10 [SEM DADO].
6. Fotos próprias nos parques (sem personagens e sem rosto de terceiros), e se o expert aparece em foto ou não [SEM DADO].
7. Confirmar "you pay Disney directly" para a página 10 [PREMISSA funil].
8. Avaliação jurídica: uso de "Disney" no título, linha de marcas registradas e prints do app [SEM DADO jurídico].

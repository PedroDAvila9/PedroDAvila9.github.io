# VocalPro — vocalpro.com.br (Renato Max)

## Identificação
- **Title**: **vazio** (`""`) — falha crítica de SEO/social sharing
- **Meta description**: ausente
- **OG tags**: ausentes
- **Generator**: WordPress 6.9.4 (tema Twenty Twenty-One)
- **Builder**: Elementor (não Pro)
- **Checkout**: Hotmart (não exposto direto na home — entra por outro fluxo)

## Tipografia / Visual
- Font body: **system stack** (`-apple-system, system-ui, Segoe UI, Roboto…`) — sem custom font carregada, menos polido
- Background: gradiente roxo/violeta + preto + roxo neon — paleta "gamer/streamer 2020"
- Cores das faixas (referência karatê): branca, amarela, azul, verde, laranja, roxa, marrom, preta — paleta funcional do mecanismo, não decorativa
- Foto do professor (Renato Max) no hero, postura artística
- Estética **YouTube/Instagram creator**, oposta ao tom editorial do SDV

## Estrutura de seções (ordem real, top → bottom)
1. **Hero** — logo "VOCALPRO" + foto do professor + tagline "O melhor curso de canto do Brasil!" + CTA "SAIBA MAIS" (#2)
2. **YouTube embedado: "3 dicas valiosas para sua voz"** — **free value** logo no topo (gancho de retenção, padrão funil de creator)
3. **Headline grande**: "A JORNADA QUE TE ENSINA A CANTAR DE VERDADE!"
4. **Diferencial-mecanismo**: "O curso é de canto mas é dividido em Faixas de Karatê!" — 8 faixas: Branca / Amarela / Azul / Verde / Laranja / Roxa / Marrom / Preta — **gamificação como mecanismo único**
5. **Disclaimer importante**: "Todas as faixas estão inclusas no curso. Você não precisa comprar nada separado!" (antecipa objeção de upsell escondido)
6. **"O que você vai receber"** — bullets + preço destacado **R$ 51,40 em 12x** (R$ 497,00 à vista)
7. **"Achou que tinha acabado? Ainda não!"** — surpresa, **3 masterclasses bônus com convidados nomeados**: Estevão Queiroga, Melk Villar, Sérgio Saas (autoridade emprestada via convidados)
8. **"Ainda tá em dúvida se vale a pena? Então dá uma olhada nos DEPOIMENTOS"** — 5+ vídeos YouTube de depoimentos em vídeo (não texto)
9. **"Adquira o VOCAL PRO agora, antes que acabe a promoção!"** — escassez verbal soft (sem timer, sem contagem)
10. **"GARANTIA INCONDICIONAL DE 07 DIAS"** — reembolso sem perguntas
11. **Suporte WhatsApp** — botão direto
12. **Footer minimalista** — redes sociais (Instagram @renatinhomax)

Total: **15 `<section>`** (a mais enxuta)
Body length: **1.444 chars** — 6x menor que SDV, 6x menor que CnP. **A maior parte do conteúdo está em imagens/vídeos**, não em texto.

## CTAs
- "SAIBA MAIS" (#2 — âncora para a seção)
- "Acesse por aqui!" (login Hotmart para alunos existentes)
- "Suporte" (WhatsApp)
- **Ausência de CTA principal de compra visível no DOM como `<a>`** — provavelmente embebido em imagem clicável ou redirect via JS (mau para acessibilidade e tracking)
- Os 8 "Faixa Branca / Amarela / Azul…" aparecem como botões mas não têm href (parecem tabs/expansores visuais)

## Oferta
- Preço cheio: **não exibido como âncora**
- **R$ 497,00** à vista
- **12x R$ 51,40** (parcelado)
- **Mais barato dos 3 concorrentes** (CnP: R$597 / SDV: R$597 / VocalPro: R$497) — posicionamento de entrada / volume
- Escassez verbal soft ("antes que acabe a promoção")
- Sem timer, sem contador

## Garantia
- **7 dias incondicional** — "sem perguntas"
- Idêntica em duração aos outros 2

## Prova social
- **Vídeos YouTube de depoimentos** (5+ embeds) — pesado em vídeo, leve em texto
- **3 masterclasses bônus com convidados nomeados** (Estevão Queiroga, Melk Villar, Sérgio Saas) — autoridade emprestada via colaboração, não via endorsement
- Instagram @renatinhomax (rede pessoal do professor)
- **Não há prova social numérica** ("X alunos", "Y aprovações")

## Tracking / Stack técnico
- **Facebook Pixel** (ID 410357504915485)
- **Cloudflare Insights**
- **YouTube iFrame API**
- Sem GA, sem Clarity, sem CRM aparente
- Stack **mais simples** dos 3 — sinaliza operação enxuta / dependente de tráfego pago Meta

## Players de vídeo
- **YouTube** — 7 iframes (1 free value + ~6 depoimentos)
- 1 `<video>` nativo (provavelmente background hero)
- Estratégia: vídeo como prova social principal (oposto de texto)

## SEO / Acessibilidade
- **Title vazio** — falha grave (compartilhamento social, indexação)
- **Sem `<h1>`**
- 13 `<h2>` (uso excessivo)
- Sem meta tags
- Conteúdo majoritariamente em imagem (1.4k chars de texto total) — péssimo para SEO orgânico, mas funciona em tráfego pago direto pra checkout

## Gatilhos psicológicos identificados
- **Mecanismo único nomeado**: "Faixas de Karatê" — narrativa de progressão clara, gamificação
- **Free value pré-compra**: 3 dicas em vídeo (antes mesmo de saber preço)
- **Antecipação de objeção**: "todas as faixas inclusas" desarma medo de upsell
- **Autoridade emprestada via convidados**: masterclasses com nomes do nicho
- **Prova em vídeo** (não texto) — alta densidade emocional
- **Escassez verbal soft**: "antes que acabe a promoção"
- **Suporte direto via WhatsApp** — humanização + redução de fricção pré-compra

## Pontos fortes
- **Mecanismo único memorável** (Faixas de Karatê) — diferenciação real, não copiável
- Posicionamento de preço **abaixo do mercado** (R$497 vs R$597) — atrai entrada
- Free value no topo é tática de funil moderna (creator economy)
- WhatsApp direto remove fricção
- Visual coerente com persona do professor (creator/streamer/cantor moderno)
- Antecipação de objeção sobre upsell (raro)

## Pontos fracos
- **Title vazio é uma falha cara** (SEO + sharing)
- Maior parte do conteúdo em imagem — péssimo para a11y e SEO orgânico
- CTA principal de compra não está exposto como `<a>` no DOM (problema de tracking, a11y, performance percebida)
- Sem font customizada — quebra a percepção de qualidade visual
- Sem prova social numérica explícita ("X alunos")
- Stack analítico fraco (só FB Pixel + CF Insights)
- Tipografia genérica (system stack) destoa do esforço visual do background

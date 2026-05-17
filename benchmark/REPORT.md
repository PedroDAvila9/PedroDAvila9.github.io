# Benchmark — LPs de Curso de Voz/Canto

**Data**: 2026-05-16
**Sites analisados**: cantonapratica.com.br · leonardogoncalves.com.br/sdv-tecnica-vocal-ig · vocalpro.com.br
**Método**: cruzamento de screenshot full-page (desktop 1440×900 + mobile 390×844) + inspeção de DOM via Chrome DevTools MCP
**Objetivo**: extrair padrões de conversão e arquitetura de informação aplicáveis à Mellodia da Voz, mantendo diferenciação real

---

## 1. Resumo executivo

| Site | Posicionamento em 1 frase | Preço à vista | 12x | Garantia |
|---|---|---|---|---|
| **Canto na Prática** | "Cante com segurança e emocione quem te ouve" — método para iniciantes via consciência vocal | R$ 597 | R$ 61,74 | 7 dias incondicional |
| **SDV (Leonardo Gonçalves)** | "Técnica vocal pelo método Sentido da Voz" — curso NÃO-introdutório, autoridade artística premium | R$ 597 | R$ 61,74 | 7 dias incondicional |
| **VocalPro (Renato Max)** | "A jornada que te ensina a cantar de verdade" — progressão por faixas de karatê (gamificação) | R$ 497 | R$ 51,40 | 7 dias incondicional |

**Convergência total**: preço de mercado entre **R$ 497–597 / 12x ≈ R$ 50–62**, garantia de **7 dias incondicional**, checkout via **Hotmart/Eduzz**, WordPress + Elementor como stack dominante, **Facebook Pixel** em todos.

**Divergência**: visual (saturado/genérico vs editorial vs creator), estrutura de prova social (volume vs autoridade emprestada vs vídeos), nível de gamificação (zero vs zero vs 8 faixas).

---

## 2. Tabela comparativa cross-site

| Critério | Canto na Prática | SDV (Leonardo G.) | VocalPro |
|---|---|---|---|
| **Hero headline** | "VOCÊ REALMENTE QUER CANTAR COM SEGURANÇA E EMOCIONAR QUEM TE OUVE?" (pergunta retórica agressiva) | "TÉCNICA VOCAL — pelo método sentido da voz" (substantivo + mecanismo) | "A JORNADA QUE TE ENSINA A CANTAR DE VERDADE!" (afirmação aspiracional) |
| **Hero CTA principal** | "SIM, QUERO ME MATRICULAR!" (verde lime) | "QUERO ME MATRICULAR" (outline branco) | "SAIBA MAIS" (#2 — leva pro free value) |
| **Vídeo do hero** | Vimeo VSL fechado (522644478) com "APERTE O PLAY" + seta vermelha | YouTube com aula completa real (free value) | YouTube com "3 dicas valiosas" (free value) |
| **Tipo de oferta** | Promoção riscada R$1297 → R$597 | Apenas R$597 (sem âncora de preço cheio) | R$497 sem âncora, com aviso "antes que acabe a promoção" |
| **Prova social principal** | "+10 mil alunos" + faixa de fotos sem nome | **Endorsements**: Bruno Cardoso, Thiaguinho, Ton Carfi | Vídeos YouTube de depoimentos (5+) |
| **Mecanismo único** | "Consciência Vocal" (genérico) | "Sentido da Voz" (autoral, conecta com discografia do artista) | "Faixas de Karatê" (gamificação visual, único) |
| **Nº de `<section>`** | 39 (Elementor inflado) | 30 | 15 (mais enxuta) |
| **Body text length** | 8.9k chars | 6.6k chars | **1.4k chars** (maior parte em imagens) |
| **Builder** | WordPress 6.9.4 + Elementor Pro | WordPress 6.9.4 + Elementor Pro + Happy/Exclusive/Essential addons | WordPress 6.9.4 + Elementor |
| **Checkout** | Eduzz | Hotmart | Hotmart (não exposto na home) |
| **Stack analítico** | FB Pixel | FB Pixel + GA4 + Microsoft Clarity + ActiveCampaign | FB Pixel apenas |
| **CTA flutuante** | WhatsApp (canto inferior) | Não | WhatsApp (suporte) |
| **`<h1>`** | **0** | 2 (TÉCNICA VOCAL + ATENÇÃO) | **0** |
| **Meta description** | Ausente | Ausente | Ausente |
| **OG tags** | Ausente | Ausente | Ausente |
| **Title** | "Canto na pratica" (sic) | "leonardo gonçalves \| técnica vocal \| SDV…" | **""** (vazio) |
| **Tipografia** | Inter (genérica) | **Playfair Display** (serifa editorial) | system-ui (genérica) |
| **FAQ** | 6 perguntas (sem `<details>`) | 12 perguntas (sem `<details>`) | Ausente |

---

## 3. Padrões recorrentes (= o que o mercado espera)

Padrões presentes em 3/3 ou 2/3 dos sites — esses são os **mínimos para parecer legítimo nesse nicho**:

1. **Hero com vídeo** (3/3) — VSL fechada ou free value embedado, sempre acima da dobra
2. **Garantia incondicional de 7 dias** (3/3) — texto enfático "sem letras miúdas / sem perguntas"
3. **Faixa de preço ~R$ 500–600 / 12x ≈ R$ 50–62** (3/3) — convergência de mercado
4. **Estrutura DOR → MÉTODO → MÓDULOS → PROVA → GARANTIA → PREÇO → FAQ** (2/3) — narrativa de info-produto clássica
5. **Mecanismo nomeado** (3/3) — todos batizam o método com um nome (Consciência Vocal / Sentido da Voz / Faixas de Karatê)
6. **CTA repetido 4–5x ao longo do scroll** (3/3) — múltiplas oportunidades de conversão
7. **Bio/foto do professor** (3/3) — humanização e autoridade
8. **Bônus listados** (3/3) — aumenta valor percebido sem mexer no preço
9. **FAQ ao final** (2/3) — antecipa objeções e segura quem chegou perto de comprar
10. **Checkout via Hotmart/Eduzz** (3/3) — infraestrutura padrão de info-produto BR
11. **Facebook Pixel** (3/3) — sinal universal de operação dependente de Meta Ads
12. **CTA com copy em primeira pessoa** (2/3) — "SIM, QUERO…" / "ESTE CURSO É PARA MIM"
13. **3 perfis de público** (3/3) — não excluir ninguém, mas dar âncora de identificação

---

## 4. Anti-padrões e clichês (= o que torna esse tipo de LP genérica)

Erros recorrentes que dão a sensação de "já vi mil dessas":

1. **Seta vermelha + "APERTE O PLAY"** sobre o vídeo do hero (CnP) — visual datado, estética 2018
2. **Verde lime / cores neon saturadas** sobre azul-escuro (CnP) — paleta info-produto de massa, cansa após scroll
3. **Title page vazio ou minúsculo sem cuidado** (VocalPro tem `""`; CnP tem `"Canto na pratica"` sem capitalize) — falha técnica visível
4. **Ausência total de meta description e OG tags** (3/3) — o link compartilhado no WhatsApp/Instagram fica feio, perde CTR
5. **Conteúdo majoritariamente em imagem** (VocalPro: 1.4k chars de texto) — péssimo para a11y, SEO e leitores de tela
6. **CTAs com `href="#123"` quebrado** (CnP) — bug visível para qualquer auditoria
7. **Prova social como número redondo sem auditoria** ("+10 mil alunos") — soa inflado
8. **Depoimentos sem nome+foto+resultado mensurável** — vira ruído
9. **Hero "VOCÊ REALMENTE QUER…"** (pergunta retórica agressiva) — combina mal com público de voz profissional, soa coach barato
10. **Repetição do hero/oferta no rodapé** (CnP) — sintoma de Elementor sendo usado como builder de conversão por força bruta
11. **Promoção "antes que acabe" sem deadline real** (VocalPro) — escassez fake corrói confiança
12. **Estética coach motivacional**: setas, emojis em headlines, exclamações duplas
13. **Sem font customizada** (VocalPro) — sinaliza descuido em produto premium

---

## 5. Análise por site

### 5.1 Canto na Prática

**Veredito**: arquitetura clássica, bem testada para tráfego pago iniciante. Visualmente datado, tecnicamente sofrível.

**Pontos fortes**:
- CTA verbal forte ("SIM, QUERO ME MATRICULAR!" em primeira pessoa)
- Oferta clara, repetida, com ancoragem de preço (riscado/promoção)
- Garantia tratada como bloco visual com peso

**Pontos fracos**:
- Sem `<h1>` (problema sério de SEO/a11y)
- Sem meta tags básicas
- 3 CTAs apontam para `#123` (link quebrado)
- Visual saturado, paleta verde lime cansa
- "+10 mil alunos" sem qualquer prova
- Vimeo VSL fechado em vez de free value (perde oportunidade de qualificar)

**Lição transferível**: ancoragem de preço (de R$X por R$Y) ainda funciona quando combinada com garantia agressiva.

### 5.2 SDV — Leonardo Gonçalves

**Veredito**: a LP mais sofisticada das 3, **com a melhor decisão estratégica** (posicionamento por filtro + autoridade emprestada).

**Pontos fortes**:
- **Tipografia Playfair Display** estabelece tom premium em 1 segundo
- **Filtro de público** ("ATENÇÃO: NÃO é cursinho introdutório") eleva valor percebido por exclusão
- **Aula completa embedada como free value** — quebra ceticismo sem precisar prometer
- **Endorsements de cantores famosos do nicho** (Bruno Cardoso, Thiaguinho, Ton Carfi) — autoridade emprestada de alto nível
- **3 CTAs com copy contextualizada** ao estágio do scroll (não um único refrão)
- Stack analítico maduro (GA4 + Clarity + ActiveCampaign) — operação séria
- Assinatura em lowercase como gesto de marca (coerente em tudo)

**Pontos fracos**:
- Sem meta description e OG tags (perda em sharing)
- 2 `<h1>` (tecnicamente errado)
- Hero é texto puro — pode ser frio para tráfego frio
- Preço idêntico ao CnP — sem diferenciação por valor numérico (depende de marca)

**Lição transferível**: **diferenciação real está em filtrar público, não em prometer transformação universal**. Curso premium ganha autoridade ao recusar parte do mercado.

### 5.3 VocalPro

**Veredito**: aposta mais alta em mecanismo único (faixas de karatê) e em vídeo como prova. Falha grave em fundamentos técnicos (title vazio).

**Pontos fortes**:
- **Mecanismo único memorável** (8 faixas de karatê) — gamificação que cria sensação de progresso e justifica volume de conteúdo
- **Free value no topo** ("3 dicas valiosas") — funil moderno de creator
- **Antecipação de objeção sobre upsell**: "todas as faixas inclusas, não precisa comprar nada separado" (raro e inteligente)
- **WhatsApp direto** remove fricção pré-compra
- **Preço abaixo do mercado** (R$497) — posicionamento de entrada
- **Convidados em masterclasses bônus** como autoridade emprestada (Estevão Queiroga, Melk Villar, Sérgio Saas)

**Pontos fracos**:
- **Title vazio** — falha grave de SEO e sharing
- Conteúdo 90% em imagem — péssimo SEO/a11y
- CTA principal de compra não está exposto como `<a>` no DOM
- Sem font customizada
- Sem prova social numérica
- Sem `<h1>`
- Estética "gamer/streamer" pode afastar público adulto profissional

**Lição transferível**: **um mecanismo único nomeado e visualizável** (não só "4 pilares") cria diferenciação narrativa que copy genérica nunca atinge.

---

## 6. Recomendações para Mellodia da Voz

Para cada padrão observado, decisão explícita: **alinhar** (vale seguir), **subverter** (a diferenciação está em não fazer), **ignorar** (não se aplica ao público de voz profissional).

### 6.1 Posicionamento e narrativa

| Padrão observado | Decisão Mellodia | Por quê |
|---|---|---|
| Hero como pergunta retórica agressiva ("VOCÊ REALMENTE QUER…") | **Subverter** | Público adulto profissional rejeita coach barato. Manter o tom afirmativo atual ("Sua voz é seu ativo. Trate-a como tal.") — mas reforçar com prova visual (ver abaixo) |
| Filtro de público explícito ("NÃO é cursinho introdutório") — SDV | **Alinhar (adaptado)** | Em vez de filtrar por nível técnico, **filtrar por uso profissional**: "Este não é um curso de canto recreativo. É para quem trabalha com voz." — eleva valor e seleciona avatar |
| Mecanismo único nomeado (Sentido da Voz / Faixas de Karatê / Consciência Vocal) | **Alinhar** | "4 pilares" é fraco. Batizar o método: ex. **"Método Mellodia"** ou **"Protocolo das 4 Camadas"** (Diagnóstico → Técnica → Aplicação → Saúde) com nome próprio |
| 3 perfis de público com peso igual | **Alinhar com diferenciação visual** | Manter 3 cards (oradores/podcasters/artistas) mas com **trilha sugerida diferente** em cada — mostra customização real |
| "Mais X mil alunos" como prova de volume | **Subverter** | Sem volume real, mentir queima. Substituir por **prova de qualidade**: 1–3 depoimentos com **resultado mensurável** ("Aumentei 4 semitons em 6 semanas") + **trecho de áudio antes/depois** se possível |

### 6.2 Prova social — onde o Mellodia mais precisa subir

A LP atual ([index.html](/Users/pedrodasilvadavila/projetcs/personal-projetcs/mellodia-course/index.html)) tem 3 cards de depoimento com placeholder `[?]`. Substituir por:

| Camada | Recomendação | Inspirado em |
|---|---|---|
| **Endorsements** | 2–3 nomes reconhecidos no nicho de voz profissional (jornalista, locutor, podcaster popular, palestrante TEDx) com foto e citação curta | SDV (Bruno Cardoso, Thiaguinho) |
| **Áudio antes/depois** | Player nativo `<audio>` com 10s antes / 10s depois de cada aluno — **prova auditiva diferencial** que NENHUM concorrente usa, e que é a coisa óbvia para um curso de voz | Inédito no benchmark |
| **Resultados mensuráveis** | "Aumentei 4 semitons", "Eliminei rouquidão pós-evento", "Subi retenção do meu podcast em 22%" — números, não adjetivos | — |
| **Depoimento em vídeo curto** | 1 vídeo de 30s embedado (não 5+) | VocalPro (mas em quantidade menor, sem poluir) |

### 6.3 Hero — onde a Mellodia tem oportunidade de ser memorável

A LP atual tem hero **puramente textual** com badge + h1 + p + 2 CTAs + stats. Risco: parece "página de SaaS" porque não tem **nenhum elemento sonoro/vocal** — ironia em um curso DE VOZ.

**Recomendação**:
- Manter headline atual ("Sua voz é seu ativo. Trate-a como tal.")
- Adicionar **um elemento sonoro ativo no hero**: player de áudio com 15–20s de trecho do professor (não vídeo — som puro é mais distintivo e leve)
- Ou alternativa: **onda de áudio animada em SVG** ligando a tagline ao CTA, como ornamento visual + assinatura sonora simbólica
- Stats atuais (+10 anos / 3 nichos / 100% online) são genéricos — substituir por **"escute uma aluna real" / "escute o método" / "escute o resultado"** com 3 players

### 6.4 Mecanismo — nomear melhor

A LP atual lista 4 pilares sem nome ("Diagnóstico vocal", "Técnica fundamental", "Aplicação real", "Saúde vocal"). Decisão: **alinhar com SDV** dando nome próprio ao método.

**Sugestões a discutir**:
- "Método Mellodia das 4 Camadas"
- "Protocolo Mellodia" com pilares numerados 01–04 (mantém estrutura, ganha identidade)
- Cada pilar com **verbo no infinitivo**: Diagnosticar / Construir / Aplicar / Sustentar

### 6.5 Free value pré-compra (gancho de funil)

Padrão dos 3 concorrentes: hero tem vídeo. CnP usa VSL fechada (pior), SDV e VocalPro usam **free value** (melhor).

**Recomendação**: adicionar seção **antes do investimento** com **1 aula completa gratuita** (10–15 min) embedada do YouTube. Quebra ceticismo + qualifica lead + alimenta canal do YouTube em paralelo.

### 6.6 Oferta

A LP atual tem ancoragem (de R$ 1.997 → 12x R$ 97) — **bem feito, manter**. Mas:

| Item | Decisão | Detalhe |
|---|---|---|
| Âncora de preço (R$1997 → R$997) | **Alinhar (manter)** | Já existe no index.html, é padrão de mercado eficaz |
| "Oferta de lançamento" sem deadline | **Subverter (ou definir prazo real)** | Frase atual ("Oferta de lançamento") é vaga. Ou colocar **deadline concreto** ("até 30/06") ou remover — escassez fake corrói confiança |
| Bônus com âncora de valor (+R$ 297) | **Alinhar (manter, já existe)** | Padrão eficaz, presente nos 3 concorrentes |
| Preço base R$ 997 vs mercado R$ 497–597 | **Avaliar** | Mellodia é 67% mais caro que VocalPro. Justifica via **público diferente** (voz profissional, não canto recreativo). Manter, mas tornar a justificativa visível no copy ("custa mais porque entrega contexto profissional, não dicas de YouTube") |

### 6.7 CTAs

A LP atual tem 5 CTAs com 3 copys diferentes ("Quero o método", "Quero dominar minha voz", "Garantir minha vaga agora", "Quero começar agora"). **Já está bem**, alinhada com SDV.

**Manter** a variação contextual + sticky mobile (que nenhum concorrente tem — é vantagem técnica real).

### 6.8 Trust & técnico

| Item | Mellodia atual | Decisão |
|---|---|---|
| `<title>` rico com keyword | ✅ tem | Manter |
| `<meta description>` | ✅ tem | Manter |
| `og:title` + `og:description` + `og:image` | ✅ tem | Manter (vantagem real sobre os 3 concorrentes) |
| `<h1>` único | ✅ tem | Manter |
| Favicons + apple-touch-icon | ✅ tem | Manter |
| Sticky CTA mobile | ✅ tem | Manter (nenhum concorrente tem) |
| FAQ semântico com `<details>` | ✅ tem | Manter (Mellodia é o **único** com `<details>` — todos os 3 concorrentes usam div+JS) |
| WhatsApp visível | ❌ não tem | **Adicionar** botão flutuante de suporte WhatsApp (presente em 2/3 concorrentes) |
| Footer com links reais | ❌ vazios (`href="#"`) | Definir destino antes de publicar |

### 6.9 O que **não** copiar (anti-padrões)

- Setas vermelhas, "APERTE O PLAY", emojis em headlines, exclamações duplas
- Verde lime / cores neon saturadas em CTA (o cyan atual já é suficientemente vibrante sobre preto)
- Contador regressivo falso
- Repetição do hero no rodapé
- Conteúdo em imagem
- Estética coach motivacional

---

## 7. Síntese prioritária (top 8 para a v2)

Ordem de impacto/esforço para a `index-v2.html`:

1. **Áudio no hero** — player com trecho do professor ou aluno (15–20s) substituindo/complementando o badge atual
2. **Filtro de público explícito** logo após o hero — "Este não é um curso de canto recreativo"
3. **Nomear o método** com identidade — "Protocolo Mellodia das 4 Camadas" (ou similar)
4. **Free value embedado** antes do investimento — 1 aula completa gratuita (10–15 min)
5. **Áudio antes/depois nos depoimentos** — diferencial inédito no nicho
6. **WhatsApp flutuante** para suporte pré-compra
7. **Endorsements de nomes do nicho** (não influencer genérico) — 1–3 citações com foto e perfil
8. **Deadline real da oferta** ou remover "lançamento" — não deixar escassez vaga

Cada decisão da `index-v2.html` deve rastrear de volta a um item desta lista.

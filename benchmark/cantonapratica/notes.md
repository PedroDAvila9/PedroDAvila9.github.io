# Canto na Prática — cantonapratica.com.br

## Identificação
- **Title**: "Canto na pratica" (sic, sem capitalize, sem complemento)
- **Meta description**: ausente
- **OG tags**: ausentes (sem og:title, og:description, og:image)
- **Generator**: WordPress 6.9.4
- **Builder**: Elementor Pro 3.31.2
- **Checkout**: Eduzz (chk.eduzz.com/730092)

## Tipografia / Visual
- Font body: `Inter, sans-serif`
- Background: branco (`rgb(255,255,255)`) com seções pretas/azul-escuro intercaladas
- CTA dominante: verde lime saturado (#7CFC00-ish) sobre azul-escuro — alta voltagem visual, padrão "info-produto Hotmart 2018"
- Apelos visuais: setas vermelhas grandes apontando para botão de play do VSL, "APERTE O PLAY" em texto destacado

## Estrutura de seções (ordem real, top → bottom)
1. **Hero VSL** — pergunta provocativa: "VOCÊ REALMENTE QUER CANTAR COM SEGURANÇA E EMOCIONAR QUEM TE OUVE?" + vídeo Vimeo + CTA verde lime "SIM, QUERO ME MATRICULAR!" + oferta "DE R$1297 POR 12x R$61,74 OU R$597 À VISTA" logo abaixo
2. **"O que é o Curso Canto na Prática?"** — apresentação do produto
3. **"Se você está cansado por não ter o controle da sua voz, você está no lugar certo!"** — dor/identificação
4. **"VOCÊ NÃO ESTÁ SOZINHO!"** — 3 cards: Aulas Práticas / Acompanhamento Online / Suporte Diferenciado
5. **"TALVEZ VOCÊ JÁ ESTEJA NA ESTRADA E JÁ CANTA HÁ ALGUM TEMPO"** — segundo perfil de público
6. **"O Grande segredo... está na Consciência Vocal"** — diferencial/método: 3 pilares (Base Vocal / Elementos Interpretativos / Acompanhamento)
7. **"QUANTAS PESSOAS JÁ CONFIARAM NOS MEUS TREINAMENTOS"** — "+ de 10 mil alunos" + faixa de fotos de alunos
8. **"CONFIRA OS MÓDULOS DO CURSO"** — 3 módulos: A Base Vocal / Cante com Técnica / Surpreenda e Emocione
9. **Bônus** — texto longo descrevendo cada bônus
10. **"Pra quem é o curso / Será que serve para mim?"** + **"SIM, então o canto na prática é para você"**
11. **"QUANTO CUSTA ESSE PACOTE COMPLETO..."** — bloco de preço/oferta principal
12. **Garantia** — 7 dias incondicional, reembolso por email
13. **"Benefícios do Curso"** — lista
14. **FAQ** — 6 perguntas (acordeon-like, não usa `<details>`)
15. **CTA final** — repetição do hero+oferta (bloco hero duplicado no rodapé)

Total: **39 `<section>` tags** (Elementor infla a contagem)

## CTAs
- Texto único repetido: **"SIM, QUERO ME MATRICULAR!"** (em primeira pessoa, gatilho de comprometimento)
- 5 instâncias na página
- Destinos misturados: 3 com `href="#123"` (âncora quebrada — provável bug), 2 apontando para `https://chk.eduzz.com/730092?utm_source=home` (checkout real)
- Sem CTA flutuante / sem botão fixo no scroll
- WhatsApp visível como botão flutuante (canto inferior direito)

## Oferta
- Preço cheio (riscado): **R$ 1.297**
- Preço promocional: **R$ 597** à vista
- Parcelado: **12x R$ 61,74**
- Sem escassez explícita (sem contador, sem "X vagas")
- Sem upsell/order bump visível na LP

## Garantia
- **7 dias incondicional**
- Texto enfático: "Aqui não tem letra miúda"
- Reembolso por email simples (cantonapratica@gmail.com)

## Prova social
- "+ de 10 mil alunos" (número redondo, sem auditoria)
- Faixa de fotos de alunos (sem nome/depoimento textual nessa faixa)
- 2 vídeos Vimeo embedados (provável VSL hero + depoimento/aula demo)
- **Não há depoimentos textuais com nome+foto+resultado**

## Tracking / Stack técnico
- **Facebook Pixel** (ID 2157336198418172) + openbridge
- **Pixel Your Site** (plugin WP) + Handl UTM Grabber
- WordPress core + jQuery 3.7.1
- Elementor Pro + sticky plugin
- Sem GA4 visível, sem GTM, sem Hotjar
- Stack típico de info-produto pago no Facebook/Instagram

## Players de vídeo
- Vimeo (não-VTurb, não-Panda) — 2 iframes
- Provável VSL no hero (vídeo 522644478) + vídeo secundário (675316657)

## SEO / Acessibilidade
- **Nenhum `<h1>` na página** (problema sério de SEO + a11y)
- 23 `<h2>` (uso excessivo)
- Sem meta description, sem OG
- Title minúsculo
- Total de texto no body: ~8.9k chars (denso)

## Gatilhos psicológicos identificados
- **Provocação inicial**: pergunta retórica que cria desconforto ("VOCÊ REALMENTE QUER...")
- **Identificação dupla**: 2 perfis (iniciante + quem já canta) — não exclui ninguém
- **Autoridade por volume**: "+10 mil alunos"
- **Garantia removendo risco**: "incondicional, sem letra miúda"
- **Comprometimento via copy do botão**: "SIM, QUERO ME MATRICULAR!" (primeira pessoa = projeção de identidade)
- **Repetição do hero no fim**: dupla chance de conversão

## Pontos fortes
- Copy de CTA em primeira pessoa é forte
- Oferta clara e visível em múltiplos pontos
- Estrutura clássica testada (dor → método → módulos → garantia → FAQ)

## Pontos fracos
- Visual saturado/agressivo data o produto (parece 2018)
- Ausência de `<h1>` e meta tags básicas
- CTAs com `href="#123"` quebrado em 3 instâncias
- Prova social sem profundidade (sem depoimento textual com nome+resultado)
- Sem diferenciação clara do método (3 pilares são genéricos: base/técnica/acompanhamento)
- Cor verde lime cansa visualmente após scroll

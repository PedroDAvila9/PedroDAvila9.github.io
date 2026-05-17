# Mellodia da Voz — Landing Page

Curso de canto online com técnica vocal aplicada — do iniciante ao cantor que ornamenta com melismas e improvisa.

## Stack

- **HTML estático** + **Tailwind CSS via CDN**
- **Google Fonts**: Inter + Montserrat
- **Hospedagem**: GitHub Pages (estático, gratuito, HTTPS automático)
- Sem build step. Edita e publica.

## Estrutura

```
mellodia-course/
├── index.html          # versão atual (publicada em /)
├── index-v1.html       # versão inicial (preservada — acessível em /index-v1.html)
├── assets/
│   ├── images/         # logo, og-image
│   ├── favicons/       # favicons em vários tamanhos
│   └── audio/          # samples de áudio do hero/depoimentos (a adicionar)
├── benchmark/          # estudo dos concorrentes — REPORT.md + screenshots
├── CNAME               # domínio customizado (mellodia.live)
└── README.md
```

## Como rodar localmente

```bash
python3 -m http.server 5173
# abre em http://localhost:5173
```

## Posicionamento

- **Quem é o curso para**: cantores — do iniciante ao avançado
- **Diferenciais técnicos**: módulo dedicado a registro e passagem (peito/mix/cabeça), belting saudável, e um módulo inteiro de ornamentação (melismas, riffs and runs, apogiaturas)
- **Identidade visual**: dark (#000) + cyan neon (#0FFFFF), Montserrat para display, Inter para corpo

## TODOs antes de ir ao ar (busque por `[` no `index.html`)

- [ ] **Áudios do hero e depoimentos** — gravar e colocar em `assets/audio/`
  - `hero-sample.mp3` — 15-20s do professor
  - `d1-antes.mp3`, `d1-depois.mp3` — depoimento 1
  - `d2-antes.mp3`, `d2-depois.mp3` — depoimento 2
  - `d3-antes.mp3`, `d3-depois.mp3` — depoimento 3
- [ ] **Aula gratuita** — substituir o `?v=dQw4w9WgXcQ` no iframe `#aula` pelo ID real do YouTube
- [ ] **Endorsements** — nomes reais + foto + perfil
- [ ] **Depoimentos** — nome real + foto + @perfil
- [ ] **Professor** — nome, bio, foto
- [ ] **Link Hotmart** — `#cta-checkout` (há snippet pronto no `<script>` final)
- [ ] **WhatsApp** — número real no link da `.wa-float`
- [ ] **Preço real** + **deadline real** na seção `#investimento`
- [ ] **Links footer**: Instagram/YouTube/TikTok + Termos + Política

## Benchmark

Estudo dos 3 principais concorrentes (cantonapratica · SDV/Leonardo Gonçalves · VocalPro) com screenshots, copy extraída do HTML e recomendações específicas para a Mellodia: [benchmark/REPORT.md](benchmark/REPORT.md).

## Deploy

Site hospedado em **GitHub Pages** com domínio customizado `mellodia.live` (via [GitHub Student Developer Pack](https://education.github.com/pack)).

### Como o deploy funciona

1. Push para `main` → GitHub Pages publica em segundos
2. Settings → Pages: source = `main` / root
3. DNS do `mellodia.live` aponta para `<seu-usuario>.github.io` via CNAME
4. HTTPS automático (Let's Encrypt via GitHub)

## Versionamento

- `index.html` — versão pós-benchmark (publicada)
- `index-v1.html` — versão inicial (preservada para histórico)

Toda mudança de copy/estrutura significativa: commitar com mensagem descritiva. Para grandes redesigns, criar `index-vN.html` antes de sobrescrever.

# Sintra Labs — Site Institucional — Handoff para Opus

## O que é

Site institucional da **Sintra Labs** (sintralabs.com.br). Empresa que desenvolve soluções de IA para negócios — o principal produto é o Sintra Flow (atendimento via WhatsApp com IA).

## Stack

- HTML/CSS/JS puro — arquivo único `index.html`
- Fonte: Google Fonts (Plus Jakarta Sans)
- Sem framework, sem build step
- Repositório: `C:\sintra`

## Estrutura de arquivos

```
sintra/
├── index.html          # Site completo (único arquivo de código)
├── rafaelresolução.png # Foto do Rafael (fundador/dev)
├── matheus.jpeg        # Foto do Matheus (equipe)
└── vinicius.jpeg       # Foto do Vinicius (equipe)
```

## Design

- **Tema:** dark, moderno, tech
- **Paleta:**
  - Background: `#050810` / `#080d18` / `#0c1428`
  - Azul principal: `#1d6bfe`
  - Ciano: `#5ba8ff`
  - Verde: `#4ade80`
  - Texto: `#eef2ff` / `#7b8fc4`
- **Tipografia:** Plus Jakarta Sans (300–800)
- **Favicon:** SVG inline — logo da Sintra Labs (polígonos branco + azul)
- Estilo: minimalista, corporativo tech, inspirado em SaaS modernos

## Contexto da empresa

**Três sócios:**
- **Rafael** — produto, design e operações (dev principal)
- **Matheus** — administração, financeiro e contabilidade
- **Vinicius** — comercial, vendas e jurídico (formação em Direito)

**Produto principal:** Sintra Flow (SaaS de atendimento WhatsApp com IA)  
**Outros serviços:** automação, presença digital, soluções com IA  
**Foco geográfico inicial:** Belo Horizonte e região metropolitana  
**Clientes em portfólio:** InPrint (`inprint-site.vercel.app`), Alegria Decora Festas  
**Planos de serviço:** Start, Pro, Smart (em definição)

## Notas importantes

- Site estático, deploy simples (GitHub Pages, Netlify, ou similar)
- Qualquer alteração é só editar o `index.html` e commitar
- As fotos da equipe (`rafaelresolução.png`, `matheus.jpeg`, `vinicius.jpeg`) são referenciadas diretamente no HTML
- O favicon é SVG inline na tag `<link>` — não precisa de arquivo separado

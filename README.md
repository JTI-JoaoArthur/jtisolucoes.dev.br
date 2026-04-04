# jtisolucoes.dev.br

Site institucional da **JTI Soluções** — empresa de tecnologia focada em desenvolvimento de software, segurança digital e infraestrutura de TI para empresas do DF, Goiás e Minas Gerais.

**Live:** [jtisolucoes.dev.br](https://jtisolucoes.dev.br)

---

## Stack

HTML, CSS e JavaScript puro. Sem framework, sem bundler, sem dependência de build. Hospedado via **Cloudflare Pages** com CDN global, proteção DDoS e analytics integrado.

Única dependência externa: [Devicon](https://devicon.dev/) (ícones de tecnologias via CDN).

## Estrutura

```
├── index.html                 # Landing page principal
├── desenvolvimento.html       # Página de serviço: sites, apps, sistemas
├── seguranca.html             # Página de serviço: segurança e backup
├── infraestrutura.html        # Página de serviço: suporte e infra
├── politica-privacidade.html  # LGPD
├── termos-de-uso.html         # Termos legais
├── 404.html                   # Página de erro personalizada
├── style.css                  # CSS único compartilhado
├── manifest.json              # Web manifest (PWA)
├── sitemap.xml                # Sitemap para indexação
└── assets (imagens)
    ├── hero-ecosystem.png     # Hero da landing (fundo transparente)
    ├── sobre.jpg              # Seção Sobre (wireframes + MacBook)
    ├── og-image.jpg           # OG image para compartilhamento social
    ├── brasao*.jpg/png        # Variações do logo
    └── favicon.png            # Favicon 64x64
```

## Formulário de contato

Integrado via [Web3Forms](https://web3forms.com/) — envio client-side sem backend. Os formulários existem na landing e em cada página de serviço, com validação em tempo real (email e telefone brasileiro) e envio AJAX sem redirecionamento.

## Deploy

`npx wrangler pages deploy . --project-name jtisolucoes-dev-br --branch main`

O domínio `jtisolucoes.dev.br` aponta via CNAME para `jtisolucoes-dev-br.pages.dev`. DNS gerenciado pelo Cloudflare com nameservers `brenna.ns.cloudflare.com` e `tadeo.ns.cloudflare.com`. SSL automático.

## SEO

- Schema.org LocalBusiness (JSON-LD) na index
- Meta tags Open Graph em todas as páginas
- Sitemap XML com todas as páginas públicas
- Canonical URLs nas páginas de serviço
- `robots: noindex` nas páginas legais

## Responsivo

Breakpoints em 576px (mobile), 768px (tablet) e 992px (desktop). Menu sanduíche com slide-in lateral e glassmorphism abaixo de 576px.

## Contato

- **WhatsApp:** (61) 99291-7593
- **Email:** jti.solucoes@outlook.com
- **Site:** [jtisolucoes.dev.br](https://jtisolucoes.dev.br)

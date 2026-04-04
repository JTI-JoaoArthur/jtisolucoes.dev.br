# jtisolucoes.dev.br

Site institucional da **JTI Soluções** — empresa de tecnologia focada em desenvolvimento de software, segurança digital e infraestrutura de TI para empresas do DF, Goiás e Minas Gerais.

**Live:** [jtisolucoes.dev.br](https://jtisolucoes.dev.br)

---

## Stack

HTML, CSS e JavaScript puro. Sem framework, sem bundler, sem dependência de build. Hospedado via GitHub Pages com domínio customizado.

Única dependência externa: [Devicon](https://devicon.dev/) (ícones de tecnologias via CDN).

## Estrutura

```
├── index.html                 # Landing page principal
├── desenvolvimento.html       # Página de serviço: sites, apps, sistemas
├── seguranca.html             # Página de serviço: segurança e backup
├── infraestrutura.html        # Página de serviço: suporte e infra
├── politica-privacidade.html  # LGPD
├── termos-de-uso.html         # Termos legais
├── style.css                  # CSS único compartilhado
├── sitemap.xml                # Sitemap para indexação
├── CNAME                      # Domínio customizado (GitHub Pages)
└── assets (imagens)
    ├── hero-ecosystem.png     # Hero da landing (fundo transparente)
    ├── sobre.jpg              # Seção Sobre (wireframes + MacBook)
    ├── brasao*.jpg/png        # Variações do logo
    ├── favicon.png            # Favicon 64x64
    └── capa-whatsapp.jpg      # OG image para compartilhamento
```

## Formulário de contato

Integrado via [Web3Forms](https://web3forms.com/) — envio client-side sem backend. Os formulários existem na landing e em cada página de serviço, com validação em tempo real (email e telefone brasileiro) e envio AJAX sem redirecionamento.

## Deploy

Push na `main` → GitHub Pages publica automaticamente. O domínio `jtisolucoes.dev.br` é configurado via CNAME e o certificado SSL é gerenciado pelo GitHub.

## Responsivo

Breakpoints em 576px (mobile), 768px (tablet) e 992px (desktop). Menu sanduíche com slide-in lateral e glassmorphism abaixo de 576px.

## Contato

- **WhatsApp:** (61) 99291-7593
- **Email:** jti.solucoes@outlook.com
- **Site:** [jtisolucoes.dev.br](https://jtisolucoes.dev.br)

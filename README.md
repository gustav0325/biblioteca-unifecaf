# Biblioteca Digital UniFECAF

Primeira interface web da Biblioteca Digital UniFECAF, desenvolvida para a disciplina **Design Web**.
O site transforma o protótipo de baixa fidelidade fornecido pela instituição em uma página responsiva e acessível, feita apenas com **HTML e CSS**.

- **Site publicado:** COLE_AQUI_O_LINK_DO_GITHUB_PAGES
- **Vídeo pitch:** COLE_AQUI_O_LINK_DO_YOUTUBE

## Estrutura

```
biblioteca-unifecaf/
├── index.html          # estrutura e conteúdo (HTML5 semântico)
├── css/
│   └── style.css       # layout, cores, tipografia e responsividade
└── assets/
    ├── imagens/        # ilustrações vetoriais (SVG) próprias
    └── fontes/         # Montserrat e Inter (woff2, licença OFL)
```

## Seções

Cabeçalho com menu · Banner principal · Sobre a nossa biblioteca · Faixa intermediária · Nossos livros · As unidades · Contatos · Rodapé

## Tecnologias e técnicas

- HTML5 semântico (`header`, `nav`, `main`, `section`, `article`, `figure`, `footer`)
- CSS3 com variáveis (`:root`), Flexbox, CSS Grid e `@font-face`
- Mobile-first, com pontos de quebra em 600px e 900px
- Menu hambúrguer feito só com CSS (checkbox + label)
- Acessibilidade: `lang="pt-BR"`, textos alternativos, link "pular para o conteúdo", foco visível e contraste WCAG AA

## Como abrir

Basta abrir o `index.html` no navegador. Não há etapa de build nem dependências.

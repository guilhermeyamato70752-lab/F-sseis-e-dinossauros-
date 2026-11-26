# Relatório de SEO — Atividade 2 (Fósseis e Dinossauros)

- **Site publicado:** [Link do GitHub Pages]
- **Palavras-chave escolhidas:**
  1. `fósseis e dinossauros`
  2. `dinossauros do brasil uberaba`
  3. `era mesozoica paleontologia`
- **Tipo schema.org:** `CollectionPage` (em `index.html`) e `Article` (em `sobre-paleontologia.html`), validados em `validator.schema.org` (inserir print).

## Decisões de Otimização
- Criação da segunda página (`sobre-paleontologia.html`) com `<title>`, `<meta name="description">` e `<link rel="canonical">` próprios[cite: 50, 51].
- Configuração de tags Open Graph e `og:image` em `1200x630` px além do `favicon.svg`[cite: 36, 51].
- Conversão das imagens para formato `.webp`, manutenção de `width`/`height` e aplicação de `loading="lazy"` nas imagens abaixo da dobra[cite: 35, 51].
- Adição de `robots.txt` e `sitemap.xml` na raiz do projeto[cite: 39, 44, 51].

## Auditoria Lighthouse (Dispositivo: Celular)

| Categoria | Antes | Depois |
| :--- | :---: | :---: |
| Desempenho | - | - |
| Acessibilidade | - | $\ge 90$ |
| Boas práticas | - | - |
| SEO | - | $\ge 95$ |
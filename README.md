# Claupa Militar

Site institucional e catálogo da Claupa Militar, fábrica de fardamento regulamentar
padrão Exército Brasileiro. Página única estática, sem dependências de build.

## Estrutura

- `index.html` — site completo (HTML, CSS e JS inline)
- `assets/` — imagens dos produtos e Open Graph

## Catálogo atual

- Conjunto Camuflado EB (gandola + calça)
- Gandola Camuflada EB
- Calça Camuflada EB
- Bota Tática Protefort
- Japona Camuflada EB

## Deploy

Site estático. Na Vercel é zero config:

- Framework Preset: Other
- Build Command: (vazio)
- Output Directory: (vazio)
- Root Directory: ./

A Vercel serve o `index.html` da raiz automaticamente.

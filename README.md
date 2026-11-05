# Receita Caseira — site

Site estático de página única. Sem build: é só subir a pasta `site/`.

## Estrutura
```
site/
  index.html          página (HTML + CSS + JS inline, schema JSON-LD)
  robots.txt          libera Google e buscadores de IA
  sitemap.xml         mapa do site com imagens
  llms.txt            resumo oficial da empresa para assistentes de IA
  site.webmanifest    ícones e cor do tema
  assets/             logo, fotos (WebP + JPG), ícones, fonte própria
PROMPT.md             briefing/spec do projeto
keywords.md           mapa de palavras-chave e ações no Perfil da Empresa
```

## Antes de publicar
1. **Domínio:** já configurado como `https://www.fabricareceitacaseria.com.br/` em `site/`.
2. **Instagram:** confirme `@receitacaseiraa_` (aparece no rodapé, no schema e no llms.txt).
3. **Fotos:** substitua `assets/caixas.*` e adicione fotos de cada doce em alta resolução (mín. 1200px).

## Publicar
- **Vercel / Netlify / Cloudflare Pages:** arraste a pasta `site/` ou aponte o repositório com diretório raiz `site`.
- **Hospedagem comum:** envie o conteúdo de `site/` para a pasta pública (`public_html`).

## Depois de publicar
1. Search Console: adicione o domínio e envie `sitemap.xml`.
2. Teste o schema em https://search.google.com/test/rich-results.
3. No Perfil da Empresa no Google, coloque o site com UTM:
   `https://SEU-DOMINIO/?utm_source=google&utm_medium=organic&utm_campaign=gbp`
4. Rode o Lighthouse no celular (meta: 90+ em todas as categorias).

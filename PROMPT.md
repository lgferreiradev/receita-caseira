# Site Receita Caseira — Fábrica de Doces (Uberaba/MG)

## Papel
Atue como estúdio de design + engenharia front-end + SEO local. Entregue um site de página única, rápido, acessível e com identidade própria, pronto para ser o "Site" do Perfil da Empresa no Google.

## O negócio (fatos confirmados — não inventar além disto)
- **Nome:** Receita Caseira — Fábrica de Doces
- **Produção própria:** ameixa de queijo, queijadinha (doce de queijo) e Maisninho (doce de leite em pó / doce de ninho)
- **Mais de 25 anos** em Uberaba, empresa de família
- **Atende atacado e varejo**
- **Endereço:** R. Inglaterra, 784 – Jardim Bela Vista, Uberaba – MG, 38070-370
- **Telefone/WhatsApp:** (34) 3313-4798
- **Horário:** segunda a sexta, 08:00–17:00 · sábado e domingo fechado
- **Instagram:** @receitacaseiraa_ (confirmar grafia — a fachada mostra "receitacaseira_")

Proibido inventar: preços, avaliações/depoimentos, notas, ano de fundação exato, entrega, ingredientes, validade.

## Objetivos (em ordem)
1. **Converter visita em contato:** WhatsApp e rota no mapa sempre a 1 toque, principalmente no celular.
2. **SEO local avançado:** ranquear para buscas de produto + Uberaba e reforçar o Perfil da Empresa (NAP idêntico ao Google).
3. **Ser fonte de informação (GEO):** responder perguntas reais ("o que é ameixa de queijo", "vende no atacado?", "abre sábado?") em texto que o Google e assistentes de IA possam citar.
4. **Retenção:** design memorável, leitura fluida, microinterações que respondem ao usuário.

## Público
- **Varejo:** moradores de Uberaba e região que querem levar doce para casa, presentear ou servir em festa.
- **Atacado:** padarias, mercearias, empórios, cantinas, revendedores e quem monta mesa de festa.

## Identidade visual (extraída da logo, fachada e embalagem)
| Token | Hex | Origem |
|---|---|---|
| Amarelo fachada | `#F6C21B` | toldo e caixas |
| Manteiga | `#F5D58A` | miolo da logo |
| Cacau | `#2B211B` | faixa escura da fachada / traço da logo |
| Doce de leite | `#B9781A` | script dourado "Fábrica de doces" |
| Leite | `#FFFCF3` | fundo de leitura |
| Xadrez | preto/branco | selo "Caseira" das caixas |

- **Tipografia:** Bricolage Grotesque (uma família, eixos de peso/largura/óptico) — personalidade de rótulo comercial antigo sem cair no serif "padrão IA".
- **Motivo-assinatura:** o **papel de bala torcido** da logo (oval + pontas listradas). Ele vira o loader, a moldura das imagens e os ícones dos produtos.
- **Layout:** editorial assimétrico, alinhado à esquerda; nada de grade de cards idênticos.

## Estrutura da página
1. **Cabeçalho** (faixa cacau como o toldo): logo, navegação, botão WhatsApp. Faixa xadrez logo abaixo.
2. **Hero amarelo:** H1 com produto + cidade, subtítulo com 25 anos/família/atacado e varejo, status ao vivo "Aberto agora / Fechado — abre segunda às 8h", CTAs "Pedir pelo WhatsApp" e "Ver rota no mapa".
3. **Nossos doces:** ameixa de queijo, queijadinha, doce de ninho — descrição, ocasião, botão de pedido com mensagem pré-preenchida por produto.
4. **Atacado e varejo:** dois caminhos claros + passo a passo de como comprar.
5. **História:** família, produção própria, 25+ anos em Uberaba.
6. **Visite a fábrica:** foto da fachada, mapa incorporado, horário com o dia atual destacado, botões "Abrir no Google Maps" e "Abrir no Waze" (abrem o app no celular).
7. **Perguntas frequentes** (accordion acessível) — base do FAQPage schema.
8. **Rodapé:** NAP, horário, redes, crédito.
9. **Barra fixa no celular:** WhatsApp + Rota. Botão flutuante de WhatsApp no desktop.

## SEO técnico
- `<title>` e meta description com produto + Uberaba; canonical; Open Graph/Twitter; `lang="pt-BR"`; geo meta.
- **JSON-LD:** `FoodEstablishment` (endereço, telefone, horário, `hasMap`, `sameAs`, `areaServed`, catálogo de produtos), `WebSite`, `FAQPage`.
- Um único H1; H2 por seção; textos com as palavras-chave do mapa (keywords.md) de forma natural.
- `robots.txt`, `sitemap.xml`, `llms.txt` (resumo para IAs), `site.webmanifest`, favicon da logo.
- Imagens WebP dimensionadas, `alt` descritivo, `loading="lazy"` abaixo da dobra, mapa com carregamento tardio.

## UX / Acessibilidade
- Responsivo de 360px a 1440px, sem rolagem horizontal; alvos de toque ≥ 44px.
- Foco visível, navegação por teclado, contraste AA.
- **Loader** curto (≤1,2s, some assim que a página carrega) com o papel de bala abrindo.
- **Scroll:** revelações discretas por seção; tudo desligado com `prefers-reduced-motion`.
- Microcopy verbo-primeiro: "Pedir pelo WhatsApp", "Ver rota no mapa", "Ligar para a fábrica".

## Critérios de aceite
- WhatsApp e rota acessíveis em 1 toque em qualquer ponto da página no celular.
- NAP do site idêntico ao Perfil da Empresa no Google.
- Schema válido no Rich Results Test; Lighthouse ≥ 90 em Performance, Acessibilidade, Boas práticas e SEO.
- Nenhum dado inventado.

## Pendências com o cliente
- Domínio definitivo (definido: `https://www.fabricareceitacaseria.com.br/`).
- Fotos dos 3 doces e da fachada já recebidas.
- Confirmar Instagram, se há entrega e formatos de embalagem (atacado/varejo).

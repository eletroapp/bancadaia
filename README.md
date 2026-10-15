# Bancada IA

Site de afiliado da Shopee com curadoria de produtos de elétrica, ferramentas, veículos e informática.

Endereço: https://bancadaia.com.br

## Como funciona

- Site estático hospedado no GitHub Pages.
- `index.html` é a página (cards, filtros e busca simples).
- `vitrine.csv` guarda os produtos (fonte principal).
- `dados.js` é uma cópia do CSV, usada quando o navegador bloqueia a leitura do CSV.

## Arquivos de dados

`vitrine.csv`: separador `;`, UTF-8. Colunas:

`nome; imagem; preco; url_shopee; link_afiliado; categoria; subcategoria; observacoes; serve_para`

- `preco`: número com ponto decimal, sem "R$" (ex.: 89.90).
- `serve_para`: função do produto em linguagem simples, com sinônimos.

**Ao editar o `vitrine.csv`, atualize também o `dados.js`.**

## Aviso

Este site participa do programa de afiliados da Shopee e pode receber comissão por compras feitas pelos links, sem custo extra para quem compra.

## Arquivos de SEO

- `robots.txt`: libera a indexação e aponta o sitemap.
- `sitemap.xml`: lista as páginas do site.

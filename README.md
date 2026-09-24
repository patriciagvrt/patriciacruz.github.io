# pcruzresearch.com

Site pessoal de Patricia Cruz, publicado no GitHub Pages.

## Estrutura
- `index.html` : home (apresentação, highlights, pesquisa selecionada, último post)
- `research.html` : todos os projetos, agrupados por status
- `writing.html` : lista de posts (aparece como "Notes" no menu)
- `about.html` : bio, formação, experiência, métodos, idiomas
- `contact.html` : formulário e links
- `site.css` : estilo de todas as páginas (mude cores e fontes aqui)
- `post-styles.css` : usado pelos posts, carrega o `site.css`
- `post-template.html` e `admin.html` : para criar novos posts

## Antes de publicar (TODO)
1. Trocar `YOUR-LINKEDIN` em todas as páginas (busque por `YOUR-LINKEDIN`)
2. Criar um formulário grátis em formspree.io com o email patricia@pcruzresearch.com e trocar `YOUR_FORM_ID` em `contact.html`
3. Conferir os anos marcados com `TODO` em `about.html`

## Como adicionar um post
1. Abra `admin.html` no navegador, escreva o post e clique em Download
2. Suba o arquivo `.html` para o repositório
3. Copie um bloco `<li>...</li>` em `writing.html` e mude link, data, título e resumo
4. Se for o post mais recente, faça o mesmo na seção Notes de `index.html`

# Como publicar seu site no GitHub Pages
## Guia passo a passo para Patricia Cruz — Cognitive Loop

---

## O que você vai precisar
- Uma conta no GitHub (gratuita) → https://github.com
- Os 3 arquivos do seu site:
  - `index.html` — página principal
  - `post-template.html` — template de posts
  - `contact.html` — página de contato

---

## PASSO 1 — Criar conta no GitHub
1. Acesse https://github.com/signup
2. Escolha um username — **este vai ser parte da URL do seu site**
   - Exemplo: se seu username for `patriciacruz`, seu site ficará em:
     `https://patriciacruz.github.io`
   - Escolha algo limpo e profissional

---

## PASSO 2 — Criar o repositório
1. Faça login no GitHub
2. Clique no botão verde **"New"** (ou acesse https://github.com/new)
3. Em **"Repository name"**, digite **exatamente**:
   ```
   seuusername.github.io
   ```
   Substituindo `seuusername` pelo seu username real.
   Exemplo: `patriciacruz.github.io`
4. Deixe como **Public**
5. Marque ✅ **"Add a README file"**
6. Clique em **"Create repository"**

---

## PASSO 3 — Fazer upload dos arquivos
1. Dentro do repositório recém-criado, clique em **"Add file"** → **"Upload files"**
2. Arraste ou selecione os 3 arquivos:
   - `index.html`
   - `post-template.html`
   - `contact.html`
3. Em **"Commit changes"**, escreva uma mensagem como: `Add website files`
4. Clique em **"Commit changes"**

---

## PASSO 4 — Ativar o GitHub Pages
1. Vá em **Settings** (aba no topo do repositório)
2. No menu lateral, clique em **Pages**
3. Em **"Source"**, selecione:
   - Branch: **main**
   - Folder: **/ (root)**
4. Clique em **Save**
5. Aguarde 1–2 minutos
6. Aparecerá uma mensagem verde com a URL do seu site:
   **https://seuusername.github.io**

---

## PASSO 5 — Verificar e personalizar
1. Abra a URL no browser para confirmar que está tudo certo
2. Abra os arquivos HTML e substitua os placeholders:
   - `your-profile` no link do LinkedIn → seu perfil real
   - `your-username` no GitHub → seu username real
   - Email no footer → seu email real

---

## Como adicionar um novo post
1. Faça uma **cópia** do arquivo `post-template.html`
2. Renomeie para algo como `post-aprendendo-com-ia.html`
3. Edite o conteúdo (título, data, texto)
4. Em `index.html`, adicione uma linha na seção Writing:
   ```html
   <a href="post-aprendendo-com-ia.html" class="post-row">
     <div class="post-date">Jun<br>2025</div>
     <div class="post-title">Título do post aqui</div>
     <span class="post-tag">Essay</span>
   </a>
   ```
5. Faça upload do novo arquivo no GitHub

---

## Como ativar o formulário de contato (opcional)
O formulário de contato precisa de um serviço externo para funcionar de verdade.
A opção mais simples e gratuita é o **Formspree**:

1. Acesse https://formspree.io e crie uma conta gratuita
2. Crie um novo formulário — você receberá um ID como `xrgdkpqz`
3. Em `contact.html`, substitua a função `handleSubmit` por:
   ```html
   <form action="https://formspree.io/f/SEU_ID" method="POST">
     <!-- campos do formulário -->
     <button type="submit">Send message →</button>
   </form>
   ```
4. As mensagens chegam no seu email automaticamente

---

## Resumo da estrutura de arquivos
```
seuusername.github.io/
├── index.html          ← página principal
├── post-template.html  ← template (copie para cada post)
├── contact.html        ← página de contato
└── post-meu-post.html  ← posts futuros (copias do template)
```

---

## URL final do seu site
```
https://seuusername.github.io
```

Boa sorte, Patricia! 🌿

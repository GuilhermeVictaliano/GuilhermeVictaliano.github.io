# guilhermevictaliano.github.io

Portfólio bilíngue (PT/EN) de Guilherme Victaliano — AI Builder.
Publicado com GitHub Pages (Jekyll, sem dependências).

## Publicar pela primeira vez

1. No GitHub, crie um repositório **público** chamado exatamente `GuilhermeVictaliano.github.io`.
2. Envie o conteúdo desta pasta:
   ```bash
   cd portfolio-site
   git init -b main
   git add .
   git commit -m "Portfólio AI Builder"
   git remote add origin https://github.com/GuilhermeVictaliano/GuilhermeVictaliano.github.io.git
   git push -u origin main
   ```
   (Sem terminal: em github.com, no repositório vazio, clique em **uploading an existing file** e arraste todos os arquivos e pastas.)
3. Em **Settings → Pages**, confirme *Source: Deploy from a branch*, branch `main`, pasta `/ (root)`.
4. Em 1–2 minutos o site está em **https://guilhermevictaliano.github.io**.

## Publicar uma nota

Copie `_templates/novo-post.md` para `_posts/AAAA-MM-DD-slug.md`, escreva e faça commit.
Para ter a nota nos dois idiomas, crie dois arquivos (`lang: pt` e `lang: en`) e aponte um para o outro em `translation:`.

## Adicionar um projeto

Copie um bloco `<article class="card">` em `index.html`. Cada texto existe duas vezes: `data-pt` e `data-en`.

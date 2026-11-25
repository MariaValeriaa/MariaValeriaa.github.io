# Academic portfolio – M. V. C. Andre

Site estático (HTML + CSS puro). Não precisa instalar nada.

## Estrutura
```
index.html
assets/photo.jpg            (sua foto)
assets/CV_Maria_Andre.pdf   (você adiciona; veja abaixo)
.nojekyll
```

## Antes de publicar (3 itens)
1. O CV (sem telefone) já está em `assets/CV_Maria_Andre.pdf`. O LinkedIn já está no site.
2. No `index.html`, procure `REPLACE-WITH-YOUR-GITHUB-USERNAME` e troque pelo seu usuário do GitHub.
3. (Opcional) Adicione um link do Google Scholar na seção `contact`.

## Publicar no GitHub Pages
1. github.com → New repository → nome: `SEU-USUARIO.github.io` (público).
2. "uploading an existing file" → arraste `index.html`, `.nojekyll` e a pasta `assets` → Commit.
3. Settings → Pages → Source: "Deploy from a branch" → Branch: `main` / `(root)` → Save.
4. Em 1–2 minutos o site abre em `https://SEU-USUARIO.github.io`.
5. Coloque esse link no cabeçalho do seu CV.

## Atualizar depois
Edite `index.html` no GitHub (ícone de lápis) → Commit. O site atualiza sozinho.

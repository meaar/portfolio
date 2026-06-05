# Alberto Almeida — GitHub Pages

Página estática profissional para publicação direta no GitHub Pages.

## Estrutura

```text
.
├── index.html
├── 404.html
├── .nojekyll
├── css/
│   └── style.css
└── js/
    └── main.js
```

## Publicação no GitHub Pages

1. Crie um repositório, por exemplo `meaar.github.io` ou outro nome.
2. Envie todos os arquivos para a branch principal.
3. Em **Settings > Pages**, selecione:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
4. Aguarde o deploy.

## Segurança aplicada

- Site 100% estático.
- Sem formulário e sem backend.
- Sem coleta de dados.
- Links externos com `noopener noreferrer`.
- `Content-Security-Policy` restritiva no `index.html`.
- `referrer` configurado como `strict-origin-when-cross-origin`.
- `.nojekyll` para evitar processamento desnecessário pelo GitHub Pages.

## Foto dinâmica

A imagem de perfil usa:

```html
https://github.com/meaar.png
```

Assim, quando a foto pública do GitHub for alterada, a imagem tende a atualizar no site também, respeitando cache do navegador/GitHub.

# Ícone "Colo" — coração acolhido

Coração (afeto) aninhado numa concha de mãos (o gesto de dar colo), no verde da
marca. O logo do topo do app (login, cabeçalho, cadastro) já foi trocado por esse
desenho dentro do `index.html`.

## Arquivos (todos vão na RAIZ do COLO, ao lado do index.html)

- `favicon.svg` — vetor, nitidez em qualquer tamanho (favicon moderno)
- `favicon.ico` — 16/32/48, para navegadores antigos
- `favicon-16.png`, `favicon-32.png` — abas
- `apple-touch-icon.png` (180) — atalho no iPhone/iPad
- `icon-192.png`, `icon-512.png` — instalação como app (PWA)
- `site.webmanifest` — nome e ícones do app instalado

## Tags (já estão no <head> do index.html)

```html
<meta name="theme-color" content="#3f6b52">
<link rel="icon" type="image/svg+xml" href="favicon.svg">
<link rel="icon" type="image/png" sizes="32x32" href="favicon-32.png">
<link rel="icon" type="image/png" sizes="16x16" href="favicon-16.png">
<link rel="apple-touch-icon" sizes="180x180" href="apple-touch-icon.png">
<link rel="icon" href="favicon.ico" sizes="any">
<link rel="manifest" href="site.webmanifest">
```

## Importante

Os caminhos são relativos à raiz. Como seu site está em
`usuario.github.io/terapia-online/`, mantenha todos esses arquivos na mesma pasta
do `index.html`. Se a aba não atualizar o ícone na hora, é cache do navegador —
force um recarregamento (Ctrl+F5) ou abra numa aba anônima.

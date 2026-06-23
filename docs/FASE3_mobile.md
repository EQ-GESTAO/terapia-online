# Portal do terapeuta + responsividade mobile

## O que mudou
- O terapeuta agora **abre direto em "Meus"**, com a aba **"Aguardando" ao lado**.
- Os três portais (paciente, terapeuta, gestão) **funcionam bem no celular**:
  navegação em uma coluna por vez (lista → conversa → ficha), com **botão de
  voltar (‹)** no topo de cada tela.
  - Terapeuta: na conversa há um botão **☰** que abre a ficha do paciente
    (anotações da sessão, "o que trouxe", encerrar) — e um "‹ Voltar à conversa".
  - Cabeçalhos enxutos no celular (some o nome ao lado do avatar, fica só o
    essencial); abas da gestão deslizam na horizontal.
- No computador, **nada muda** — continua com as colunas lado a lado.

## Como testar no celular
Abra o site (a mesma URL do GitHub Pages) no navegador do celular, ou no
computador aperte F12 → ícone de celular (modo dispositivo). A quebra acontece
em telas de até 820px de largura.

Nada a configurar no Supabase para isto.

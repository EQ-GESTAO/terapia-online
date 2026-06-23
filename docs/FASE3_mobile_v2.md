# Mobile v2 — sem rolagem lateral

## O que foi corrigido
- **Zero rolagem horizontal** travada de forma definitiva (não rola mais pro lado
  em nenhuma tela).
- No celular, **uma tela por vez**: lista → toca → abre a conversa em tela cheia,
  com **‹ (voltar)** no topo. Nada de colunas espremidas lado a lado.
- **Paciente entra direto na conversa** (quando já tem uma), com o ‹ levando de
  volta à lista das conversas / "Nova conversa".
- Altura **dinâmica (100dvh)**: a barra de digitar não fica mais escondida atrás
  da barra de endereço do navegador no celular.
- Colunas à prova de estouro (não forçam largura maior que a tela).

## IMPORTANTE: cache
Se você já tinha aberto o site, o navegador pode mostrar a versão antiga (que
rolava pro lado). Depois de publicar:
- no celular: feche a aba e abra de novo, ou use uma **aba anônima**;
- no computador (modo dispositivo do F12): **Ctrl + Shift + R**.

Nada a configurar no Supabase.

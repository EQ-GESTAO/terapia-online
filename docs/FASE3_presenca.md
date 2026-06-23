# Fase 3 · parte 1 — Presença (online em tempo real)

Substitui o `index.html`. **Não precisa configurar nada no Supabase** — usa o
Realtime Presence (mesmo canal de tempo real que já está ligado).

O que passa a funcionar:
- O **status "online agora / offline"** do paciente no painel do terapeuta vira real.
- A **bolinha verde** de online na lista de pacientes e na Equipe (gestão) acende
  de verdade quando a pessoa está com o app aberto.
- A tela de login mostra **"Plantão 24h · N terapeutas online agora"** real.

Como testar: abra o app em duas janelas com contas diferentes. Quem está com o
app aberto aparece como online para o outro; feche/saia e em segundos fica offline.

Próxima parte da Fase 3: **áudio (mensagens de voz) via Supabase Storage** — essa
sim vai pedir um bucket novo e um patch de SQL (eu mando o passo a passo).

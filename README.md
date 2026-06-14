# GestMan365

Sistema web para gestao de manutencao, maquinas, mapa industrial, MTTR, MTBF, ordens de servico e checklists.

## Versao atual

Esta versao inicia sem dados cadastrados. A conta visual do sistema e de Administrador, com permissoes para:

- Criar, editar e excluir maquinas.
- Criar, editar e excluir locais.
- Criar, editar e excluir tags e subtags.
- Criar, editar e excluir OS.
- Criar, editar e excluir checklists.
- Apagar todos os dados e recomecar.
- Exportar os dados em JSON.

## Arquivos

- `index.html`: sistema principal.
- `supabase-setup.sql`: base inicial para evolucao com Supabase.
- `ESCOPO.md`: escopo do produto.

## Como usar

Abra `index.html` no navegador.

Os dados sao salvos no navegador usando `localStorage`. Para recomecar do zero, clique em `Apagar tudo`.

## Fluxo recomendado

1. Crie os locais do parque industrial.
2. Crie tags e subtags.
3. Cadastre as maquinas e posicione cada uma no mapa.
4. Crie OS e checklists para alimentar os indicadores.
5. Acompanhe MTTR, MTBF, disponibilidade e backlog no dashboard.

## GitHub

Para publicar:

1. Crie um repositorio chamado `gestman365`.
2. Envie os arquivos desta pasta pelo GitHub.
3. Ative GitHub Pages apontando para `index.html`.

## Seguranca

Nao publique senhas, chaves secretas ou service role keys no repositorio.

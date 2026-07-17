# Instituto Kronos · Painel — Layout Editorial Magazine

Hub agregador do Instituto Kronos num único arquivo HTML.

- **Versão**: v0.13-teste · Layout Editorial Magazine
- **Inspiração**: Stripe Press / Medium — tipografia serif generosa (Fraunces), max-width 720px, divisores em vez de cards, rosa só em itálico
- **Conteúdo**: 6 camadas (Gestão/Operação/Produtos/SOPs/Biblioteca/Conhecimento) + 7 sub-áreas de Operação + 5 produtos + Playbook Mentoria Kairós com 10 notas
- **Persistência**: localStorage (`kronos_state_v1`)

## Como rodar

```bash
python -m http.server 8000
# abrir http://localhost:8000
```

Single-file, sem build, sem dependências. Funciona offline.

## Funcionalidades

- Busca com stemmer + 200+ sinônimos
- Botão Resumo (todos os links/docs/notas em uma página)
- Modal Adicionar/Editar
- Visualizador de notas (Playbook Kairós)
- 4 abas: Gestão / Operação / Produtos / SOPs / Biblioteca / Conhecimento
- Drag handle `⋮⋮` aparece no hover
- Vazios visíveis por padrão

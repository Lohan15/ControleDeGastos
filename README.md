# GoldQuest — RPG Financeiro

Controle financeiro pessoal com gamificação. Gerencie seu dinheiro enquanto evolui um herói, completa missões e desbloqueia conquistas.

## Como usar

Baixe o arquivo `rpg-financeiro.html` e abra no navegador. Nenhuma instalação necessária — funciona 100% offline.

## Funcionalidades

- **Painel do herói** — visão geral de saldo, gastos do mês, missões ativas e diário de eventos
- **Gerenciamento financeiro** — cadastro de salário, limite de orçamento mensal, registro de receitas e despesas com categorias
- **Missões** — diárias, semanais e desafios especiais com barras de progresso
- **Conquistas** — 8 medalhas desbloqueadas automaticamente conforme o progresso
- **Sistema RPG** — avatar evolutivo (5 níveis), barras de HP e XP, moedas de ouro, level up animado
- **Diário** — histórico cronológico de todos os eventos

## Tecnologias

- HTML, CSS e JavaScript puro (sem dependências ou frameworks)
- Fonte: [Cinzel + Crimson Pro](https://fonts.google.com) via Google Fonts
- Persistência via `localStorage` — dados salvos automaticamente no navegador

## Estrutura do projeto

```
rpg-financeiro.html   # arquivo único com toda a aplicação
README.md
```

## Observações

- Os dados ficam salvos localmente no navegador; limpar o cache apaga o progresso
- O orçamento e as missões diárias/semanais resetam automaticamente a cada mês
- Testado nos navegadores Chrome, Firefox, Edge e Safari

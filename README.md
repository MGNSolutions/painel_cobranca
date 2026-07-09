# 📞 Painel de Cobrança

Sistema web para registro e acompanhamento de contatos de cobrança com clientes. Centraliza o dia a dia da equipe de cobrança: quem foi contatado, por qual canal, qual o status da negociação e o que ficou combinado.

**Feito em HTML, CSS e JavaScript puros — um único arquivo, sem dependências, sem build.**

## ✨ Funcionalidades

- **Registro de contatos** com empreendimento, cliente, unidade, forma de contato (telefone, WhatsApp, e-mail ou presencial), data, status e observações
- **Campo inteligente**: o formulário se adapta à forma de contato escolhida (pede telefone, e-mail ou oculta o campo quando presencial)
- **Estatísticas em tempo real**: contatos do dia, total de clientes, total de registros e casos em andamento
- **Busca e filtro**: pesquise por cliente, empreendimento ou unidade e filtre por status
- **Status com um clique**: altere o status direto na tabela pelo badge colorido
  - 🔵 Em andamento · 🟡 Negociando · 🔴 Sem retorno · 🟢 Finalizado · 🟣 Distrato
- **Edição inline de observações**: clique na célula e edite sem sair da tela
- **Histórico por cliente**: linha do tempo com todos os contatos já feitos com aquele cliente
- **Persistência local**: os dados ficam salvos no navegador (localStorage) — nada se perde ao fechar a página

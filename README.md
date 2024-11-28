Sistema de Gerenciamento de Futebol e Tarefas

Este repositório contém dois modelos de casos de uso desenvolvidos em **StarUML**, abrangendo os seguintes sistemas:
1. **Sistema de Controle de Partida de Futebol**.
2. **Sistema de Controle de Tarefas**.

Os modelos representam funcionalidades importantes e os fluxos de interação entre os usuários e os sistemas.

📋 Descrição Geral

1. **Sistema de Controle de Partida de Futebol**
Este sistema foi projetado para gerenciar os processos relacionados a partidas de futebol, incluindo:
- Planejamento e organização de jogos;
- Registro e monitoramento de eventos durante a partida (gols, cartões, etc.);
- Controle de tempo da partida.

2. **Sistema de Controle de Tarefas**
Desenvolvido para facilitar o gerenciamento de tarefas, permitindo ao usuário:
- Criar, editar e excluir tarefas;
- Consultar tarefas com base em critérios específicos;
- Integrar funcionalidades como envio de notificações por e-mail.

🖥️ Ferramenta Utilizada

Os diagramas foram criados utilizando o **StarUML**, uma ferramenta amplamente usada para modelagem de sistemas baseados em UML (Unified Modeling Language).

🗂️ Atores e Casos de Uso

**Sistema de Controle de Partida de Futebol**
**Atores**
- **Apoio Técnico, Técnico do Clube e Técnico Auxiliar**: Gerenciam a operação e monitoramento do jogo.
- **Servidor HTTP, API Sistema e Banco de Dados**: Gerenciam a integração técnica e o armazenamento de dados.

**Principais Casos de Uso**
- Marcar jogo, convocar jogadores, registrar gols/cartões amarelos.
- Controlar o placar, adicionar tempo e finalizar a partida.
- Gerenciamento de logs e tratamento de erros.

**Sistema de Controle de Tarefas**
**Atores**
- **Cliente**: Usuário principal que gerencia as tarefas.
- **Servidor HTTP, API Tarefa e Banco de Dados**: Realizam o processamento técnico e armazenamento de informações.

**Principais Casos de Uso**
- Login e autenticação do cliente.
- Criação, edição, exclusão e atualização de tarefas.
- Consulta detalhada das tarefas (por data, informações completas, etc.).
- Envio de notificações por e-mail.

🛠️ Funcionalidades Planejadas

**Controle de Partida de Futebol**
- Logs detalhados de eventos críticos.
- Tratamento de erros ao listar jogadores ou registrar eventos.

**Controle de Tarefas**
- Notificações automáticas por e-mail em caso de erro ou para tarefas importantes.
- Histórico de tarefas mais recentes e tarefas criadas por primeiro.

📂 Estrutura do Repositório

- `Sistema de Controle de Partida de Futebol.png`: Diagrama do primeiro sistema.
- `Sistema de Controle de Tarefas.png`: Diagrama do segundo sistema.
- `README.md`: Documento de descrição do projeto.


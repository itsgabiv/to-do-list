# to-do-list
Trabalho programação III TO DO LIST

Explicação Rápida do Trabalho: Sistema de Gerenciamento de Tarefas (To-Do List)

Este projeto consiste em desenvolver um sistema de gerenciamento de tarefas (to-do list) com frontend em Vue.js e backend em Node.js usando o framework NestJS, conectado a um banco de dados PostgreSQL.

Funcionalidades Implementadas:
Backend (Node.js com NestJS):

Estrutura organizada seguindo os padrões do NestJS.
Conexão ao banco de dados PostgreSQL configurada no arquivo ormconfig.json.
Modelo de dados para as tarefas (Task) criado em task.entity.ts.
Controladores implementados para operações CRUD em tasks.controller.ts.
Serviço encapsulando a lógica de manipulação de dados em tasks.service.ts.
Frontend (Vue.js):

Estrutura de pastas padrão do Vue.js.
Componentes criados para o cabeçalho, lista de tarefas, formulário de cadastro/edição, etc.
Consumo de APIs do backend usando Axios ou fetch.
Configuração de rotas com Vue Router.
Implementação de marcação de tarefas como concluídas e modal de exclusão.
Diferencial (Opcional):
Reordenação da lista implementada via drag and drop (usando, por exemplo, a biblioteca Vue.Draggable).
GitHub:
Repositório no GitHub contendo todo o código-fonte.
README.md no repositório com instruções de instalação e execução.
Entrega:
Backend capaz de salvar dados no banco de dados PostgreSQL.
Frontend funcional permitindo operações CRUD, marcação de tarefas como concluídas e exclusão via modal.
Apresentação:
Demonstração do sistema em funcionamento.
Destaque para as principais funcionalidades.
Explicação de uma parte do código durante a apresentação.
Este projeto visa proporcionar uma experiência completa de desenvolvimento, desde a configuração do backend até a interação do usuário no frontend. As tecnologias utilizadas são o Node.js para o backend, Vue.js para o frontend, PostgreSQL como banco de dados e NestJS para facilitar a organização e estruturação do código no backend.

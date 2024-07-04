# Site de Gerenciamento de Tarefas

![License](https://img.shields.io/badge/license-MIT-blue.svg)

## Descrição

Um site de gerenciamento de tarefas para ajudar os usuários a organizar suas atividades diárias de forma eficiente. O site permite adicionar, editar, excluir e marcar tarefas como concluídas.

## Funcionalidades

- Adicionar novas tarefas
- Editar tarefas existentes
- Excluir tarefas
- Marcar tarefas como concluídas
- Visualizar tarefas por categorias
- Notificações de lembrete
- Sincronização com o calendário

## Tecnologias Utilizadas

- **Front-end**: React
- **Back-end**: Node.js, Express
- **Banco de Dados**: MongoDB
- **Autenticação**: JWT (JSON Web Tokens)
- **Serviços de Notificação**: Firebase Cloud Messaging

## Instalação

1. Clone o repositório:
    ```sh
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    cd nome-do-repositorio
    ```

2. Instale as dependências do back-end:
    ```sh
    cd backend
    npm install
    ```

3. Instale as dependências do front-end:
    ```sh
    cd ../frontend
    npm install
    ```

4. Configure as variáveis de ambiente:
    - Crie um arquivo `.env` no diretório `backend` com as seguintes variáveis:
        ```env
        MONGO_URI=sua-string-de-conexao-mongodb
        JWT_SECRET=sua-chave-secreta-jwt
        FCM_SERVER_KEY=sua-chave-do-firebase-cloud-messaging
        ```

5. Inicie o servidor back-end:
    ```sh
    cd backend
    npm start
    ```

6. Inicie o servidor front-end:
    ```sh
    cd ../frontend
    npm start
    ```

## Uso

1. Abra seu navegador e acesse `http://localhost:3000`.
2. Crie uma conta ou faça login.
3. Comece a adicionar e gerenciar suas tarefas.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Para mais informações, entre em contato pelo email: [f0rm1g0n1.r0ss0@gmail.com](mailto:f0rm1g0n1.r0ss0@gmail.com)

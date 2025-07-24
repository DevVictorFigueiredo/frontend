💻 Frontend - Aplicação Web de Lista de Tarefas

✨ Visão Geral

Este é o Frontend da aplicação de lista de tarefas, uma interface de usuário interativa e responsiva que permite aos usuários gerenciar suas tarefas de forma intuitiva. Ele se comunica com o API Gateway para buscar, criar, atualizar e excluir tarefas.

🚀 Funcionalidades

    Exibição de uma lista de tarefas.

    Adição de novas tarefas.

    Marcação de tarefas como concluídas ou pendentes.

    Exclusão de tarefas existentes.

🛠️ Tecnologias Utilizadas

    React: Biblioteca JavaScript para construção de interfaces de usuário.

    Vite: Ferramenta de desenvolvimento rápido para projetos front-end.

    TypeScript: Adiciona tipagem estática ao JavaScript para maior robustez e manutenção do código.

    CSS: Para estilização e design da aplicação.

    Axios: Cliente HTTP para fazer requisições à API.

⚙️ Configuração e Execução Local

Para rodar o Frontend no seu ambiente local, siga os passos abaixo:

Pré-requisitos

Certifique-se de ter os seguintes softwares instalados:

    Node.js (versão 18 ou superior recomendada)

    npm (gerenciador de pacotes do Node.js)

    O API Gateway deve estar em execução na porta 3000.

1. Configuração das Variáveis de Ambiente (.env)

Crie um arquivo chamado .env na raiz deste diretório (frontend/) e adicione a seguinte variável:
Snippet de código

VITE_API_GATEWAY_URL=http://localhost:3000

2. Instalação das Dependências

Com o terminal aberto na raiz do diretório frontend/, instale as dependências do projeto:
Bash

npm install

3. Execução da Aplicação

Para iniciar o Frontend em modo de desenvolvimento (com recarregamento automático):
Bash

npm run dev

O Vite iniciará um servidor de desenvolvimento, e você verá uma URL no terminal (geralmente http://localhost:5173/).

4. Acessar no Navegador

Abra seu navegador web e acesse a URL fornecida pelo comando npm run dev (ex: http://localhost:5173/).

🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests caso encontre problemas ou queira adicionar funcionalidades.

📄 Licença

Este projeto está licenciado sob a MIT License.

# Food E-commerce Application

## Descrição
Este projeto é uma aplicação de ```E-commerce FOOD``` desenvolvida com a stack MERN (MongoDB, Express, React, Node.js). A aplicação permite que os usuários naveguem, adicionem produtos ao carrinho e façam compras online de alimentos.

## Funcionalidades
- Cadastro e login de usuários
- Navegação por categorias de produtos
- Pesquisa de produtos
- Adição de produtos ao carrinho
- Finalização de compra
- Histórico de pedidos
- Avaliação e comentários de produtos
- Painel de administrador para gerenciamento de produtos e pedidos

## Tecnologias Utilizadas
- **Frontend:** React, Redux, Vite
- **Backend:** Node.js, Express
- **Banco de Dados:** MongoDB
- **Autenticação:** JSON Web Tokens (JWT)
- **Estilização:** CSS, Tailwind CSS

## Pré-requisitos
- Node.js instalado
- MongoDB instalado e em execução

## Instalação
1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd nome-do-repositorio
    ```

3. Instale as dependências do servidor:
    ```bash
    cd backend
    npm install
    ```

4. Instale as dependências do cliente:
    ```bash
    cd ../frontend
    npm install
    ```

5. Configure as variáveis de ambiente:
    - Crie um arquivo `.env` no diretório `backend` com as seguintes variáveis:
        ```env
        PORT=5000
        MONGO_URI=sua_uri_mongodb
        JWT_SECRET=sua_chave_secreta
        ```

## Executando a Aplicação
1. Inicie o servidor backend:
    ```bash
    cd backend
    npm start
    ```

2. Inicie o servidor frontend:
    ```bash
    cd ../frontend
    npm start
    ```

3. Acesse a aplicação em [http://localhost:3000](http://localhost:3000)

## Estrutura do Projeto
```plaintext
nome-do-repositorio/
│
├── backend/          # Código do servidor e API
│   ├── controllers/  # Controladores da API
│   ├── models/       # Modelos do MongoDB
│   ├── routes/       # Rotas da API
│   ├── config/       # Configuração e conexão com o MongoDB
│   ├── middleware/   # Middlewares
│   └── server.js     # Inicialização do servidor
│
├── frontend/         # Código do cliente e interface de usuário
│   ├── public/       # Arquivos públicos
│   ├── src/          # Código-fonte do React
│   │   ├── components/  # Componentes do React
│   │   ├── pages/       # Páginas do React
│   │   └── App.js       # Componente raiz do React
│   └── package.json  # Dependências do frontend
│
└── README.md         # Documentação do projeto
Contribuição
Faça um fork do projeto

Crie uma nova branch (git checkout -b feature/xyz)

Faça commit das suas alterações (git commit -m 'Add some feature')

Faça push para a branch (git push origin feature/xyz)

Abra um Pull Request

Licença
Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.


Espero que isso ajude! Se precisar de mais alguma coisa, é só falar.


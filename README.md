# Agenda
Projeto Agenda

Projeto Contatos
Descrição:

Este é um sistema de gerenciamento de contatos desenvolvido em Node.js, Express e MongoDB.
Permite criar, editar, listar e excluir contatos, além de funcionalidades de login e autenticação de usuários.

Tecnologias Utilizadas:

Node.js

Express.js

MongoDB (com Mongoose)

EJS (para views)

Validator (validação de campos)

bcryptjs (para hash de senhas)

Bootstrap (para estilização)

Funcionalidades:

Cadastro de contatos (nome, sobrenome, email e telefone)

Validação de dados (email válido, pelo menos um contato, campos obrigatórios)

Edição de contatos existentes

Exclusão de contatos

Cadastro de usuário com hash de senha

Login e autenticação

Estrutura do Projeto
projeto-contatos/
│
├─ src/
│   ├─ controllers/       # Controladores para login e contatos
│   ├─ models/            # Models do Mongoose (Contato e Login)
│   ├─ views/             # Páginas EJS
│   └─ routes.js          # Rotas do projeto
│
├─ public/                # Arquivos públicos (CSS, JS, imagens)
├─ package.json
└─ server.js              # Arquivo principal do servidor

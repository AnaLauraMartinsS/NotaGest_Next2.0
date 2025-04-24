# 🧾 NotaGest - Sistema de Gestão de Notas Fiscais

**Projeto Integrador | Full Stack - Next.js + Express.js**

NotaGest é uma aplicação web desenvolvida para auxiliar profissionais da construção civil na **organização digital de notas fiscais e comprovantes**, com foco em **controle financeiro, facilidade de acesso** e **centralização de documentos**.

---

## 🚀 Tecnologias Utilizadas

### 💻 Front-End:
- [Next.js](https://nextjs.org/) com [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [React Icons](https://react-icons.github.io/react-icons/)
- [AOS (Animate on Scroll)](https://michalsnik.github.io/aos/)
- [React Slick Carousel](https://react-slick.neostack.com/)

### 🔧 Back-End:
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- Dados mockados (sem conexão real com banco de dados por enquanto)

---

## ⚙️ Como Executar Localmente

### 🔧 Backend - Express.js

1. Acesse a pasta do backend:
   ```bash
   cd NotaGest_Backend
2. Instale as dependências
      ```bash
   npm install
3. Execute o servidor
      ```bash
   npm run dev

🧪 Testando a API
O servidor ficará disponível em: http://localhost:3001

Você pode testar com ferramentas como:

Insomnia ou Postman

Endpoints disponíveis:

| Método  | Rota            | Descrição                   |
|---------|-----------------|-----------------------------|
| GET     | /api/item       | Lista todos os itens        |
| GET     | /api/item/{id}  | Busca item por ID           |
| POST    | /api/item       | Cria um novo item           |
| PUT     | /api/item/{id}  | Atualiza um item por ID     |
| DELETE  | /api/item/{id}  | Deleta um item por ID       |

💻 Frontend - Next.js

1. Acesse a pasta do front-end:
      ```bash
   cd NotaGest_Front
      
2. Instale as depêndencias
      ```bash
   npm install
      
3. Inicie a aplicção com:
      ```bash
   npm run dev

O app será iniciado em: http://localhost:3000

🌐 Funcionalidades Existentes

✅ Login e cadastro de usuários

✅ Upload de arquivos simulados

✅ API com CRUD básico e dados mockados

🚧 Integração real com banco de dados (em breve)


📌 Adendo

A conexão com banco de dados ainda está em fase de implementação.

Por enquanto os dados estão sendo simulados em memória.

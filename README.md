<h1 align="center">
  <img src="https://ik.imagekit.io/ij3myhonv21/31S0Ht7jUyL_3LcU09hEQ.png">
</h1>

# 📖 Sobre

Segundo desafio da trilha **NodeJS** do **Ignite**. Nesse projeto podemos criar, listar, atualizar e deletar tarefas. Porem dessa vez para um usuário especifico e com um plano free que limita o numero de tarefas em 10. Para mais de 10 tarefas tem o plano Pro que permite criar tarefas ilimitadas.

# 👨‍💻 Tecnologias utilizadas

Nesse projeto utilizamos as seguintes tecnologias:

[![Node Badge](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white&link=https://nodejs.org/en/)](https://nodejs.org/en/)
[![Express Badge](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white&link=https://expressjs.com/pt-br/)](https://expressjs.com/pt-br/)


# 🔀 Rotas da Aplicação

- Criar usuário: POST <http://localhost:3333/users>
- Listar tarefas: GET <http://localhost:3333/todos>
- Criar tarefas: POST <http://localhost:3333/todos>
- Atualizar titulo e deadline: PUT <http://localhost:3333/todos/:id>
- Atualizar done: PATH <http://localhost:3333/todos/:id/done>
- Deletar tarefa: DELETE <http://localhost:3333/todos/:id>

# ⚙️ Get Started

```bash
  # Clone o Repositório:
  $ git clone
   https://github.com/JunioResende/Ignite-Desafio_02-Trabalhando_com_Middlewares.git

  # Entre no Diretório:
  $ cd Ignite-Desafio_02-Trabalhando_com_Middlewares

  # Instale as Dependências do Projeto:
  $ yarn install

  # Inicie:
  $ yarn dev
```
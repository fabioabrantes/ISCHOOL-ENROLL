# API de matrícula de discentes.
### Com o objetivo geral de desenvolver uma API que possa permitir um sistema de matrícula mais gerencial e dinâmico para uma escola de ensino fundamental I. Para permitir que o processo de matrícula escolar e gerenciamento de turmas possam acontecer fora do espaço físico e onde o gerenciamento das turmas criadas possam ser tocados em qualquer momento do dia.

## Casos de usos
- [x] RF_01: Cria Conta - O sistema deve persistir nos seguintes dados obrigatórios do usuário: matrícula, nome, data de nascimento, email, senha, endereço e ocupação.
- [x] RF_02: Atualizar Conta - O sistema deve permitir a atualização nos seguintes dados obrigatórios do usuário: matrícula, nome, data de nascimento, email, senha, endereço eocupação.
- [x] RF_03: Excluir Conta - O sistema deve permitir que o usuário exclua sua conta.
- [x] RF_04: Criar turma - O sistema deve permitir que o usuário diretor possa criar turmas, com os seguintes dados obrigatórios da turma: série e descrição.
- [x] RF_05: Se vincula a uma turma - O sistema deve permitir que o usuário professor possa se vincular a uma turma.
- [x] RF_06: Se matricular em uma turma - O sistema deve permitir que o usuário aluno possa se matricular em uma turma.
- [x] RF_07: Validar vinculação - O sistema deve permitir que o usuário diretor possa validação de um professor por turma.
- [x] RF_08: Validar matrícula - O sistema deve permitir que o usuário diretor valide as matrículas dos alunos na turma.
- [x] RF_09: Visualizar turma - O sistema deve permitir que o usuário possa visualizar as turmas, com sua série e descrição, além dos alunos matriculados na turma e o professor vinculado a mesma.
- [x] RF_10: Editar turma - O sistema deve permitir que o usuário diretor possa editar turmas nos seguintes dados obrigatórios: série e descrição Também permitindo desvincular um professor e invalidar a matrícula de alunos.
- [x] RF_11: Excluir Turma - O sistema deve permitir que o usuário diretor possa excluir turmas.

### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [mongoose](https://mongoosejs.com/)
- [Node.js](https://nodejs.org/en/)
- [React](https://pt-br.reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)

##Sequência para criar o projeto criar o arquivo package
- npm init -y
- yarn add express
- node App.js
- yarn add -g nodemon
- nodemon App.js
- yarn add mongodb
- yarn add mongoose
- yarn add cors


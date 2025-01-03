# Create Users

A interface **Create Users** é uma aplicação **front-end** desenvolvida em **React**. Sua funcionalidade principal é permitir que os usuários realizem o cadastro de novos usuários de forma gráfica e visualizem todos os usuários cadastrados. 

A interface se comunica com uma [API](https://github.com/luigieterovik/create-users-backend) para realizar operações de cadastro e visualização de dados.

<img src="https://i.imgur.com/QhJEgBd.png">

---

## Funcionalidades

- **Cadastro de Usuários**: O usuário pode preencher um formulário gráfico para adicionar novos usuários.
- **Visualização de Usuários**: Uma lista gráfica exibe todos os usuários cadastrados no sistema, consumindo os dados da API.

---

## Tecnologias Utilizadas

- **React**: Biblioteca JavaScript para construção de interfaces.
- **Axios**: Para consumo da [API](https://github.com/luigieterovik/create-users-backend).
- **Styled-Components**: Estilização da interface.

---

## Como Executar

### Pré-requisitos
- Node.js instalado na máquina.
- Gerenciador de pacotes (npm ou yarn).

### Passos
1. Clone o repositório do projeto:
   ```
   git clone <link-do-repositorio>
   ```
3. Instale as dependências:
   ```
   npm install
   ```
   # ou
   ```
   yarn install
   ```
5. Inicie o servidor de desenvolvimento:
   ```
   npm start
   ```
   # ou
   ```
   yarn start
   ```
7. Acesse no navegador:
   ```
   http://localhost:3000
   ```
---

## Configuração da API

A interface consome os dados da [API](https://github.com/luigieterovik/create-users-backend). Certifique-se de que a API esteja em execução antes de iniciar o frontend.

---

## Contribuição

Contribuições são bem-vindas! Siga os passos abaixo para contribuir:

1. Faça um fork do projeto.
2. Crie uma branch para sua funcionalidade:
   git checkout -b minha-nova-funcionalidade
3. Commit suas alterações:
   git commit -m 'Adiciona nova funcionalidade'
4. Faça o push para a branch:
   git push origin minha-nova-funcionalidade
5. Abra um Pull Request.

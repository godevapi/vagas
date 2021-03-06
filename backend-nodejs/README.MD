# Desafio de código Backend NodeJS

Objetivo deste desafio é avaliarmos o seu domínio em back-end, ou seja, sua organização, lógica e boas práticas com o 
código, familiaridade com programação em NodeJs e tecnologias utilizadas.

Boa sorte e obrigado por participar!

## 🚨 As regras do jogo

1. A API deverá ser construída em NodeJS. Nós preferimos NestJs, mas se for optar por outro, justifique sua escolha no README;

2. Implementar autenticação e deverá seguir o padrão JWT, lembrando que o token a ser recebido deverá ser no formato Bearer;

3. Para a comunicação com o banco de dados utilize algum ORM/ODM;

4. Utilizar banco não relacionais permitidos. Nós preferimos MongoDB, mas se for optar por outro, justifique sua escolha no README;

5. Sua API deverá seguir os padrões Rest na construção das rotas e retornos; 

6. Crie um arquivo README que explique como rodar o projeto, como executar quaisquer scripts necessários;

7. A aplicação deve possuir um script que popula o banco de dados inicialmente com conectores fictícios para demonstração.

## 🎁 Bônus

Esses itens não são obrigatórios, porém desejados.

- Testes unitários;
- Linter;
- Code Formater;
- Docker;
- Documentação utilizando Swagger ou ReDoc;
- Utilizar Serverless.

## 🖥 O Desafio

O desafio consiste em criar uma Web API para a DevApi que será consumida pelo portal web. 

Sua API deve conter as seguintes features:

- Listar conectores;
- Filtrar conector por nome, categoria, tipo (REST, BD, SOAP), Privacidade (PUBLIC ou PRIVATE);
- Adicionar conector;
- Editar conector;
- Exclusão lógica. 

### Dados do conector: 

| Campo       |
|-------------|
| Id          |
| Name        |
| Type        |
| Privacy     |
| Base URL    |
| Logo URL    |
| Category    |
| Description |
| Status      |


## 🕵🏻‍♂️ Como vou ser avaliado?

- Estrutura do Projeto;
- Segurança da API, como autenticação, senhas salvas no banco, SQL Injection e outros;
- Boas práticas da Linguagem/Framework;
- Seu projeto deverá seguir tudo o que foi exigido na seção: [As regras do jogo](##--as-regras-do-jogo).

## 🏗 Para onde enviar seu repositório:

Todo o seu código deve ser disponibilizado num repositório **público** ou **privado** em seu Github, Gitlab ou Bitbucket 
pessoal. Envie um email para mariana.ganassin@devapi.com.br com o assunto Desafio Backend NodeJS - [SEU NOME] contendo o link para o repositório que você criou ou faça um pull-request.

## :question: Dúvidas

Envie suas dúvidas diretamente para tais.moura@devapi.com.br.

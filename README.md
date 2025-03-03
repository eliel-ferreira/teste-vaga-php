# Teste para candidatos à vaga de Analista Sistema Melhoria Continua

Olá caro desenvolvedor, nesse teste analisaremos seu conhecimento geral e inclusive velocidade de desenvolvimento. Abaixo explicaremos tudo o que será necessário.

## Instruções

O desafio consiste em implementar uma aplicação web utilizando o PHP, um banco de dados relacional (neste caso o SQLite), que terá como finalidade a inscrição de candidatos a uma oportunidade de emprego.

Sua aplicação deve possuir:

- CRUD de vagas:
  - Criar, editar, excluir e listar vagas.
  - A vaga pode ser CLT, Pessoa Jurídica ou Freelancer.
  
- CRUD de candidatos:
  - Criar, editar, excluir e listar candidatos.
- Um cadidato pode se inscrever em uma ou mais vagas.
- Deve ser possível "pausar" a vaga, evitando a inscrição de candidatos.

- Cada CRUD:
  - Deve ser filtrável (ordenável se possível qualquer campo), e possuir paginação de 10 itens.
  - Deve possuir formulários para criação e atualização de seus itens.
  - Deve permitir a deleção de qualquer item de sua lista.
  - Implementar validações de campos obrigatórios e tipos de dados.
- Deve utilizar compose para realizar autoload (PRS-4)

## Banco de dados

- O banco de dados deve ser criado utilizando populado com as informações no banco de dados.

## Tecnologias a serem utilizadas

Devem ser utilizadas as seguintes tecnologias:

- PHP
- HTML
- CSS
- Javascript
- SQLite

## Entrega

- Para iniciar o teste, faça um fork deste repositório; **Se você apenas clonar o repositório não vai conseguir fazer push.**
- Crie uma branch com o seu nome completo;
- Altere o arquivo README.md com as informações necessárias para executar o seu teste (comandos, migrations, etc);
- Depois de finalizado, envie-nos o pull request;

## Bônus

- API Rest JSON para todos os CRUDS listados acima.
- Permitir deleção em massa de itens nos CRUDs.
- Permitir que o usuário mude o número de itens por página.
- Implementar autenticação de usuário na aplicação.
- Utilizar conceito de migrations para criaação das tabelas do banco de dados
- Utilizar padrão MVC

## O que iremos analisar

- Organização do código;
- Aplicação de design patterns;
- Separação de módulos e componentes;
- Legibilidade;
- Criação do ambiente.

### Boa sorte!
# RocketNotes API

API para o projeto **RocketNotes**, uma aplicação para gerenciar notas e categorias, com recursos de autenticação e busca, desenvolvida com Node.js e Knex.js.

## Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)


## Sobre o Projeto

O RocketNotes é uma aplicação de gerenciamento de notas que permite aos usuários:
- Criar, atualizar e excluir notas.
- Organizar notas com tags.
- Filtrar e buscar notas por tags e título.
- Autenticar e gerenciar perfis de usuários.

## Tecnologias Utilizadas

- **Node.js**: Plataforma de execução para o JavaScript.
- **Docker**: ferramenta que empacota a aplicação junto com tudo que ela precisa para rodar, de forma isolada e previsível..
- **Express**: Framework web para Node.js.
- **Knex.js**: Construtor de consultas SQL para Node.js.
- **SQLite**: Banco de dados utilizado para armazenamento local.
- **bcrypt.js**: Biblioteca para criptografia de senhas.
- **JWT (JSON Web Token)**: Autenticação de usuário baseada em tokens.

## Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:
- Node.js instalado (versão 14 ou superior)
- NPM ou Yarn instalado
- Git instalado

## Instalação

Clone o repositório para o seu ambiente local:

```bash
git clone https://github.com/seu-usuario/rocketnotes-api.git
cd rocketnotes-api

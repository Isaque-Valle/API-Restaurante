# Alfood - Lista de Restaurantes

Este projeto é uma aplicação web chamada **Alfood** que apresenta uma lista de restaurantes e pratos armazenados em uma API. A página também possui uma área administrativa onde o usuário pode registrar novos restaurantes, e as informações são salvas na API.

## Funcionalidades

- Exibição de uma lista de restaurantes e seus pratos.
- Área administrativa para adicionar novos restaurantes.
- Comunicação com a API por meio de requisições **HTTP** utilizando a biblioteca **Axios**.
- A aplicação foi desenvolvida utilizando **React** e **TypeScript**.

## Tecnologias Utilizadas

- **React** para construção da interface.
- **TypeScript** para tipagem estática e maior segurança no código.
- **Axios** para realizar as requisições HTTP à API.
- **Docker** para gerenciamento da API com containers.
- **API** rodando na porta **8000**.

## Requisitos

- **Node.js** e **npm** instalados.
- **Docker** e **Docker Compose** instalados para rodar a API.

Para configurar e rodar a API localmente, siga os passos abaixo:

Navegue até a pasta restaurantes_api-master:
**cd restaurantes_api-master**

Construa a API com o comando:
**docker compose-build**

Inicie a API com o comando:
**docker-compose up**



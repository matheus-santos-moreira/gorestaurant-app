<p align="center">
  <a href="" rel="noopener">
 <img src="https://i.imgur.com/mM4p6H8.png" alt="GoRestaurant"></a>
</p>
<h1 align="center">GoRestaurant Mobile</h1>

<div align="center">


[![GitHub](https://img.shields.io/github/last-commit/matheus-santos-moreira/GoRestaurant-App?style=flat-square)](https://img.shields.io/github/last-commit/matheus-santos-moreira/GoRestaurant-App?style=flat-square)
[![GitHub Languages](https://img.shields.io/github/languages/top/matheus-santos-moreira/GoRestaurant-App?style=flat-square)](https://img.shields.io/github/languages/top/matheus-santos-moreira/GoRestaurant-App?style=flat-square)
[![GitHub Size](https://img.shields.io/github/repo-size/matheus-santos-moreira/GoRestaurant-App?style=flat-square)](https://img.shields.io/github/repo-size/matheus-santos-moreira/GoRestaurant-App?style=flat-square)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

</div>

---

<p align="center">
Nesse desafio do bootcamp GoStack, desenvolvi uma aplicação, a GoRestaurant, a versão mobile para o cliente, um pequeno app para pedidos de comida.
Essa aplicação se conecta a uma Fake API, e exibir e filtrar os pratos de comida da API e permitir a criação de novos pedidos.
    <br>
</p>

## 📝 Tabela de conteúdos

- [Configurando um ambiente local](#getting_started)







## 🏁 Configurando um ambiente local <a name = "getting_started"></a>

Estas instruções fornecerão a você uma cópia do projeto instalado e funcionando em sua máquina local para desenvolvimento
e para fins de teste.

### Pré-requisitos

O que você precisa para instalar o software e como instalá-los.
Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/) e [React Native](https://reactnative.dev/).
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/).


### Utilizando uma fake API

Antes de tudo, para que você tenha os dados para exibir em tela, temos um arquivo que você poderá utilizar como fake API para te prover esses dados.

Para isso, deixamos instalado no seu package.json uma dependência chamada `json-server`, e um arquivo chamado `server.json` que contém os dados para as seguintes rotas:

**Rota `/foods`**: Retorna todas as comidas cadastradas na API

**Rota `/foods/:id`**: Retorna um prato de comida cadastradas na API baseado no `id`

**Rota `/categories`**: Retorna todas as categorias cadastradas na API

**Rota `/orders`**: Retorna todas os pedidos que foram cadastrados na API

**Rota `/favorites`**: Retorna todas as comidas favoritas que foram cadastrados na API

```js
  yarn json-server server.json -p 3333
```



```bash
  # Clone este repositório
  git clone https://github.com/matheus-santos-moreira/GoRestaurant-App

  # Acesse a pasta do projeto no terminal/cmd
  cd GoRestaurant-App

  # Instale as dependências
  yarn install

  # Instale a aplicação em seu emulador ou dispositivo fisíco
  yarn android
    # ou
  yarn ios

  # Execute a aplicação em modo de desenvolvimento
  yarn start
```

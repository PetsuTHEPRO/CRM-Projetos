<div align="center">
  <img src="https://img.shields.io/github/languages/top/ponte-digital-ifma/central-digital?style=for-the-badge&color=563D7C" alt="Linguagem Principal">
</div>

<h1 align="center">
  Central Digital - Programa Ponte Digital
</h1>

<p align="center">
  <img alt="Licença" src="https://img.shields.io/badge/license-MIT-brightgreen?style=flat-square">
  <img alt="Status do Projeto" src="https://img.shields.io/badge/status-em%20desenvolvimento-yellow?style=flat-square">
</p>

<p align="center">
  [cite_start]O projeto "Central Digital" visa modernizar e centralizar as informações dos projetos do programa Ponte Digital, substituindo o site estático atual por uma aplicação moderna com Vue.js e um CMS Headless (WordPress). [cite: 5, 6]
</p>

<p align="center">
 <a href="#-visão-geral">Visão Geral</a> •
 <a href="#-arquitetura-e-tecnologias">Tecnologias</a> •
 <a href="#-pré-requisitos">Pré-requisitos</a> •
 <a href="#-instalação">Instalação</a> •
 <a href="#-como-usar">Como Usar</a> •
 <a href="#-como-contribuir">Como Contribuir</a> •
 <a href="#-licença">Licença</a>
</p>

## 📖 Visão Geral

Este projeto é uma iniciativa do programa **Ponte Digital** para criar uma plataforma centralizada e dinâmica. [cite_start]A aplicação substituirá o site anterior, desenvolvido em HTML e CSS puros [cite: 6][cite_start], por uma Single Page Application (SPA) em **Vue.js**[cite: 8]. [cite_start]Todo o conteúdo do site, como projetos, anúncios e galerias, será gerenciado de forma independente pela equipe através de um painel **WordPress** configurado como Headless CMS [cite: 9, 67][cite_start], com os dados sendo consumidos via API REST[cite: 68].

## 🛠️ Arquitetura e Tecnologias

O projeto é construído utilizando as seguintes tecnologias:

* [cite_start]**Frontend:** [Vue.js](https://vuejs.org/) [cite: 8]
* [cite_start]**Backend (CMS Headless):** [WordPress](https://wordpress.org/) [cite: 9]
* [cite_start]**API:** WordPress REST API [cite: 68]
* **Estilização:** (A ser definido - Ex: TailwindCSS, SCSS)
* **Hospedagem:** (A ser definido - Ex: Netlify, Vercel)

## ✅ Pré-requisitos

Antes de começar, você precisará ter instalado em sua máquina as seguintes ferramentas:
* [Git](https://git-scm.com)
* [Node.js](https://nodejs.org/en/)
* [NPM](https://www.npmjs.com/) ou [Yarn](https://yarnpkg.com/)
* Uma instância do WordPress para o backend.

## 📦 Instalação

Siga os passos abaixo para configurar o ambiente de desenvolvimento:

```bash
# 1. Clone o repositório
$ git clone [https://github.com/ponte-digital-ifma/central-digital.git](https://github.com/ponte-digital-ifma/central-digital.git)

# 2. Acesse a pasta do projeto
$ cd central-digital

# 3. Instale as dependências
$ npm install
# ou
$ yarn install

# 4. Crie um arquivo .env na raiz do projeto e adicione a URL da sua API WordPress
VUE_APP_API_URL=[http://seu-wordpress.local/wp-json/wp/v2/](http://seu-wordpress.local/wp-json/wp/v2/)

# 5. Inicie o servidor de desenvolvimento
$ npm run serve
# ou
$ yarn serve

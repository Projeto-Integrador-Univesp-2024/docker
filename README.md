# Despertando Mentes Jovens: Jornada na Educação Financeira Infantil

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=Projeto-Integrador-Univesp-2024_docker&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=Projeto-Integrador-Univesp-2024_docker)

![GitHub repo size](https://img.shields.io/github/repo-size/Projeto-Integrador-Univesp-2024/docker?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/Projeto-Integrador-Univesp-2024/docker?style=for-the-badge)
![GitHub top language](https://img.shields.io/github/languages/top/Projeto-Integrador-Univesp-2024/docker?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/Projeto-Integrador-Univesp-2024/docker?style=for-the-badge)
![GitHub pull requests](https://img.shields.io/github/issues-pr/Projeto-Integrador-Univesp-2024/docker?style=for-the-badge)
![GitHub](https://img.shields.io/github/license/Projeto-Integrador-Univesp-2024/docker?style=for-the-badge)

> O projeto em questão é uma proposta a introdução de um inovador aplicativo de educação financeira voltado para crianças.

## 💻 Pré-requisitos

Antes de começar, tenha certeza que você tem os requisitos abaixo:

- Você tem o [git](https://git-scm.com) instalado na sua máquina.
- Você tem o [npm](https://www.npmjs.com) ou o [yarn](https://yarnpkg.com) instalado na sua máquina.
- Você tem instalado o [Docker](https://www.docker.com).

Opcional e Detalhes

- Para instalar o yarn, primeiro você precisa ter o [npm](https://www.npmjs.com) instalado, e então instale com o comando `npm install --global yarn`

## 🚀 Instalando Despertando Mentes Jovens

Para instalar o Despertando Mentes Jovens, siga os passos abaixo:

- Primeiro abra seu terminal e crie uma pasta onde irá colocar os arquivos de código usando o comando `mkdir [NOME_DA_PASTA]`

- Após criar a pasta, entre dentro dela usando o comando `cd [NOME_DA_PASTA]`

- Dentro da pasta, clone os projetos:
  - [Docker](https://github.com/Projeto-Integrador-Univesp-2024/docker)
  - [Backend](https://github.com/Projeto-Integrador-Univesp-2024/backend)
  - [Frontend](https://github.com/Projeto-Integrador-Univesp-2024/frontend)

- Para clonar o Docker:
 HTTP: `git clone https://github.com/Projeto-Integrador-Univesp-2024/docker.git`
 or
 SSH: `git clone git@github.com:Projeto-Integrador-Univesp-2024/docker.git`

- Para clonar o Backend:
 HTTP: `git clone https://github.com/Projeto-Integrador-Univesp-2024/backend.git`
 or
 SSH: `git clone git@github.com:Projeto-Integrador-Univesp-2024/backend.git`

- Para clonar o Frontend:
 HTTP: `git clone https://github.com/Projeto-Integrador-Univesp-2024/frontend.git`
 or
 SSH: `git clone git@github.com:Projeto-Integrador-Univesp-2024/frontend.git`

### Para rodar a aplicação

- Após clonar todos os projetos, navegue até `cd docker` e rode o comando:
```bash
docker compose up --build -d
```
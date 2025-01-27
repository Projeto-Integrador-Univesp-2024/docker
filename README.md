
# **Documentação do Docker**

Bem-vindo à documentação oficial do projeto **Jornada na Educação Financeira Infantil**. 
Este documento descreve os pré-requisitos, etapas de instalação, e como executar o ambiente utilizando Docker.

---

## **1. Visão Geral**
O projeto tem como objetivo criar um aplicativo inovador de educação financeira para crianças, com o backend, frontend e banco de dados integrados por meio de contêineres Docker.

### **1.1 Tecnologias Utilizadas**
- Docker
- Docker Compose

---

## **2. Pré-requisitos**
Antes de começar, certifique-se de que o ambiente atende aos seguintes pré-requisitos:

- Git: [Instale o Git](https://git-scm.com/).
- Node.js/NPM ou Yarn: [Instale o Node.js e NPM](https://nodejs.org/) ou [Yarn](https://yarnpkg.com/).
- Docker: [Instale o Docker](https://www.docker.com/).
- Docker Compose: Incluído no Docker Desktop ou instale separadamente.

### **2.1 Requisitos Opcionais**
```bash
	npm install --global yarn
```

---

## **3. Estrutura do Projeto**

O projeto é dividido em três principais repositórios:

-   **Docker**: Configuração de contêineres e orquestração.
-   **Backend**: API do sistema.
-   **Frontend**: Interface do usuário.

---

## **4. Instalação**


Siga as etapas abaixo para clonar os repositórios e configurar o ambiente:

### **4.1. Criar um Diretório**

Abra o terminal e crie um diretório para os arquivos do projeto:
```bash
	mkdir [NOME_DA_PASTA]
	cd [NOME_DA_PASTA]
```

### **4.2. Clonar os Repositórios**
Clone os repositórios usando **HTTP** ou **SSH**:
-   **Docker**:
    ```bash
	    git clone https://github.com/Projeto-Integrador-Univesp-2024/docker.git
	    # ou via SSH
	    git clone git@github.com:Projeto-Integrador-Univesp-2024/docker.git
    ```
-   **Backend**:
    ```bash
	    git clone https://github.com/Projeto-Integrador-Univesp-2024/backend.git
	    # ou via SSH
	    git clone git@github.com:Projeto-Integrador-Univesp-2024/backend.git
    ``` 
-   **Frontend**:
    ```bash
	    git clone https://github.com/Projeto-Integrador-Univesp-2024/frontend.git
	    # ou via SSH
	    git clone git@github.com:Projeto-Integrador-Univesp-2024/frontend.git
    ```
    
---

## **5. Executando a Aplicação**
Após clonar os repositórios, siga as etapas abaixo para iniciar o ambiente:

### **5.1. Navegar até o Diretório Docker**
```bash
	cd docker
```
### **5.2. Construir e Subir os Contêineres**
Execute o comando:
```bash
	docker compose up --build -d
```
### **5.3. Verificar os Contêineres**
Para verificar se os contêineres estão em execução:
```bash
	docker ps
```

---

© 2025 Jornada na Educação Financeira Infantil. Todos os direitos reservados.
# API REST para Gerenciamento de Tarefas

Backend RESTful para o sistema de lista de tarefas, construído com Spring Boot.

<p align="center">
  <img src="https://img.shields.io/badge/Java-21-blue?style=for-the-badge&logo=java" alt="Java 21">
  <img src="https://img.shields.io/badge/Spring_Boot-3-success?style=for-the-badge&logo=spring" alt="Spring Boot 3">
  <img src="https://img.shields.io/badge/Maven-4-red?style=for-the-badge&logo=apache-maven" alt="Maven">
  <img src="https://img.shields.io/badge/PostgreSQL-16-blue?style=for-the-badge&logo=postgresql" alt="PostgreSQL">
</p>

<details>
  <summary><strong>📝 Descrição do Projeto</strong></summary>
  <br>
  Esta API atua como o backend da aplicação “Lista de Tarefas”, disponibilizando endpoints REST para operações completas de CRUD (Criar, Ler, Atualizar, Excluir) sobre as tarefas.

  O desenvolvimento foi baseado no tutorial “Projeto Aplicação Full Stack” do professor Ricardo Tec.
</details>

## 🏛️ Organização do Projeto

Este repositório é responsável pelo backend da solução “Lista de Tarefas”, que está dividida em três partes para melhor modularização e manutenção:

- **Backend (API REST):** Serviço RESTful criado com Spring Boot para gerenciar a lógica da aplicação.
- **Frontend (Web):** Interface web feita com Angular.
  - Repositório: [https://github.com/KauanLourenti/listadetarefas-WEB.git](https://github.com/KauanLourenti/listadetarefas-WEB.git)


## 💻 Tecnologias Utilizadas

- **Linguagem:** Java 21  
- **Framework:** Spring Boot 3  
- **Banco de Dados:**  
  - H2 (para ambiente de desenvolvimento)  
  - PostgreSQL (para produção)  
- **Gerenciamento de Dependências:** Maven  
- **ORM:** Spring Data JPA com Hibernate  

## 🚀 Guia para Rodar a API

1. Clone o repositório:  
    ```bash
    git clone https://github.com/ZagoGiovanni/Projeto-Java-Spring-API.git
    ```

2. Acesse o diretório do projeto:  
    ```bash
    cd lista-tarefas-api
    ```

3. Ajuste as configurações do banco de dados no arquivo `src/main/resources/application.properties`.

4. Inicie a aplicação:  
    ```bash
    mvn spring-boot:run
    ```

5. A API estará disponível em `http://localhost:8080`.

## Endpoints Disponíveis

- `GET /api/tarefas` — Retorna a lista completa de tarefas.
- `POST /api/tarefas` — Cria uma nova tarefa.
- `PUT /api/tarefas/{id}` — Atualiza uma tarefa específica.
- `DELETE /api/tarefas/{id}` — Exclui uma tarefa.

## Sobre o Autor

**kauan de Padua Lourenti**


- GitHub: [https://github.com/KauanLourenti](https://github.com/KauanLourenti)

# Projeto Fullstack: Quarkus + Vue + MongoDB

Este projeto é uma prova de conceito (PoC) para demonstrar uma arquitetura de microsserviços moderna utilizando Java e SPA.

## 🏗 Arquitetura

O projeto está estruturado como um Monorepo:
- **/backend**: API RESTful desenvolvida com Quarkus (Java).
- **/frontend**: Single Page Application desenvolvida com Vue.js.
- **/infra**: Arquivos de Infraestrutura como Código (Docker Compose).

## 🚀 Tecnologias

- **Quarkus**: Supersonic Subatomic Java.
- **MongoDB**: Banco de dados NoSQL orientado a documentos.
- **Vue.js**: Framework JavaScript progressivo.
- **Docker**: Containerização.

## 🛠 Como rodar o ambiente (Infraestrutura)

Pré-requisitos: Docker e Docker Compose instalados.

```bash
# Na raiz do projeto, suba o banco de dados:
docker-compose up -d

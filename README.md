# Enquete em Tempo Real com Fastify, Prisma e Redis

Sistema de enquetes em tempo real desenvolvido com Fastify, Prisma e Redis, utilizando PostgreSQL para armazenamento eficiente.

## Tecnologias Utilizadas

- **Framework Web:** Fastify
- **Banco de Dados:** PostgreSQL (via Prisma)
- **Cache:** Redis
- **Comunicação em Tempo Real:** WebSocket
- **Gerenciamento de Dependências:** npm
- **ORM (Object-Relational Mapping):** Prisma
- **Validação de Dados:** Zod
- **Integração com Banco de Dados:** Prisma Client
- **Controle de Votação:** Redis e Prisma
- **Persistência de Dados:** Prisma Client
- **Containerização:** Docker

## Funcionalidades e Aprendizados
- Desenvolvimento de uma aplicação de enquetes em tempo real com Fastify
- Utilização do Prisma como ORM para interação com PostgreSQL
- Implementação de WebSocket para atualizações em tempo real
- Uso de Redis para gerenciamento de cache e controle de votação
- Integração de Docker para facilitar a implantação e execução do projeto
- Utilização de Zod para validação de dados
- Arquitetura eficiente com controle de votação e persistência de dados

## Como Executar
1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    ```

2. Entre no diretório do projeto:
    ```bash
    cd nome-do-repositorio
    ```

3. Inicie os serviços usando Docker Compose:
    ```bash
    docker-compose up
    ```

4. O servidor estará disponível em http://localhost:3333.

## Autor
- GitHub: [@JeanClaro](https://github.com/JeanClaro)
- LinkedIn: [Jean Claro](https://www.linkedin.com/in/jeanclaro/)

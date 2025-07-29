echo "# Documentação da Arquitetura

Este documento descreve a arquitetura do sistema **controle-fluxo-Carrefour**.

## Visão Geral

- Projeto com arquitetura orientada a eventos
- Microsserviços Spring Boot: launch-service, daily-summary
- Banco de dados PostgreSQL
- Mensageria Redis Streams
- Containerização com Docker e Kubernetes

## Componentes Principais

- launch-service: serviço de entrada de lançamentos financeiros
- daily-summary: serviço de geração de saldo diário consolidado

## Tecnologias Utilizadas

- Java 17
- Spring Boot 3.2.4
- Maven
- Redis
- PostgreSQL
- Docker / Kubernetes

" > docs/arquitetura.md

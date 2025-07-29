# 🧠 Decisões Arquiteturais

Este documento apresenta as principais decisões tomadas na construção da arquitetura do projeto **Desafio Fluxo de Caixa**, com foco em boas práticas, escalabilidade e separação clara de responsabilidades.

---

## 🏗️ Padrões Aplicados

- **Arquitetura em camadas**: separação entre apresentação, aplicação, domínio e infraestrutura.
- **DDD (Domain-Driven Design)**: estrutura orientada a domínios e subdomínios de negócio.
- **Inversão de dependências**: interfaces utilizadas para desacoplar repositórios e serviços.
- **Tratamento centralizado de erros**: middleware para capturar exceções e formatar respostas.

---

## 📦 Tecnologias e Ferramentas

| Camada       | Tecnologia             |
|--------------|------------------------|
| Banco de Dados | PostgreSQL            |
| Backend        | Node.js + TypeScript |
| Containerização | Docker                |
| Autenticação   | JWT                   |

---

## 🧱 Regras e Convenções

- Código modular e reutilizável
- Testes unitários com cobertura mínima de 80%
- Nomeação padronizada (camelCase para variáveis, PascalCase para classes)
- Organização por domínios no backend

---

## 🚀 Estratégias de Deploy

- **Ambiente containerizado** com Docker Compose
- **Banco com migrations automatizadas** usando ferramentas como Prisma ou Sequelize
- CI/CD em fase de planejamento, com foco em integração com GitHub Actions

---

Essas decisões garantem uma base sólida e extensível para o projeto, facilitando manutenção futura e inclusão de novos domínios sem impacto crítico na estrutura existente.



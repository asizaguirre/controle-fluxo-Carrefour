# 🧱 Domínios e Requisitos

Este documento apresenta o mapeamento dos principais domínios do sistema, suas funcionalidades e os requisitos técnicos e funcionais esperados.

---

## 🔷 Domínio: Financeiro

- Cadastro de transações financeiras
- Categorização por tipo (receita, despesa, transferência)
- Geração de extrato por período
- Cálculo de saldo acumulado
- Visualização de fluxo em dashboard

---

## 🔐 Domínio: Autenticação e Autorização

- Login com autenticação via JWT
- Perfis com diferentes permissões (admin, operador)
- Cadastro e edição de usuários
- Controle de acesso baseado em domínio

---

## 🔁 Domínio: Integração de Dados

- Importação de arquivos CSV com transações
- Validação de dados e tratamento de erros
- Consulta a API externa de câmbio
- Cache local de cotação de moedas

---

## 🏗️ Domínio: Infraestrutura

- Banco de dados relacional (PostgreSQL) com migrations
- Containers via Docker para ambientes padronizados
- Configuração de ambiente de desenvolvimento e produção

---

## ✅ Requisitos Não Funcionais

- Segurança com criptografia de dados sensíveis
- Performance com indexação e cache inteligente
- Escalabilidade com organização modular por domínios
- Testabilidade com cobertura mínima de 80% e CI em fase de planejamento



# 💰 Plataforma Financeira — Pipeline & Análise de Dados com Python e MySQL

Projeto end-to-end desenvolvido em **Python** integrado ao banco de dados relacional **MySQL** (`plataforma_db`) para ingestão, armazenamento estruturado e análise de transações financeiras.

---

## 🎯 Objetivo do Projeto
Organizar movimentações financeiras em uma arquitetura modular que separa a camada de banco de dados, a ingestão de registros e a análise dos indicadores, servindo como base prática para engenharia e análise de dados.

---

## 🗂️ Estrutura do Repositório

```text
plataforma-financeira/
├── src/
│   ├── database/      # Conexão e configuração do banco MySQL (plataforma_db)
│   ├── ingestion/     # Rotinas de entrada, tratamento e carga de transações
│   ├── analise.py     # Consultas e análise exploratória dos dados financeiros
│   └── main.py        # Orquestração e execução principal do sistema
├── .gitignore
└── README.md

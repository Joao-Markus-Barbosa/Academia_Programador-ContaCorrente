# 💳 Sistema de Conta Corrente - C# (.NET Console)

Este projeto foi desenvolvido como uma **atividade da Academia do Programador**, simulando um **sistema bancário de conta corrente**, utilizando conceitos sólidos de **Programação Orientada a Objetos (POO)** em C#. O sistema permite a criação e gestão de múltiplas contas com operações bancárias reais.

---

## 🎯 Funcionalidades

- 📌 Criar conta corrente com titular e limite de crédito
- 💰 Depósito e saque com controle de saldo e limite
- 🔁 Transferência entre contas
- 📄 Emissão de extrato com histórico detalhado de movimentações
- 💹 Consulta de saldo atualizado
- 📋 Listagem de contas existentes
- 🧠 Menu interativo via terminal (console)

---

## 💡 Tecnologias Utilizadas

- Linguagem: **C#**
- Plataforma: **.NET Console Application**
- Paradigma: **Programação Orientada a Objetos**
- Estrutura modular com classes separadas:
  - `ContaCorrente`
  - `Movimentacao` (+ enum `TipoMovimentacao`)
  - `Banco`
  - `Program` (execução e menu)

---

## 🧱 Estrutura das Classes

```text
├── Program.cs           // Menu interativo
├── Banco.cs             // Gestão de múltiplas contas
├── ContaCorrente.cs     // Operações da conta (depósito, saque, etc.)
└── Movimentacao.cs      // Representação de cada transação bancária

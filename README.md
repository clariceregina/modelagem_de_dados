
# 💳 Modelagem de Dados – Flexempresta

Este repositório contém o **modelo conceitual de dados** do sistema **Flexempresta**, desenvolvido como parte de um exercício acadêmico com foco em modelagem de banco de dados para um sistema de gestão financeira com empréstimos e contas bancárias.

![Modelo Conceitual](./Modelagem%20de%20dados%20Flexempresta%20-%20Modelo%20Conceitual.vpd.png)

## 🧠 Objetivo

O objetivo desta modelagem é representar de forma conceitual os principais processos e entidades de um sistema financeiro, incluindo:

- Gestão de clientes
- Cadastro e controle de contas
- Empréstimos e pagamentos
- Avaliação de score de crédito
- Estrutura interna de colaboradores e departamentos

---

## 🧾 Notação Utilizada (Modelo Entidade-Relacionamento)

A modelagem segue a notação clássica ER, com os seguintes elementos:

- **Entidade**: representada por **retângulos** (ex: `Clientes`, `Conta`)
- **Entidade fraca**: representada por **retângulo com borda dupla**
- **Relacionamento**: representado por **losangos** (ex: `Possui / Pertence`, `Feito / Fazer`)
- **Atributo**: representado por **elipses** (ex: `nome`, `CPF`, `email`)
- **Atributo chave**: representado por **elipse com texto sublinhado** (ex: `IDCliente`)
- **Entidade associativa**: representada por **losango dentro de um quadrado**
- **Atributo multivalorado**: representado por **elipse com borda dupla**
- **Cardinalidade**: indicada por **números entre parênteses** próximos às conexões (ex: `(1,n)`, `(0,1)`)

Essa convenção permite identificar visualmente a estrutura lógica do banco de dados de forma clara e padronizada.

---

## 🛠️ Ferramenta Utilizada

- **Visual Paradigm (non-commercial use)**  
  Utilizado para a criação do modelo conceitual, com notação Entidade-Relacionamento (ER).

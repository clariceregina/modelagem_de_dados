
# 💳 Modelagem de Dados – Flexempresta

Este repositório contém o **modelo conceitual e lógico de dados** do sistema **Flexempresta**, desenvolvido como parte de um exercício acadêmico com foco em modelagem de banco de dados para um sistema de gestão financeira com empréstimos e contas bancárias.

## 🧠 Objetivo

O objetivo desta modelagem é representar de forma conceitual os principais processos e entidades de um sistema financeiro, incluindo:

- Gestão de clientes
- Cadastro e controle de contas
- Empréstimos e pagamentos
- Avaliação de score de crédito
- Estrutura interna de colaboradores e departamentos

## 🧱 Modelo Conceitual de Dados

O diagrama abaixo representa o modelo conceitual do sistema **Flexempresta**, desenvolvido com a notação Entidade-Relacionamento (ER).

![Modelo Conceitual](./Modelagem%20Conceitual%20de%20dados%20Flexempresta.png)

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

## 🧩 Modelo Lógico de Dados

Abaixo está o modelo lógico do sistema **Flexempresta**, onde as entidades foram transformadas em tabelas relacionais com suas respectivas **chaves primárias (PK)** e **chaves estrangeiras (FK)**.

![Modelo Lógico](./Modelagem%20Lógica%20de%20dados%20Flexempresta.jpg)

### Características do Modelo Lógico

- **Nome de tabelas com prefixo "Tabela"** para manter consistência.
- **Chaves primárias** indicadas por `PK` e **chaves estrangeiras** por `FK`.
- **Relacionamentos normalizados**, mantendo a integridade referencial entre as tabelas.
- Tabelas associativas, como `TabelaClienteConta`, representam relacionamentos `n:n`.

Este modelo lógico serve como base para a criação do **modelo físico**, onde serão definidos tipos de dados e constraints em SQL.

## 🛠️ Ferramenta Utilizada

- **Visual Paradigm (non-commercial use)**  
  Utilizado para a criação do modelo conceitual, com notação Entidade-Relacionamento (ER).


# 💳 Modelagem de Dados – Flexempresta

Este repositório contém a modelagem de dados do sistema **Flexempresta**, abordando os modelos conceitual, lógico e físico com base na metodologia Entidade-Relacionamento (ER).

## 🧱 Modelo Conceitual de Dados

O diagrama abaixo representa o modelo conceitual do sistema **Flexempresta**, desenvolvido com a notação Entidade-Relacionamento (ER).

![Modelo Conceitual](./Modelagem%20Conceitual%20de%20dados%20Flexempresta.png)

### Notação Utilizada (Modelo Entidade-Relacionamento)

A modelagem segue a notação clássica ER, com os seguintes elementos:

- **Entidade**: representada por **retângulos** (ex: `Clientes`, `Conta`)
- **Entidade fraca**: representada por **retângulo com borda dupla**
- **Relacionamento**: representado por **losangos** (ex: `Possui / Pertence`, `Feito / Fazer`)
- **Atributo**: representado por **elipses** (ex: `nome`, `CPF`, `email`)
- **Atributo chave**: representado por **elipse com texto sublinhado** (ex: `IDCliente`)
- **Entidade associativa**: representada por **losango dentro de um quadrado**
- **Atributo multivalorado**: representado por **elipse com borda dupla**
- **Cardinalidade**: indicada por **números entre parênteses** próximos às conexões (ex: `(1,n)`, `(0,1)`)

## 🧩 Modelo Lógico de Dados

Abaixo está o modelo lógico do sistema **Flexempresta**, onde as entidades foram transformadas em tabelas relacionais com suas respectivas **chaves primárias (PK)** e **chaves estrangeiras (FK)**.

![Modelo Lógico](./Modelagem%20Lógica%20de%20dados%20Flexempresta.jpg)

### Características do Modelo Lógico

- **Nome de tabelas com prefixo "Tabela"** para manter consistência.
- **Chaves primárias** indicadas por `PK` e **chaves estrangeiras** por `FK`.
- **Relacionamentos normalizados**, mantendo a integridade referencial entre as tabelas.
- Tabelas associativas, como `TabelaClienteConta`, representam relacionamentos `n:n`.

## 🧮 Modelo Físico de Dados

Abaixo está o modelo físico de dados, que detalha os tipos de dados, restrições de integridade e relacionamentos usados no banco da aplicação **Flexempresta**.

![Modelo Físico](./Modelagem%20Física%20de%20dados%20Flexempresta.jpg)

## 🛠️ Ferramenta Utilizada

- **Visual Paradigm (non-commercial use)**  
  Utilizado para a criação do modelo conceitual, com notação Entidade-Relacionamento (ER).
  O arquivo com extensão .vpd (extensão do Visual Paradigm) também está disponível no repositório.

# 📊 Business Intelligence Dashboard

<p align="center">

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-005C99?style=for-the-badge)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![ETL](https://img.shields.io/badge/ETL-Data%20Preparation-blue?style=for-the-badge)

</p>

---

## 📌 Sobre o Projeto

Este projeto consiste no desenvolvimento de um **Dashboard de Business Intelligence** construído no **Power BI**, contemplando todas as etapas de um projeto analítico:

- Extração dos dados
- Tratamento e transformação (ETL)
- Modelagem de Dados
- Criação de medidas em DAX
- Storytelling
- Design de Dashboard
- Geração de Insights

O objetivo foi transformar dados operacionais em informações estratégicas para apoiar a tomada de decisão por meio de uma interface intuitiva e visualmente agradável.

---

## 🎥 Demonstração

<p align="center">
  <img src="./assets/dashboard-demo.gif" alt="Dashboard Preview" width="100%">
</p>

## 🖼️ Páginas do Dashboard

### 📈 Visão Geral

- Faturamento Total
- Quantidade de Ciclos
- Quantidade de Usuários
- Quantidade de Condomínios
- Ticket Médio
- Evolução Mensal

---

### 👥 Clientes

- Quantidade de Usuários
- Ticket Médio por Usuário
- Média de Ciclos por Usuário
- Percentual de Usuários Isentos
- Ranking de Usuários

---

### 🏢 Condomínios

- Quantidade de Condomínios
- Ticket Médio por Condomínio
- Média de Ciclos
- Ranking por Faturamento
- Ranking por Utilizações

---

### ⚙️ Operação

- Quantidade de Máquinas
- Média de Ciclos por Máquina
- Faturamento Médio por Máquina
- Distribuição por Tipo de Máquina

---

### 📊 Utilização

- Evolução das Utilizações
- Evolução do Faturamento
- Ticket Médio
- Utilizações por Dia da Semana

---

### 💡 Insights

Página destinada à interpretação dos resultados encontrados durante a análise.

---

# 🛠 Tecnologias Utilizadas

- Power BI Desktop
- DAX
- Power Query
- Excel
- ETL
- Modelagem Dimensional
- Storytelling
- Dashboard Design

---

# 📂 Estrutura do Projeto

```text
📁 Dashboard-BI
│
├── Dashboard.pbix
├── README.md
│
├── 📁 Images
│   ├── capa.png
│   ├── visao-geral.png
│   ├── clientes.png
│   ├── condominios.png
│   ├── operacao.png
│   ├── utilizacao.png
│   └── insights.png
│
├── 📁 Video
│   └── dashboard-demo.mp4
│
└── 📁 Documentacao
    ├── DAX.docx
    ├── PowerQuery.docx
    └── ModeloDados.png
```

---

# 📐 Modelagem de Dados

O projeto foi desenvolvido utilizando um **modelo estrela**, composto por:

### Tabelas Dimensão

- Clientes
- Máquinas
- Condomínios

### Tabela Fato

- Utilizações

Relacionamentos:

```text
Clientes
     │
     ▼
Utilizações
     │
     ▼
Máquinas
     │
     ▼
Condomínios
```

---

# 🔄 ETL

O tratamento dos dados foi realizado utilizando **Power Query**.

Principais etapas:

✔ Padronização dos tipos de dados

✔ Remoção de registros duplicados

✔ Limpeza de IDs

✔ Tratamento de caracteres especiais

✔ Tratamento de valores nulos

✔ Padronização dos nomes dos registros

✔ Ajuste dos tipos das colunas

---

# 📊 Indicadores Desenvolvidos

## Visão Geral

- Faturamento Total
- Ticket Médio
- Quantidade de Ciclos
- Quantidade de Usuários
- Quantidade de Condomínios

## Clientes

- Ticket Médio por Usuário
- Média de Ciclos por Usuário
- Percentual de Usuários Isentos

## Condomínios

- Ticket Médio por Condomínio
- Média de Ciclos por Condomínio

## Operação

- Quantidade de Máquinas
- Média de Ciclos por Máquina
- Faturamento Médio por Máquina

---

# 📈 Storytelling

O dashboard foi desenvolvido seguindo princípios de **Storytelling com Dados**, permitindo que cada página responda perguntas específicas do negócio.

O fluxo de navegação foi estruturado da seguinte forma:

```text
Visão Geral
      ↓
Clientes
      ↓
Condomínios
      ↓
Operação
      ↓
Utilização
      ↓
Insights
```

---

# 💡 Principais Aprendizados

Durante este projeto foi possível aprofundar conhecimentos em:

- ETL
- DAX
- Power Query
- Modelagem Dimensional
- Storytelling
- UX para Dashboards
- Data Visualization
- Business Intelligence

---

# 👨‍💻 Autor

**Henrique Sousa**

Analista de Dados | Business Intelligence

📌 LinkedIn

> [https://www.linkedin.com/in/SEU-LINK](https://www.linkedin.com/in/henriquesousaa/)

---

## ⭐ Se gostou do projeto

Deixe uma ⭐ no repositório.

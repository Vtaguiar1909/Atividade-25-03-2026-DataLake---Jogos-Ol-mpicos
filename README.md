# 📊 Atividade Data Lake

## 📌 Descrição
A proposta deste projeto consiste em criar uma pipeline **ETL** utilizando a arquitetura **Medallion**, conforme proposto pelo professor Cuevas.  
O objetivo é organizar os dados em diferentes camadas, garantindo melhor estruturação, rastreabilidade e performance no processamento.

---

## 🏗️ Arquitetura Medallion

A pipeline é dividida em três camadas principais:

### 🟫 RAW (Dados Brutos)
- Armazenamento dos dados em seu formato original.
- Os arquivos são mantidos em uma pasta chamada `RAW`.
- Geração automática de metadados no formato **JSON**.

---

### 🟪 Bronze (Dados Tratados)
- Conversão dos dados brutos para um formato otimizado.
- Transformação dos arquivos para o formato **Parquet**.
- Preservação da estrutura original dos dados, com melhorias para processamento.

---

### 🟨 Gold (Dados Refinados)
- Dados estruturados e prontos para consumo.
- Informações tratadas e organizadas para análise.
- Ideal para uso em dashboards, relatórios e aplicações.

---

## 🚀 Objetivo
Implementar uma pipeline ETL eficiente, seguindo boas práticas de engenharia de dados, utilizando a arquitetura Medallion para garantir:
- Organização dos dados  
- Facilidade de manutenção  
- Melhor desempenho nas consultas  

---

## 📂 Estrutura de Pastas (Exemplo)
data/<br>
├── raw/<br>
├── bronze/<br>
└── gold/<br>
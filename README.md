[← Voltar ao Portfólio de Engenharia de Dados](https://github.com/joycequoos/Data_Enginer/blob/main/README.md)

# Google Cloud BigQuery

Estudo prático sobre o BigQuery, data warehouse gerenciado da Google Cloud — desde a criação da conta até consultas SQL básicas e intermediárias.

## Sumário

- [O que é o BigQuery](#o-que-é-o-bigquery)
- [Criando sua conta gratuita](#criando-sua-conta-gratuita)
- [Conhecendo a estrutura](#conhecendo-a-estrutura)
- [Criando um projeto](#criando-um-projeto)
- [Criando dataset e tabelas](#criando-dataset-e-tabelas)
- [Primeiras consultas SQL](#primeiras-consultas-sql)
- [Funções de restrição (WHERE, IN, IS NULL)](#funções-de-restrição)
- [Principais aprendizados](#principais-aprendizados)

---

## O que é o BigQuery

O BigQuery é um data warehouse totalmente gerenciado e sem servidor oferecido pela Google Cloud. Ele foi projetado para armazenar e analisar grandes volumes de dados de forma rápida e eficiente, permitindo executar consultas SQL em escala de petabytes sem gerenciar infraestrutura.

**Principais benefícios:**
- Simplificação da análise de dados: centraliza dados de diferentes fontes (Finanças, RH, Vendas) em um só lugar
- Sem necessidade de gerenciamento de servidor
- Escalável para grandes volumes de dados

---

## Criando sua conta gratuita

Passo a passo em vídeo: https://www.youtube.com/watch?v=tsJrsgSIoPo

---

## Conhecendo a estrutura

Acessando o BigQuery pela primeira vez:

![Acesso ao BigQuery](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/01_Acesso_Big_Query.jpg)

---

## Criando um projeto

![Criar novo projeto](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/02_Novo_Projeto.jpg)
![Projeto criado](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/Criando_Projeto.png)

---

## Criando dataset e tabelas

### Criando o Data Set (conjunto de dados)

![Criar conjunto de dados](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/03_Criar_Conjunto_Dados.jpg)
![Conjunto de dados criado](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/04_Conjunto_Dados_2.png)
![Dataset de vendas](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/05_Vendas.png)

### Criando tabela via upload de arquivo

![Criar tabela](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/06_CriarTabela.jpg)
![Upload de arquivo](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/07_Criacao_Tabela_Upload.jpg)
![Selecionar arquivo](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/08_Selecionar_Arquivo_Criacao.jpg)

---

## Primeiras consultas SQL

### SELECT * (primeira consulta)

![Primeira consulta](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/09_Primeiro_Select.jpg)
![Consulta executada](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/10_Consulta.png)
![Execução da consulta](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/11_Primeira_Exec_Consulta.png)

### SELECT DISTINCT

Exemplo prático: identificar em quantos estados diferentes há clientes cadastrados.

![Select Distinct](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/12_Select_Distinct.png)

### Renomeando colunas e salvando como tabela

![Alterar nomes de colunas](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/13_Alterar_Nomes_Colunas.png)
![Salvar como tabela](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/14_Salvar_Como_Tabela1.png)
![Tabela criada](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/15_Tabela_Big_Query.png)
![Salvando tabela](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/16_Salvando_Tabela.png)
![Tabela salva](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/17_Tabela_Salva.jpg)

### Salvando consultas personalizadas

![Contatos de clientes](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/18_Contatos_Clientes.png)
![Consultas salvas](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/19_Consultas_Salvas.jpg)

---

## Funções de restrição

### WHERE, IN, NOT IN

![Usando WHERE](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/19_Utilizando_Where.png)
![Usando IN](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/20_Utilizando_IN.png)
![Usando NOT IN](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/21_Utilizando_Not_IN.png)

### IS NULL / IS NOT NULL

![IS NULL](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/22_Email_IsNull.png)
![IS NOT NULL](https://github.com/joycequoos/GoogleCloud_BigQuer/raw/main/img/23_Email_IsNotNull.png)

---

## Principais aprendizados

- Criação e configuração de um projeto no Google Cloud / BigQuery
- Estruturação de datasets e tabelas, incluindo upload de arquivos
- Consultas SQL básicas (`SELECT`, `SELECT DISTINCT`) e de restrição (`WHERE`, `IN`, `NOT IN`, `IS NULL`)
- Organização e reutilização de consultas salvas

**Próximos passos:** funções de agregação (`GROUP BY`, `COUNT`, `SUM`), JOINs entre tabelas, particionamento e clustering de tabelas para otimização de custo/performance.

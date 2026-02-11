# 📊 Pipeline de Análise Salarial com GenIA

Este projeto é uma pipeline de dados ponta a ponta desenvolvida para extrair, transformar e analisar dados salariais de uma empresa, utilizando **Python** e conceitos de **Engenharia de Dados**.

## 🚀 Objetivo
O objetivo principal é calcular a média salarial por setor e identificar há quanto tempo cada funcionário está sem reajuste salarial, facilitando a tomada de decisão do RH.

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python 3.x
* **Banco de Dados:** SQLite (Relacional)
* **Bibliotecas:** * `Pandas`: Manipulação e análise de dados.
    * `SQLAlchemy`: Conexão e extração de dados do banco.
    * `DateTime`: Cálculo de períodos de tempo.
* **IA Generativa:** Utilizada para estruturar o prompt de criação e lógica do script.

## 📈 Funcionalidades
- [x] Simulação de banco de dados relacional.
- [x] Extração automatizada de dados.
- [x] Cálculo de média salarial agrupada por departamento.
- [x] Medição de tempo (em dias) desde o último aumento salarial.

## 📁 Estrutura do Projeto
* `pipeline.py`: Script principal contendo toda a lógica ETL (Extract, Transform, Load).
* `empresa.db`: Arquivo de banco de dados gerado automaticamente.
* `README.md`: Documentação do projeto.

## 🔧 Como Executar
1. Clone este repositório:
   ```bash
   git clone [https://github.com/SEU_USUARIO/pipeline-analise-salarial.git](https://github.com/SEU_USUARIO/pipeline-analise-salarial.git)

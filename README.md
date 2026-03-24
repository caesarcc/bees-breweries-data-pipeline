# bees-breweries-data-pipeline

Este repostiório implementa um pipeline de dados baseado em arquitetura Metallion (bronze, silver, gold) utilizando:

- Apache Airflow para orquestração
- Python para processamento de dados
- PySpark para transformação de dados
- Docker para containerização
- Delta Lake para armazenamento de dados

O objetivo é extrair dados de uma API pública de cervejarias, processá-los e armazená-los em um formato otimizado para análise.
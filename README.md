# bees-breweries-data-pipeline

Este repositório implementa um pipeline de dados baseado em arquitetura Metallion (bronze, silver, gold) utilizando:

- Python para processamento de dados
- Apache Airflow para orquestração
- Apache Spark para transformação de dados (Usando um master + 2 workers)
- Delta Lake para armazenamento de dados (Usando MinIO para simular um ambiente 100% compativel com o AWS S3)
- Docker para containerização (docker-compose para orquestrar os serviços em linux containers)
- PostgreSQL para o banco de dados do Airflow (evitando o uso do SQLite, que é recomendado apenas para desenvolvimento)

O objetivo é extrair dados de uma API pública de cervejarias, processá-los e armazená-los em um formato otimizado para análise.
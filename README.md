# Projeto de Inserção de Dados em Banco PostgreSQL

Este projeto tem como objetivo inserir dados de um arquivo CSV em uma tabela PostgreSQL, usando a linguagem Python. O processo inclui a leitura do arquivo CSV em chunks (partes) para evitar sobrecarga de memória e inserir os dados em uma tabela chamada `tabela_bronze_reviews`. Além disso, o código utiliza as bibliotecas `psycopg2` para conectar ao PostgreSQL e `pandas` para manipulação eficiente dos dados.

## Requisitos

Para executar este projeto, você precisará dos seguintes requisitos:

- Python 3.x
- PostgreSQL (instalado e configurado)
- Bibliotecas Python:
  - `psycopg2`: Para interagir com o banco de dados PostgreSQL.
  - `pandas`: Para manipulação e leitura de dados em CSV.

Você pode instalar as dependências necessárias usando o `pip`:

```bash
pip install psycopg2 pandas

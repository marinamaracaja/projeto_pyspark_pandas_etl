# Projeto de ETL
Carregamento, limpeza e tratamento de dados de um dataset utilizando MongoDB, Pandas e Pyspark como projeto individual do curso de Engenharia de Dados da SoulCode Academy

## Pré-requisitos:
### Nivel Infra
O Dataset deve ser salvo em ambiente cloud(Cloud Storage)
O arquivo original e tratado deve ser salvo em MongoDB Atlas em coleções diferentes
Os DataFrames devem ser obrigatoriamente salvos em uma bucket do CloudStorage

### Nivel Pandas
O arquivo está em outra linguagem e deve ter seus dados traduzidos para Português-BR
Realizar a extração corretamente para um dataframe
Verificar a existência de dados inconsistentes e realizar a limpeza para NaN ou NA
Realizar o drop(se necessário) de colunas do dataframe realizando o comentário do porque da exclusão 
Todos os passos devem ser comentados

### Nivel PySpark
Deverá ser montada a estrutura do DataFrame utilizando o StructType.
Verificar a existência de dados inconsistentes, nulos e realizar a limpeza.
Verificar a necessidade de drop em colunas ou linhas. Caso seja necessário, fazer comentário do porque.
Realizar a mudança de nome de pelo menos 2 colunas
Deverá criar pelo menos duas novas colunas contendo alguma informação relevante sobre as outras colunas já existentes (Funções de Agrupamento, Agregação ou Joins). (Use a sua capacidade analítica)
Deverá utilizar filtros, ordenação e agrupamento, trazendo dados relevantes para o negócio em questão. (Use a sua capacidade analítica)
Utilizar pelo menos duas Window Functions

### Nivel SparkSQL
Utilizar no minimo 5 consultas diferentes utilizando o SparkSQL, comentando o porquê de ter escolhido essas funções e explicando o que cada consulta faz.


## Ferramentas Utilizadas
* Google Cloud Platform
* MongoDB
* Python
* Biblioteca Pandas
* PySpark
* Google Colab

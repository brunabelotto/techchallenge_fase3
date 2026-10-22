# techchallenge_fase3
dados: https://www.kaggle.com/datahackers/datasets
Criar pasta no S3 chamada input

Criar pasta no S3 chamada bronze

Criar pasta no S3 chamada silver

Criar pasta no S3 chamada gold

Criar notebook no Glue chamado ETL-Bronze e colar código da pasta ETL-Bronze

Criar notebook no Glue chamado ETL-Silver e colar código da pasta ETL-Silver

Para montar o coalesce no ETL-Gold e construir apenas as colunas, foi necessário primeiro extrair os nomes das colunas da tabela da camada Silver

Ao executar esta linha no athena:

SHOW COLUMNS FROM default.state_of_data_silver;

foi possível extrair as colunas em uma lista e assim identificar as colunas que continham os dados necessários para responder as perguntas do negócio.

Perguntas do negócio estão anexadas.

Foram construídos colunas que traziam as informações unificadas, assim os dados de diferentes colunas eram argupados em uma única coluna na camada Gold

Criar notebook no Glue chamado ETL-Gold e colar código da pasta ETL-Gold

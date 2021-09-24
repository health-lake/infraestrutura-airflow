# infraestrutura-airflow

As variáveis de ambiente a baixo devem ser setadas na EC2 antes de rodar o CI:
```
export POSTGRESQL_DATABASE="bitnami_airflow"
export POSTGRESQL_USERNAME="bn_airflow"
export POSTGRESQL_PASSWORD="bitnami1"
export AIRFLOW_PASSWORD="airflow"
export AIRFLOW_USERNAME="airflow"
export AIRFLOW_EMAIL="healthlake@airflow.com"
```
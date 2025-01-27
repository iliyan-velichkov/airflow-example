# local-executor-example
Apache Airflow example project with [LocalExecutor](https://airflow.apache.org/docs/apache-airflow/stable/core-concepts/executor/local.html)

## Steps
### Run Steps
- Start Airflow
    ```shell
    cd local-executor-example
    
    docker compose up
    ```

- Open Airflow UI at [http://localhost:8080](http://localhost:8080)
- User credentials `airflow` / `airflow`
- Example DAG at [http://localhost:8080/dags/my_dag](http://localhost:8080/dags/my_dag)

### Stop Steps
```shell
rm -rf my_postgresql_data

docker compose stop

docker compose down
```

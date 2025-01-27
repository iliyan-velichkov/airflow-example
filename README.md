# airflow-example
Apache Airflow example project 

--- 

The example is based on:
- [Running Airflow 2.0 with Docker in 5 mins](https://youtu.be/aTaytcxy2Ck?feature=shared)
- [Airflow DAG: Coding your first DAG for Beginnerss](https://youtu.be/IH1-0hwFZRQ?feature=shared)

## Steps
- Start Airflow
    ```shell
    cd airflow-example
    
    docker compose up airflow-init
    
    docker compose up
    ```

- Open Airflow UI at [http://localhost:8080](http://localhost:8080)
- User credentials `airflow` / `airflow`
- Example DAG at [http://localhost:8080/dags/my_dag](http://localhost:8080/dags/my_dag)

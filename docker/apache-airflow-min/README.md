## First Airflow DAG: Data ingestion pipeline

1 - Prepare the database first `docker-compose up airflow-init`

This is going to created db/airflow.db mysql database

2 - Launch Airflow `docker-compose up`

Wait for scheduler and webserver to get healthy, then go to `localhost:8081` 

```python
username: admin
password: airflow
```

Enable the DAG and watch it ingest data.

### Reference
https://www.youtube.com/watch?v=TkvX1L__g3s
https://www.youtube.com/watch?v=CLkzXrjrFKg&list=PLwFJcsJ61oujAqYpMp1kdUBcPG0sE0QMT&index=6
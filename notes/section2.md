# Core component of Airflow

1. Flask Server
2. Scheduler
3. Metastore
4. Executor - There is a queue in the executor
5. Worker

## DAG

## Operator

## Workflow

## one node architecture

## Multi node architecture -Celery

# Build the airflow image

```
docker build -t airflow-basic .
```

# Docker container using airflow-basic image

```
docker run --rm -d -p 8080:8080 airflow-basic
```

# Open the docker containers command prompt

```
docker exec -it 0e0002f307f0 /bin/bash
```

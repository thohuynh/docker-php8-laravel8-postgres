# Explain Env Variables

```
APP_PORT = Application port output run with php8.0
APP_PHP_81_PORT = Application port output run with php8.1
APP_PATH = Real path to source code
MYSQL_PORT = Mysql port output
REDIS_PORT = Redis port output
LOCALSTACK_PORT = Localstack port output (same with S3 AWS)
COMPOSE_PROJECT_NAME = {PROJECT_NAME}
POSTGRES_PORT = Postgres port output
```

### Step 1: `docker-compose build`
### Step 2: `docker-compose up -d`
### Step 3: `docker ps` (for check container running)

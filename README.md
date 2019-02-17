## python3.7

local build

```
docker-compose run lambda-dev-build
```

test run

```
docker-compose run lambda-run main.lambda_handler $(printf '%s' $(cat ./input.json))
```

build

```
docker-compose run lambda-build
```

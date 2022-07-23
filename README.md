# fromzero
Repository created to learn to build microservices by following tutorial of youtube video of noahgift. 
Live training
[![Python application test with Github Actions](https://github.com/laura-BTS12/fromzero/actions/workflows/main.yml/badge.svg)](https://github.com/laura-BTS12/fromzero/actions/workflows/main.yml)

### To call microservice

something like this
```bash
curl -X 'POST' \
  'http://0.0.0.0:8080/wiki' \
  -H 'accept: application/json' \
  -H 'Content-Type: application/json' \
  -d '{
  "name": "Microsoft"
}'
```

### Build container

`docker build .`
`docker image ls`

### Run container

something like this

`docker run -p 127.0.0.1:8080:8080 9b46f119bcb2`

### Invoke

run `invoke.sh`
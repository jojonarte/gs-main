# Guidesmiths Frontend+Backend exam

## Running the app
### Prerequisites:
- docker

```shell
$ cp .env.example .env
$ git submodule update --init --recursive
$ docker-compose up // or with -d
```

Building the services might take a while as it needs to pull the dependencies before it can run.

# Where to find them?
Api service will be built on - http://localhost:3002

Client service will be build on http://localhost

This configuration can be changed in the `.env` file.

# Tests
- each service have individual test suites configured, you can do below steps
```
cd <service folder>
cp .env.example .env
yarn; yarn test
```

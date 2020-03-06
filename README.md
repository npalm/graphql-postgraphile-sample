# GraphQL API Server for PostgreSQL

Example to put a GraphQL API server on top of PostgreSQL based on the schema used in [graphql-java-demo](https://github.com/npalm/graphql-java-demo/tree/rest-service).

## Setup

First start the services via docker-compose
```
docker-compose up -d 
```
Once ready you should be able to access the Java GraphQL API via http://localhost:8080/playground. Next start `postgraphile`

```
yarn && yarn start
```
or (`npm install && npm start`)

Go to http://localhost:5000/graphiql to checkout the GraphQL API.
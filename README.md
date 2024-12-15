<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://cdn.icon-icons.com/icons2/2699/PNG/512/graphql_logo_icon_171045.png" width="400" alt="Nest Logo" /></a>
</p>


# 🟪 Appointments GraphQL API 🟪
A simple GraphQL api that creates appointments for customers

# 🟣 What is GraphQL?
- GraphQL is a query language for APIs that allows you to request exactly the data you need, preventing `overfetching` (getting more data than necessary) and `underfetching` (missing required data). Unlike REST APIs, where you may need multiple requests to gather all necessary information, GraphQL optimizes data retrieval by letting clients specify exactly what they want, reducing unnecessary data transfer and improving efficiency.

# 💻 Libs
- Type GraphQL: In GraphQL, a type defines the structure of the data in your API. It specifies what data can be queried or mutated and the shape of the responses. Common types include `Query`, `Mutation`, and custom types that represent entities like Appointments, using this library, it's possible to Code First, and then the schema is automatically generated, as you can see in `schema.gql` file.

- Apollo Server: Apollo Server is a popular open-source library for building GraphQL APIs. It provides an easy-to-use framework for defining types, resolvers, and connecting to data sources. It handles the execution of GraphQL queries and mutations, supports schema stitching, and enables features like caching and subscriptions.

## ⚙ Installation

```bash
$ npm install
```

## ✅ Running the app

```bash
# development
$ npm run dev
```

- It will be possible to try the queries and mutations with the Apollo Server interface, you just need to access http://localhost:4000 after running the api ✅

## License

This application is [MIT licensed](LICENSE).

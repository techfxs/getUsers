# getUsers

1. Install node dependencies

npm i

2. run server

npm run dev:server

3. navigate to "http://localhost:4000/graphql"

You will see graphiql tool to talk to graphql server and query

sample query
============

{
  user(id:"40") {
    id
    firstName
    age
  }
}

this one fetches data from db.json.
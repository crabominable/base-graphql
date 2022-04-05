- Quais problemas GraphQL resolve?
    - Overfetching
    - Underfetching
- Dificuldades
    - Cache
    - Erros

- http://localhost:3000/graphql

```gql
query {
  users {
    id
    name
    github


    addresses {
      city
      state
      country
    }
  }
}
```
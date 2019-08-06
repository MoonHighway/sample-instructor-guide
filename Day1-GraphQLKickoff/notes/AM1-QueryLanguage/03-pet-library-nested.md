# Nested Queries

```graphql
query {
  allPets {
    name
    category
    weight
    photo {
      full
      thumb
    }
  }
}
```

[<< prev](https://github.com/MoonHighway/sample-instructor-guide/blob/master/GraphQL/Day1-GraphQLKickoff/notes/AM1-QueryLanguage/02-pet-library-enums.md) | [next >>](https://github.com/MoonHighway/sample-instructor-guide/blob/master/GraphQL/Day1-GraphQLKickoff/notes/AM1-QueryLanguage/04-pet-library-args.md)

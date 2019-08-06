# Aliases

```graphql
query {
  availablePets: totalPets(status: AVAILABLE)
  checkedOutPets: totalPets(status: CHECKEDOUT)
  dogs: allPets(category: DOG, status: AVAILABLE) {
    name
    weight
    status
    category
    photo {
      full
      thumb
    }
  }
}
```

[<< prev](https://github.com/MoonHighway/sample-instructor-guide/blob/master/Day1-GraphQLKickoff/notes/AM1-QueryLanguage/04-pet-library-args.md) | [next >>](https://github.com/MoonHighway/sample-instructor-guide/blob/master/Day1-GraphQLKickoff/notes/AM1-QueryLanguage/06-pet-library-variables.md)

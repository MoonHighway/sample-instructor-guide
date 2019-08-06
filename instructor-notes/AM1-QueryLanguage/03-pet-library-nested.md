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

[<< prev](https://github.com/MoonHighway/sample-instructor-guide/blob/master/instructor-notes/AM1-QueryLanguage/02-pet-library-enums.md) | [next >>](https://github.com/MoonHighway/sample-instructor-guide/blob/master/instructor-notes/AM1-QueryLanguage/04-pet-library-args.md)

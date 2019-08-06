# Variables

```graphql
query AvailableDogs($category: PetCategory, $status: PetStatus) {
  allPets(category: $category, status: $status) {
    id
    name
    status
    category
  }
}
```

_Query Variables Passed as JSON_

```json
{
  "category": "DOG",
  "status": "AVAILABLE"
}
```

[<< prev](https://github.com/MoonHighway/sample-instructor-guide/blob/master/Day1-GraphQLKickoff/notes/AM1-QueryLanguage/05-pet-library-aliases.md) | [next >>](https://github.com/MoonHighway/sample-instructor-guide/blob/master/Day1-GraphQLKickoff/notes/AM1-QueryLanguage/07-pet-library-connected-types.md)

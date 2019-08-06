# Connected Types

## Connect Pet to Customer

```graphql
query($id: ID!) {
  petById(id: $id) {
    name
    inCareOf {
      name
      username
    }
  }
}
```

_Query vars_

```json
{
  "id": "C-1"
}
```

_Send different query vars_

```json
{
  "id": "S-1"
}
```

## Connect Customer to Pet

```graphql
query {
  allCustomers {
    name
    username
    currentPets {
      name
    }
  }
}
```

[<< prev](https://github.com/MoonHighway/sample-instructor-guide/blob/master/instructor-notes/AM1-QueryLanguage/06-pet-library-variables.md) | [next >>](https://github.com/MoonHighway/sample-instructor-guide/blob/master/instructor-notes/AM1-QueryLanguage/08-pet-library-operation-names.md)

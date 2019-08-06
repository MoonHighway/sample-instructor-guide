# Operation Names

```graphql
query AllData {
  totalCustomers
  allCustomers {
    name
    username
    dateCreated
    checkoutHistory {
      pet {
        name
      }
      checkOutDate
      checkInDate
      late
    }
  }
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

- Split into two queries
- Show without Operation Name First

```graphql
query CustomerPage {
  totalCustomers
  allCustomers {
    name
    username
    dateCreated
    checkoutHistory {
      pet {
        name
      }
      checkOutDate
      checkInDate
      late
    }
  }
}

query PetPage {
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

[<< prev](https://github.com/MoonHighway/sample-instructor-guide/blob/master/instructor-notes/AM1-QueryLanguage/07-pet-library-connected-types.md) | [next >>](https://github.com/MoonHighway/sample-instructor-guide/blob/master/instructor-notes/AM1-QueryLanguage/09-vote-mutation.md)

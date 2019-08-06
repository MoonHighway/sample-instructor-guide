# Vote Subscription

**Time: 5 Minutes ⏰**

- Run Subscription

```graphql
subscription {
  result {
    eve
    alex
  }
}
```

- Test with Vote Mutation

```graphql
mutation {
  vote(host: EVE)
}
```

[<< prev](https://github.com/MoonHighway/curriculum/blob/master/GraphQL/Day1-GraphQLKickoff/notes/AM1-QueryLanguage/11-join-maillist-mutation.md) | [next >>](https://github.com/MoonHighway/curriculum/blob/master/GraphQL/Day1-GraphQLKickoff/notes/AM1-QueryLanguage/13-lab-snowtooth.md)

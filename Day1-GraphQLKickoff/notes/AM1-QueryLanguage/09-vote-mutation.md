# Vote Mutation

**Time: 10 Minutes ⏰**

- Open [vote.moonhighway.com](http://vote.moonhighway.com/)
- Vote for Eve

```graphql
mutation {
  vote(host: EVE)
}
```

- Vote for Alex

```graphql
mutation {
  vote(host: ALEX)
}
```

- Check the totals

```graphql
query {
  results {
    eve
    alex
  }
}
```

[<< prev](https://github.com/MoonHighway/sample-instructor-guide/blob/master/Day1-GraphQLKickoff/notes/AM1-QueryLanguage/08-pet-library-operation-names.md) | [next >>](https://github.com/MoonHighway/sample-instructor-guide/blob/master/Day1-GraphQLKickoff/notes/AM1-QueryLanguage/10-vote-mutation-extras.md)

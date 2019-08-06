# GraphQL Query Language

## 1. Pre Class Checklist

- [ ] Outline on Board
- [ ] Put [Slides on the Screen](https://slides.com/moonhighway/graphql-intro/)
- [ ] Notes On iPad
- [ ] Slow Down
- [ ] Face Forward
- [ ] Get GraphQL Fun Running

* http://www.graphql.fun/board/ localStorage.setItem("token", "graphqlisbetterthanrest")
* GraphQL Playground: http://www.graphql.fun/graphql { "Authorization":"graphqlisbetterthanrest" }

## 2. [Slides](https://slides.com/moonhighway/graphql-intro/)

## 3. GraphQL Fun

* Check how many players
* Then get their name

```graphql
query allPlayers {
  playerCount
  allPlayers {
    name
  }
}
```
* Create teams

```graphql
mutation {
  createTeams(count: 2) {
    color {
      name
    }
  }
}
```


**Time: 20 minutes ⏰**

[next >>](https://github.com/MoonHighway/curriculum/blob/master/GraphQL/Day1-GraphQLKickoff/notes/AM1-QueryLanguage/01-pet-library-queries.md)

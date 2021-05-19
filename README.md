# React & GraphQL Links

## Instructor Info

- **Eve Porcello**: [Twitter](https://twitter.com/eveporcello) | [Email](mailto:eve@moonhighway.com)
- **Moon Highway Training**: [Moon Highway Website](https://www.moonhighway.com) | [Mailing List](http://bit.ly/moonhighway) | [Articles](https://www.moonhighway.com/articles)

## Lake Lab Activity

- [Start Files](https://codesandbox.io/s/infallible-northcutt-p3b2o?file=/src/index.js)

### Star Rating

- Five Stars Rendered - ([run it](https://codesandbox.io/s/learning-react-star-rating-1-h7byq?file=/src/StarRating.js))
- Star Component with Props - ([run it](https://codesandbox.io/s/learning-react-star-rating-2-zbkuu?file=/src/App.js))
- Star Component with State - ([run it](https://codesandbox.io/s/learning-react-star-rating-3-tpmr9?file=/src/StarRating.js))
- Completed Star Component - ([run it](https://codesandbox.io/s/learning-react-star-rating-4-gxvb5?file=/src/Star.js))
- Advanced Star Component - ([run it](https://codesandbox.io/s/learning-react-star-rating-5-86ngm?file=/src/StarRating.js))

### useReducer

- Checkbox with `useState` - ([run it](https://codesandbox.io/s/learning-react-usereducer-1-ef229?file=/src/App.js))
- Checkbox with `toggle` - ([run it](https://codesandbox.io/s/learning-react-usereducer-2-oqy23?file=/src/App.js))
- Checkbox with `useReducer` - ([run it](https://codesandbox.io/s/learning-react-usereducer-3-mht63?file=/src/App.js))
- Increment number with `useReducer` - ([run it](https://codesandbox.io/s/learning-react-usereducer-4-b1yxs?file=/src/App.js))

## Requesting Data

1. Fetch ([run it](https://codesandbox.io/s/dry-sea-wmw8w?file=/src/index.js))
2. requestGithubUser ([run it](https://codesandbox.io/s/happy-hypatia-hu6e6?file=/src/index.js))
3. Fetching with the GitHubUser Component ([run it](https://codesandbox.io/s/crazy-borg-xyw0m?file=/src/App.js))

## Render Props

1. Displaying a List ([run it](https://codesandbox.io/s/great-knuth-iq8qu?file=/src/App.js))
2. Empty List ([run it](https://codesandbox.io/s/eager-http-zgou9?file=/src/App.js))
3. List with Data ([run it](https://codesandbox.io/s/affectionate-tdd-0mucp?file=/src/App.js))
4. Conditional Render Prop Function ([run it](https://codesandbox.io/s/suspicious-sara-3dtyy?file=/src/App.js))

## GraphQL

### GraphQL Query Language

- [Query Language Slides](https://slides.com/moonhighway/graphql-intro/)
- [Snowtooth Playground](https://snowtooth.moonhighway.com)
- [Pet Library Playground](https://pet-library.moonhighway.com)
- [Moon Highway Vote Playground](http://vote.moonhighway.com)
- [Github GraphQL Explorer](https://developer.github.com/v4/explorer/)
- [Lab Instructions](https://slides.com/moonhighway/snowtooth-query-lab/)

### Apollo Client

#### Simple Requests

- curl Request

```sh
curl -X POST \
     -H "Content-Type: application/json" \
     --data '{ "query": "{allLifts{name}}" }' \
     http://snowtooth.moonhighway.com
```

- [Fetch Sample](https://codesandbox.io/s/n3jro0o4n0)
- [graphql-request](https://codesandbox.io/s/4qzq5z2vz0)

### React & Apollo

- [Snowtooth UI Start Files](https://github.com/graphqlworkshop/snowtooth-ui)
- [Snowtooth UI Finished Files](https://github.com/graphqlworkshop/snowtooth-ui/tree/complete)

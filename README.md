This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
## Fullstack Enginnering Technical Test

## Project

In the project directory, you can run:npm install && node server/server.js 

the app will open on port 4000 

## Tech stacks

- ReactJs 
- Apollo Client (react-apollo)
- Apollo Server
- Apollo boost
- React - redux
- NodeJS 
- Centralised state management (Redux/Context API + Action/Reducer pattern)
- [CodeSandbox](https://codesandbox.io/s/dreamy-water-nynvj) for implenting solution


### `App`

The app is broken down into two 
distinct parts, server and client:

### `Server`
Apollo GraphQL API that wraps chucknorris.io 
GraphQL API has a Query type that resolves all Categories (https://api.chucknorris.io/jokes/categories)
GraphQL API has a Query type that resolves a random joke given a Category as an argument (https://api.chucknorris.io/jokes/random?category={category})

### `Client`
Single Page App (SPA)
Consumes the above GraphQL API 
home page with a list of categories
When a category is clicked,  a random joke is displayed appropriately 



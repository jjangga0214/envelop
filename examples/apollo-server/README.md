## Envelop example with Apollo-Server

This example demonstrate how to implement the basic GraphQL Envelop flow with Envelop and [`Apollo-Server`](https://github.com/apollographql/apollo-server).

In this exmaple, Apollo-Server provides the basic HTTP wrapper and execution flow, and Envelop is in charge of the execution runtime.

## Running this example

1. Install all dependencies from the root of the repo (using `yarn`)
2. `cd` into that folder, and run `yarn start`.
3. Open http://localhost:3000/graphql in your browser, and try to run: `query { hello }`.

## Limitations

See https://github.com/apollographql/apollo-server/discussions/5541 

## Minimal GraphQL Node.js Template

### Description

Sets up a starter GraphQL API template.

This is by no means my recommended way of structuring your code, but should do well to demonstrate the core functionality of GraphQL. 

### Implementation

Uses `express` to handle requests  and `babel` for transpiling code.

**schema** is defined in `schema.js` and
**resolvers** are defined in `resolvers.js`

Provides a `graphiql` interface for API exploration at `/graphiql`

Authentication is not implemented.

# Space Gundb Relay Peer

This is a gundb relay peer server implementation mean't to be used with the [space-sdk](https://fleekhq.github.io/space-sdk/).

It is mean't to ensure the version of gundb on the server pair is in sync with the latest version of the space-sdk.

### Usage
This require `node` and `npm` to be installed on the server.
Then run the following instructions:

```
npm install
node server.js
```

By default it starts the server on port 5555 but it can be configured through the `PORT` environment variable.

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

# React Tutorial

This is the React comment box example from [the React tutorial](http://facebook.github.io/react/docs/tutorial.html).

## To use

There is a simple server implementations included that serves static files from `public/` and handles requests to `/api/comments` to fetch or add data. Start the server with one of the following:

### Node

```sh
npm install
node server.js
```

## Changing the port

You can change the port number by setting the `$PORT` environment variable before invoking any of the scripts above, e.g.,

```sh
PORT=3001 node server.js
```

# Single Page Application Demo

This is a demo project for beginners showing them how to build a Single Page Application without using a popular framework such as React, Angular, Vue, Ember or Backbone.js.

The main libraries used here are:

- [jQuery](https://jquery.com/) : DOM Handler
- [Handlebars](https://handlebarsjs.com/) : Templates Library
- [Vanilla Router](https://github.com/Graidenix/vanilla-router) - Clint-side routing

This application consumes data provided by [Fixer.io](https://fixer.io).

## Requirements

- [Node.js](http://nodejs.org/)

## Installation Steps

You'll need to register an [account](https://fixer.io/signup/free) with fixer.io in order to access their **Free API Key**. After you have cloned the repository, create a new file called `.env` at the root of the project. Provide your api key inside the file like this:

```env
API_KEY=<insert api access key here>
PORT=3000
TIMEOUT=5000
```

1. Clone repository
2. Run `npm install`
3. Start server with `npm start` or `node server`
4. Visit [http://localhost:3000/](http://localhost:3000/).

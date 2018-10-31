
---
## Description
Todo Application Api (Node.js, Strongloop, loopback, mongodb), with priority & attachments and exports todo list.
---

## Installation

You need to have installed [NodeJS](https://nodejs.org/) with [npm](https://www.npmjs.com/) and [MongoDB](https://www.mongodb.com/)


### To run the server:

```
$ npm start

server starts at PORT=3000
 ```

All dependencies will be installed automatically

### To run in dev mode or debugg mode:

```
$npm run dev
```

```
$npm dev:debug
```


## API

The server part has multiple **API endpoints** using several routes:

- `POST /appuser/login` -> login user.
- `POST /appuser/logout` -> logout user.
- `GET /todos` -> get todos list.
- `POST /todos` -> create new todo.
- `PUT /todos` -> update todo.
---

## Built with:

- **Front-end**
	- react , redux
	- material design

- **Back-end**
  - strongloop, loopback
  - jsonwebtoken
  - mongodb- mlab
  - node.js
---




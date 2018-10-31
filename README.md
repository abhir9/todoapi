
---
## Description
Todo Application Api (Node.js, Strongloop, loopback, mongodb), with priority & attachments and exports todo list.
---

## Installation

You need to have installed [NodeJS](https://nodejs.org/) with [npm](https://www.npmjs.com/) and [MongoDB](https://www.mongodb.com/)


### To run the server:

```
$ npm install

$ npm start // node . 

server starts at PORT=3000
 ```

All dependencies will be installed automatically

### To run in dev mode :

```
$npm run dev
```
### To run test cases:

```
$npm test
```

## API
The server part has multiple **API endpoints** using several routes:

- `POST api/appuser/login` -> login user.
- `POST api/appuser/logout` -> logout user.
- `GET api/todos` -> get todos list.
- `POST api/todos` -> create new todo.
- `PUT api/todos` -> update todo.
---

##UI
please find the url of UI repository

```
https://github.com/abhir9/todoui
```

## Modules Used
- **Node js server starter**
    - strongloop
	- loopback
- **test**
	- mocha
    - supertest
	- assert

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




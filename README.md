# Kanban Trello Board

Stolen with impunity from:  [Markus Englund](https://github.com/markusenglund) <markus.s.englund@gmail.com>
The original github repo is [here](https://github.com/markusenglund/react-kanban)

A server-rendered React app inspired by [Trello](https://trello.com/home).

### Features

* It has most of the features available on Trello, like creating and editing new cards, dragging around cards and so on.
* Supports GitHub flavored markdown, which enables stuff like headings and checklists on the cards.
* Works great on touch devices.

### Tech stack

* [React](https://github.com/facebook/react)
* [Redux](https://github.com/reactjs/redux)
* [React-beautiful-dnd](https://github.com/atlassian/react-beautiful-dnd)
* [Sass](https://github.com/sass/sass)
* [Webpack](https://github.com/webpack/webpack)
* [Babel](https://github.com/babel/babel)
* [Express](https://github.com/expressjs/express)
* [MongoDB](https://github.com/mongodb/mongo)
* [Passport](https://github.com/jaredhanson/passport)

#### Setup

```shell
git clone https://github.com/ed42311/react-kanban.git

cd react-kanban

yarn install
```

##### Mongodb

Mac OSx

##### Twitter Sign In

TODO: Document Process

##### Google Sign In

TODO: Document Process

```
# Has to be port 1337
ROOT_URL=http://127.0.0.1:1337
```

```shell
npm run build
npm run serve
```

For production deployment run:

```shell
npm run build:prod
npm run serve:prod
```

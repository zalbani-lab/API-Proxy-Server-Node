# API-Proxy-Server-Node
> Just a canvas for making a proxy api using nodeJs.
> Created following Traversy Media youtube tutorial : [https://www.youtube.com/watch?v=ZGymN8aFsv4](https://www.youtube.com/watch?v=ZGymN8aFsv4)

## Built With

* [NodeJS](https://github.com/nodejs/nodejs.dev) - Node.js is a free, open-sourced, cross-platform JavaScript run-time environment that lets developers write command line tools and server-side scripts outside of a browser.
* [Express](https://github.com/expressjs/express) - Fast, unopinionated, minimalist web framework for node.

## Installation

```bash
# install dependencies
$ npm install

# serve with at localhost:8000
$ npm run dev
```

## Development setup

First of all creat a `.env` file in the root folder
copy/paste the content of `.env.example` inside you're .env file.
Then you just have to fill every variables (`PORT` is optional by default is set to `9000`)

```js
PORT =
API_BASE_URL = ""
API_KEY_NAME = ""
API_KEY_VALUE = ""
```

## Organisation
```bash
.
├─ routes         -> This folser contain all API endpoint thats our proxy provide
│   └─ index.js   -> This file contain a API endpoint exemple, you can duplicate it and customize it   
├─ .env           -> Environement variables setup  
└─ index.js       -> This is the kernel of the app inside it you find : cors definition, routes declaration and ratelimiting
```

## Release History

* 0.1.0
    * POC

## Authors

Alban PIERSON – pro.pierson.alban@gmail.com

## License

This project is licensed under the GNU GPL v3 License - see the [LICENSE.md](LICENSE.md) file for details

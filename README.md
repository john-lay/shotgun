# Shotgun

## Running in development
Install NPM http-server with `npm install http-server -g`

Open the root folder in a terminal and run `http-server`


---

# Installation

## Prerequisites
* [Node.js](https://github.com/nodejs/node) and NPM. (NPM can be optionally installed using [NVM](https://github.com/creationix/nvm) to avoid some known permission problems)
* [http-server](https://www.npmjs.com/package/http-server) Install NPM http-server with `npm install http-server -g`

## Development server
* Clone the develop branch of the repository `git clone https://github.com/john-lay/shotgun.git`
* Open your preferred command line application and navigate to your local folder containing the above repository
* Run `http-server` for a dev server. Navigate to [http://localhost:8080/index](http://localhost:8080/index). The app will automatically reload if you change any of the source files.


## Compiling source
* `./node_modules/.bin/webpack`
* Run with `npm start`
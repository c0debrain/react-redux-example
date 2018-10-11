# Init project (Server)
npm init -y
npm install --save-dev babel-core babel-cli babel-preset-es2015 mocha chai

##npm install --save-dev mocha chai
## Run tests
./node_modules/mocha/bin/mocha --compilers js:babel-core/register --recursive


npm install --save immutable
npm install --save-dev chai-immutable

## install redux
npm install --save redux

## Install socket.io
npm install --save socket.io


# Init project (Client)
mkdir voting-client
cd voting-client
npm init -y

## Add webpack
npm install --save-dev webpack webpack-dev-server
--NOTE: install webpack-cli

## Run webpack globally
npm install -g webpack webpack-dev-server

## Add ES6
npm install --save-dev babel-core babel-loader babel-preset-es2015 babel-preset-react

## Testing
npm install --save-dev mocha chai

--Karma or
npm install --save-dev jsdom

## Install immutable
npm install --save immutable
npm install --save-dev chai-immutable

## Install reactDom and hot loader
npm install --save react react-dom
npm install --save-dev react-hot-loader

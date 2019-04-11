# Plasma MVP

[![Build Status](https://travis-ci.org/voltairelabs/plasma.svg?branch=master)](https://travis-ci.org/voltairelabs/plasma)

Install dependencies with

```
$ npm install
```

Run test cases:

```
# start test rpc server (which starts server on localhost:8545)
$ npm run testrpc

# run test cases
$ npm run test
```

### Development

```
# start test rpc server or you can start `geth`/`parity` node
$ npm run testrpc

# deploy contracts
$ npm run deploy

# start authority's server
$ npm run authorized-dev

# start dev server
$ npm run dev
```

### Production

```
# build server
$ npm run build

# start server
$ npm start
```

### CLI

```
$ npm run testrpc # or use actual ethereum node (check configurations)
$ npm run authorized-node # or simple dev node => npm run dev


# start cli (`-p` option provides a way to accept sender's private key)
$ ./src/cli/index.js -p '9b28f36fbd67381120752d6172ecdcf10e06ab2d9a1367aac00cdcd6ac7855d3'
plasma > .help
```

## Install dependencies
```
$ npm install -g truffle
$ npm install
```

## Deploy
```
# Note: ganache-cli@latest doesn't work on node 14.x 
$ nvm use lts/dubnium 
$ node -v 
# Outputs:
> v10.20.1
# Start ganache-cli:
$ ganache-cli
# Deploy:
$ truffle migrate
```

## Deploy to Matic (testnet)
```
# @truffle does work on node 14.x
$ nvm use stable
$ node -v
# Outputs:
> v14.3.0
# Deploy:
$ truffle migrate --network matic
```

# mpl-membership-token

This package contains the auction house contract SDK code.

## Developing

In order to update the generated SDK when the rust contract was updated please run:

```
yarn api:gen
```

NOTE: at this point this only generates the IDL json file but later will generate TypeScript
definitions and SDK code as well, derived from that IDL.

## LICENSE

Apache v2.0

## Test

To run tests locally use

```
yarn amman:start
yarn build
yarn test
```

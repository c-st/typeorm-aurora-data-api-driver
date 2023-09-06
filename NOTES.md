# Notes on how to get this running locally

```sh
yarn install
npm i --no-save typeorm
yarn build
yarn link typeorm-aurora-data-api-driver

docker-compose -f docker/pg.yml up -d

yarn test:unit
yarn test:pg-func
```

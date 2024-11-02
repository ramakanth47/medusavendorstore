



## How to run 

```
docker compose up
```

```
cd medusa-marketplace-demo
yarn
cp .env.template .env
npx medusa db:setup --db marketplace
yarn dev
```

The Medusa dashboard should now be running on http://localhost:9000/app



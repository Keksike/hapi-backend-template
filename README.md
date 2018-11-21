# Hapi Backend Template

A very basic boilerplate template for creating backends with Hapi.

Includes:

- example endpoint `POST /hello`
- example Jest e2e test & service unit test
- Joi request payload validation
- smart feature-driven folder structure and separation of HTTP handler & business logic
- swagger API docs
- winston logger
- Dockerfile
- `.travis.yml` which runs tests

## Dev guide

First set up environment variables.

```
# copy and fill in the .env values
cp .env.example .env
```

Start the service with `yarn start`

Watch the tests with `yarn test:watch`

When in dev mode swagger API docs are available at `http://localhost:2020/documentation`

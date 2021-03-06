# Location & Weather API
Demonstration application for Flow which provides IP inferred location information and current weather or forecast (location based or queried by city name)

## Application is running @ https://sheltered-earth-53915.herokuapp.com/v1

## Node version used:  v10.15.3 (npm v6.11.2)

## Instructions
- run `npm install`
- make sure to be running Node v10.15.13
- to run tests `cp .env.example .env` is enough
- to try out the API create `.env` file and punch in your environment variables following `.env.example` file.
- start the server and browse `http://localhost:PORT/v1/documentation` for the swagger docs!

## Commands
- `npm run start`: starts server
- `npm run test`: runs linter and then tests (**100% coverage**)

## Dependencies
- `dotenv`: for loading `.env` file containing sensitive information on to process environment variables.
- `fastify`: web framework API
- `got`: HTTP request API
- `nock`: HTTP mocking
- `lodash`: for helper functions
- `eslint`: linter tool
- `eslint-config-google`: base linter config
- `tap`: testing suite
- `fastify-status`: provides status endpoint
- `fastify-swagger`: OpenAPI Specification plugin

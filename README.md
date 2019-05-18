# Seers-API OpenAPI Specification

[![Build Status](https://travis-ci.org/mckinley-and-rice/seers-api.svg?branch=master)](https://travis-ci.org/mckinley-and-rice/Seers-api.)

## Links

- [Reference Documentation (Seers-API)](https://mckinley-and-rice.github.io/seers-api/)
- OpenAPI Raw Files: [JSON](https://mckinley-and-rice.github.io/seers-api/openapi.json) [YAML](https://mckinley-and-rice.github.io/seers-api/openapi.yaml)


## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and run `npm install` in the repo root

### Usage

```
npm install
npm start
```

#### `npm start`
Starts the development server.



## Development server started 🎉 :

  ✔ Documentation (ReDoc):      http://localhost:8080

  ✔ Swagger Editor:             http://localhost:8080/swagger-editor/

Visit http://localhost:8080/swagger-editor/ and edit and commit



#### `npm run build`
Bundles the spec and prepares web_deploy folder with static assets.

#### `npm test`
Validates the spec.

#### `npm run gh-pages`
Deploys docs to GitHub Pages. You don't need to run it manually if you have Travis CI configured.

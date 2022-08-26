# FigmaTokens
Figma Tokens Example

- Node 16.15.1

```sh
# local環境
yarn install
yarn token

# docker環境
docker run --rm -w "/app" -v "${PWD}:/app" node:16.15.1-buster-slim yarn install
docker run --rm -w "/app" -v "${PWD}:/app" node:16.15.1-buster-slim yarn token
```
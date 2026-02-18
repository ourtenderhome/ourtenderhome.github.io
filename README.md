# Website

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

## Installation

```bash
yarn
```

## Local Development

```bash
yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```bash
yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

```bash
$env:GIT_AUTHOR_NAME="ourtenderhome"
$env:GIT_AUTHOR_EMAIL="rokuhirachihirosato@gmail.com"
$env:GIT_COMMITTER_NAME="ourtenderhome"
$env:GIT_COMMITTER_EMAIL="rokuhirachihirosato@gmail.com"

set GIT_AUTHOR_NAME=ourtenderhome
set GIT_COMMITTER_EMAIL=rokuhirachihirosato@gmail.com
set GIT_COMMITTER_NAME=ourtenderhome
set GIT_COMMITTER_EMAIL=rokuhirachihirosato@gmail.com
set GIT_USER=ourtenderhome

yarn deploy
```

https://mth3860.github.io/ 
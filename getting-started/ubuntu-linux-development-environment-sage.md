---
ID: 29773
post_title: 'Ubuntu Linux Development Environment: Sage'
author: Michael W. Delaney
post_excerpt: ""
layout: doc
permalink: >
  https://roots.io/getting-started/docs/ubuntu-linux-development-environment-sage/
published: true
post_date: 2018-08-21 10:58:46
---
Sage relies on a few build tools to manage dependencies and build assets. Install these tools:

- nvm
- Node.js
- yarn

## nvm

Install nvm from the instructions at [https://github.com/creationix/nvm](https://github.com/creationix/nvm), or with the following command:

```sh
$ curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.34.0/install.sh | bash
```

## Node.js

Install the latest Node.js LTS release from nvm:

```sh
$ nvm install --lts
```

## yarn

Install yarn:

```sh
$ npm install --global yarn
```
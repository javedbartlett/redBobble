# Project Name

> RedBobble Proxy Server

## Table of Contents

1. [Setup](#Setup)
1. [Requirements](#requirements)
1. [Development](#development)

## Setup

1. Clone this repo using this command:
```bash
git clone --recurse-submodules https://github.com/javedbartlett/redBobble/tree/master/allServices-deployReady.git
```
2. Install dependencies:
```bash
npm install
```
3. Start [MongoDB](https://docs.mongodb.com/manual/installation/)

4. Build and start all the required servers:
```bash
# For development:
npm run start-dev
# Or for production:
npm start
```

## Requirements

An `nvmrc` file is included if using [nvm](https://github.com/creationix/nvm).

- Node v12.13.1
- MongoDB

# ezmarket

## Table of Contents

1. [About](#about)
2. [Prerequisites](#prerequisites)
3. [Setup](#setup)
4. [Features](#features)
5. [Future Work](#future-work)

## About

Community marketplace to upload information of the items you would like to sell. Add, delete and update your listings.

Hosted on <a>https://ezmarket.netlify.app</a>

## Prerequisites

- (Dev only) PostgreSQL 14.1

## Setup
1. Clone entire repo as client and server are stored as submodules

   ```
   git clone --recursive https://github.com/xinyitay/ezmarket.git
   ```
   
2. Install concurrently

   ```
   npm i
   ```

3. Install app dependencies using setup script:

   ```
   npm run setup
   ```

4. Change local DB user and password to that of your own in `ezmarket-server/src/index.ts` and set ssl option (line 30) to `false`

5. Start the app

   ```
   npm start
   ```

## Features

### Carousel main menu

### Add items

### Delete items

### Update items

<!-- ![react](./assets/react.png)

Validation of inputs also occurs for the frontend:

![reactValid](./assets/reactValid.png)

![reactValidAlert](./assets/reactValidAlert.png)  -->

## Future work

Add user auth (Google) by EzBackend so that you can only update your own listings and view others'.

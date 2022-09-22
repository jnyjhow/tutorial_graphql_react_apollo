# Overview

A simple clone of Hackernews. Here’s a list of the features the app will have:

- Display a list of links
- Search the list of links
- Handle user authentication
- Allow authenticated users to create new links
- Allow authenticated users to up vote links (one vote per link and user)
- Realtime updates when other users up vote a link or create a new one

In this track, we’ll use the following technologies for building the app:

## Frontend:

- React: Library for building user interfaces
- Apollo Client: Production-ready, caching GraphQL client

## Backend:

- Apollo Server: Fully-featured GraphQL Server with focus on easy setup, performance and great developer experience
- Prisma: Open-source database toolkit that makes it simple to work with relational databases

# How to use

## 1) Clone repository

```
git clone https://github.com/jnyjhow/tutorial_graphql_react_apollo/
```

## 2) Start the backend server

Go to the `backend` folder, install dependencies and start the server.

```
cd tutorial_graphql_react_apollo/backend
yarn install
yarn dev
```

> **Note**: If you want to interact with the GraphQL API of the server inside, you can navigate to [http://localhost:4000](http://localhost:4000).

## 3) Run the app

Now that the server is running, you can start the React app as well. The commands need to be run in a new terminal tab/window inside the root directory `tutorial_graphql_react_apollo` (because the current tab is blocked by the process running the server):

```sh
yarn install
yarn start
```

You can now open your browser and use the app on http://localhost:3000.

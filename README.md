# Polls API

## Table of Content:

- [About The App](#about-the-app)
- [Technologies](#technologies)
- [Setup](#setup)
- [Approach](#approach)
- [Status](#status)
- [License](#license)

## About The App
The Polls API is an application that allows users to create and manage polls, as well as manage votes for polls.

## Technologies
The API is written using Fastify, Node.js, Prisma ORM, PostgreSQL, and Redis.

## Setup
To set up the project, follow these steps:
- Clone the repository
- Run `npm install` to install the dependencies
- Run `docker compose up -d` to setup PostgreSQL and Redis
- Create a `.env` file taking `.env.example` as a template
- Run `npm run dev` to start the application
- That's it, you now can use the API on `http://localhost:3333`!

## Approach
The API adopts a RESTful architecture and utilizes Fastify for efficient request handling. Prisma ORM is used for database access, with PostgreSQL as the main database and Redis for caching.

## Status
The Polls API is currently in development and is expected to reach version 1.0 soon.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

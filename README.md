# Testing Java Microservices

This is the codebase of [Testing Java Microservices](https://www.manning.com/books/testing-java-microservices).

It has a heterogeneous framework is intentionally chosen by the books author to cover more test styles.

## The application

This is a toy application that provides information about games
and add the possibility to view ingame videos and add comments.

## Architecture

There are 4 services:

- `Video` fetches videos of a specific game
- `Comments` handles all logic concerning comments
- `Game` handles all logic concerning games
- `Aggregator` is the API gateway used by the frontend.

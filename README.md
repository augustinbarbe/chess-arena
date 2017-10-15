# chess-arena

chess-arena is a micro-service application where robots fight each other at chess. It relies on the following micro-services:

- web-api, which is a web client to start and watch robots playing chess.
- chess-docker, which takes care of managing docker containers to host chess ai.
- chess-ai, which is the application taking care of playing. Relies on docker.
- chess-redis, which contains the redis instance.

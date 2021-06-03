# Keycloak JS Client

This is a simple client for a Keycloak instance. It is configured to work on a local instance of Keycloak. This is one part of a three part system involving a _Authorization Server_ (Keycloak), a _Resource Server_ (Java Spring Application), and a _Client_ (this application).

The client is configured to login and logout of Keycloak as well as display information about the various tokens it recieves from Keycloak.

## Setup

Configuration details for a JavaScript Keycloak client can be found [here](https://www.keycloak.org/docs/latest/securing_apps/index.html#_javascript_adapter). This aplication is Dockerised and exposed on port 8000 due to our configurations in Keycloak.

## Install

You can build the Docker image using:

```
docker build -t keycloak-js-client .
```

## Usage

You can run the container with the following command:

```
docker run -p 8000:80 keycloak-js-client
```

## Maintainers
[Nicholas Lennox (@NicholasLennox)](https://gitlab.com/NicholasLennox)

## Licence

Copyright 2021, Noroff Accelerate AS

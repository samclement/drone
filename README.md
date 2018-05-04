# Drone CI

This `docker-compose` file will up an instance of a drone server and one drone agent on the swhurl.com network.

## Pre-requisites

1. Create Github OAuth app. 
2. Create a docker `.env` file with:

- `DRONE_GITHUB_CLIENT`
- `DRONE_GITHUB_SECRET`
- `DRONE_SECRET`

## Run

Start with: `docker-compose up -d`

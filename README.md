# AWS Examples

This repo contains different type of examples of no `click ops` with AWS using code pipelines. Please refer to Readme.md in each folder for more details.

With added Nginx sidecar container to act as reverse proxy. Using this pattern https://github.com/awslabs/ecs-nginx-reverse-proxy/tree/master/reverse-proxy

## Locally

To build:

` docker-compose build `

then to run the containers locally:

` docker-compose up `

Then browse to `http://localhost/test-app-0.1/` and you'll see the test page

# Archived repo

Please use [Optimism Docker](https://github.com/CryptoManufaktur-io/optimism-docker) for BoB RPC nodes

# BoB Docker

Docker compose for BoB

Meant to be used with central-proxy-docker for traefik and Prometheus remote write; use :ext-network.yml in COMPOSE_FILE inside .env in that case.

`cp default.env .env`, then `nano .env` and adjust variables.

If you don't have Docker CE yet, `./bobd install` can install it

`./bobd up` starts the stack
`./bobd update` followed by `./bobd up` will update the images, and restart what changed

## Version

BoB Docker uses a "semver" scheme.

This is BoB Docker v1.0.0

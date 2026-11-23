# Full-stack

Umbrella for full-stack applications and related services. Related microservices are grouped together under `microservices/`; each directory is a separate repository added as a Git submodule.

## Repositories

- `full-stack-projects/` - Full-stack project collection.
- [Ecommerce frontend](https://github.com/sridharkattakindi/frontend-practice/tree/main/medium-projects/ecommerce) - Located in the Front-end umbrella; configured to call an API gateway.
- `microservices/Order-Service/`
- `microservices/Product-Service/`
- `microservices/product-loader/`
- `microservices/api-gateway/`
- `microservices/Eureka/`

The gateway routes product and order requests to their services through Eureka.

Clone with `git clone --recurse-submodules`.

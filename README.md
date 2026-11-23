# Full-stack

Umbrella for full-stack applications and related services. The ecommerce frontend and its supporting services are grouped under `grp-ecommerce/`.

## Repositories

- `full-stack-projects/` - Full-stack project collection.
- `grp-ecommerce/ecommerce/` - React frontend.
- `grp-ecommerce/Order-Service/` - Order API.
- `grp-ecommerce/Product-Service/` - Product API.
- `grp-ecommerce/product-loader/` - Product data loader.
- `grp-ecommerce/api-gateway/` - Gateway routing to product and order APIs.
- `grp-ecommerce/Eureka/` - Service discovery.

The gateway routes product and order requests to their services through Eureka.

Clone with `git clone --recurse-submodules`.

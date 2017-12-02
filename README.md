# swaggers

## Steps to generate Swagger YAML files:
- Grab curl command from POST in SB from devtools
- Plug curl command into Postman, generate JSON formatted requests
- Create collection of requests in Postman
- Using apimatic.io/transformer, convert collection to OpenAPI Spec v.3.0 YAML
- Generate swagger api docs from YAML files
- Clean up generated YAML files

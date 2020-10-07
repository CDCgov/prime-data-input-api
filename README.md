# PRIME Data Input API

This is a prototype API for the PRIME Data Input application. It utilizes a design-first approach to API design and implementation: the [OpenAPI Specification](https://www.openapis.org/) in `openapi.yml` is the design document from which the API is generated. 

The API itself is Express middleware generated with [OpenAPI Enforcer](https://github.com/byu-oit/openapi-enforcer). It currently is a mock server serving data provided as `examples` in the `openapi.yml` document. As we iterate on the design, we will begin building out this middleware so that it implements desired logic and connects to desired data storage, etc.

## Getting Started

Clone this repo. 

Make sure you have NodeJS installed and accessible in the project directory.

Run the server: `node api.js`

Your API is now available at localhost:3000.

## Using the OAS document

If you don't want to use this Express server, or you want to take advantage the extensive tooling ecosystem around OpenAPI, you can simply plug and play `openapi.yml` with any of your favorite tools! This project's OAS doc is in OAS v 3.0.0, so you can use any tool compatible with this version.

Check out these lists of tools:

[OpenAPI.tools](https://openapi.tools/)
[OpenAPI 3.0 Implementations](https://github.com/OAI/OpenAPI-Specification/blob/master/IMPLEMENTATIONS.md)

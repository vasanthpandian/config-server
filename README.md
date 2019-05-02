# config-server
![GitHub contributors](https://img.shields.io/github/contributors/vasanthpandian/config-server.svg) ![GitHub last commit](https://img.shields.io/github/last-commit/vasanthpandian/config-server.svg)

Config server is where all configurable parameters of microservices are written and maintained. It is more like externalizing properties / resource file out of project codebase to an external service altogether, so that any changes to that property does not necessitate the deployment of service which is using the property. All such property changes will be reflected without redeploying the microservice.

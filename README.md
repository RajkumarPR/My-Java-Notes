# RESTful-APIs-wiki

# RESTful API
REpresentational State Transfer is an architectural style which defines set of constraints to be used to create web service. REST describes the general rules for how the data and services are represented through the API so that other programs will be able to correctly request and receive the data and services that an API makes available. Restful web service interoperates between computer on the internet. REST API explicitly takes advantage of HTTP methodologies to supports almost all HTTP operations i.e.
GET
POST
PUT
DELETE
PATCH
# Six constraints of RESTful APIs
1. Stateless
2. Clinet-Server
3. Uniform Interface
4. Cacheable
5. Layered System
6. Code on Demand
# 1. Stateless
Roy fielding got inspiration from HTTP, so it reflects in this constraint. API Server doesn't maintaines the state of the client requests, it treat each request as new request even if the user of the API already sent a GET request for the same resource in the past. It doesn’t remember which resources the user of the API requested before.

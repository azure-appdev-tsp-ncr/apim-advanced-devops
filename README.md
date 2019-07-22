# apim-advanced-devops
Advanced Azure APIM DevOps Deployment Practices &amp; Patterns 

The purpose of this repo will be to provide documentation and examples of advanced DevOps APIM deployment best practices learned from real-world customers that are pushing the envelope of API Capabilities including:

1) Using OpenAPI Spec (Swagger) Imports/Updates + Git Sync capability combined with Named Values (to abstract env specific settings) to migrate API's through their ALM

2) Implement a generalized Circuit Breaker pattern as an APIM Policy

3) Advanced Caching/Integration Patterns, where's an API Provider ansynchrounously pushes changes to a Cache, replacing the need to synchronous back-end calls

4) Implementation of CQRS/Microservice Patterns and integration eventing data sources such as Apache Flink

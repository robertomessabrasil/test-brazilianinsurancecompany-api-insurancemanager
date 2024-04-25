# About

This api is been built as an job selection process for a brazilian insurance company

## Insurance Api

This api was built with the [swagger editor](https://editor.swagger.io/) and [swagger maven plugin](https://www.youtube.com/watch?v=zmfCS1E7oeI&t=86s).

Due to unespected delays in other commitments, I was unable to consume the [Insurance Manager Dependency](https://github.com/RobertoMessaBrasil/test-brazilianinsurancecompany-dep-insurancemanager) in this api.

### Next steps:
1. override the post verb and use the Insurance Manager Inbound adapter to create a customer
2. override the get by id verb and use the Insurance Manager Inbound adapter to retrieve a customer
3. update the swagger.yaml to create the remaing verbs
4. create the controllers for the remaining verbs
5. implement the Inbound to read from http requests
6. implement the Outbound adapters to write to h2 database
7. create the integration tests
8. create a docker image for the api
9. run the container
10. test the api

### Deploy in AWS
1. push the image do [docker hub](https://hub.docker.com)
3. create an [ECS](https://aws.amazon.com/ecs/) Task in ASW
4. pull the image from docker hub
5. start the container
6. test the api

### Documentation
1. create a [c4 model](https://c4model.com/) to explain the architecture
2. create a linkedin article to explain the whole solution
3. create a Youtube playlist to explain my decisions on executing the technical test

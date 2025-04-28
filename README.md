# License-Verification-API
This is the final addition to Menditect from Oscar William Nolan Mensink.

# Goal of project
The goal is to have an api that is eternally running on AWS that can verify if a Menditect user still has an ongoing license for a given menditect application.
The needs to be updatable by the Menditect portal application worked on by Rolf. 
There also needs to be API requests that can verify licenses stored in AWS.

# Building components
- [Confluence for requirments](https://menditect.atlassian.net/wiki/spaces/Persist/pages/433192961/License+Module)
- [Nestjs for API Framework](https://docs.nestjs.com/)
- [Swagger Cli from Nestjs](https://docs.nestjs.com/openapi/cli-plugin#overview) offers API Documentation fo rfuture users
- [rspack](https://rspack.dev/) as application bundler
- [Dynamo-db](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html) as the database for storing projects
- [dynamodb-toolbox](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html) as the request building code for dynamodb
- [AWS CDK V2](https://docs.aws.amazon.com/cdk/v2/guide/home.html) for building and hsting through AWS
- [vitest](https://vitest.dev/guide/) as the testing framework

# Visual Studio
# # Visual suggested studio extensions
- Docker

# Project Local setup

# # Run local AWS compponents
Enter terminal and go to projet location.

1. 
    docker compose up

# Tips
F-Secure blocked access to folders to node. I fixed this by getting  notifications from F-secure whenever it blocks anything, and when that happens changing the access by clicking on said notification.

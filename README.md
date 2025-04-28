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
- [Webpack](https://docs.nestjs.com/openapi/cli-plugin#overview) as application bundler
- [Dynamo-db](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html) as the database for storing projects
- [dynamodb-toolbox](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html) as the request building code for dynamodb
- [AWS CDK V2](https://docs.aws.amazon.com/cdk/v2/guide/home.html) for building and hsting through AWS
- [Jest](https://jestjs.io/docs/getting-started) as the testing framework

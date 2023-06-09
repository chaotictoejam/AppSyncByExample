# AppSync By Example

This repo is source code for the AWS Summit in Washington D.C. In this Dev Chat we learned how to build an AWS AppSync API. This example is a small Library catalog which uses a sigal table design for DynamoDB

This code is structured as following:
* serverless.yml - this holds the tool to deploy your appsync solution using serverless framework
* lib/schema.graphql - this is the GraphQL schema for your AppSync API
* lib/mapping-templates - this holds all the VTL mapping templates for AppSync

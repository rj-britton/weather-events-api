Complementary codebase for my blog post [Securing AWS API Gateway with Cognito Authorizer and OAuth 2.0](https://veygoeng.medium.com/securing-aws-api-gateway-with-cognito-authorizer-and-oauth-2-0-241326d84856)

# Weather API

A RestApi for retrieving and updating lists of weather events.

## Dev Requirements

- An AWS Account
- AWS Access Key
  - Allows Serverless Framework to access your AWS instance to deploy infrastructure. Check out this guide if you need help setting up.
- Node.js
  - Required to install the Serverless Framework dependency using the package.json file included in the repository.

## Deploying the Cloudformation Stack with Serverless Framework

```bash
yarn && yarn serverless deploy
```

## Destroying the Cloudformation Stack with Serverless Framework

```bash
yarn serverless remove
```

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
yarn serverless deploy
```

## Destroying the Cloudformation Stack with Serverless Framework

```bash
yarn serverless remove
```

# Alchemy AWS Example

This example application deploys an AWS Lambda Function, with an IAM Role and DynamoDB Table

# Deploy

```bash
bun install

bun run up # deploy the app

bun run destroy # destroy the app
```

# Project

- [src/app.ts](src/app.ts) - the Alchemy AWS Infrastructure configuration
- [src/handler.ts](src/handler.ts) - the AWS Lambda Function Code

# Scratch - A Simple Note Taking App

# _https://serverless-stack.com_

## Setup

- Clone repository
- Install dependencies

```bash
$ npm install
```

- add the ./config.js file with appropriate data

```js
export default {
  s3: {
    REGION: "REPLACE_WITH_BUCKET_REGION",
    BUCKET: "REPLACE_WITH_S3_BUCKET"
  },
  apiGateway: {
    REGION: "REPLACE_WITH_API_REGION",
    URL: "REPLACE_WITH_API_URL"
  },
  cognito: {
    REGION: "REPLACE_WITH_COGNITO_REGION",
    USER_POOL_ID: "REPLACE_WITH_COGNITO_USER_POOL_ID",
    APP_CLIENT_ID: "REPLACE_WITH_COGNITO_APP_CLIENT_ID",
    IDENTITY_POOL_ID: "REPLACE_WITH_COGNITO_IDENTITY_POOL_ID"
  }
};
```

- Start react

```bash
$ npm start
```

## Deploy

```bash
$ npm run deploy
```

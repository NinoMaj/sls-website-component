### Create template

```sh
serverless create --template-url https://github.com/serverless/components/tree/master/templates/website
```

### Deploying website

- Create user in AWS IAM service (give programmatic access and give AdministratorAccess to serveless).
- Create `.env` file and set AWS credentials.

```
AWS_ACCESS_KEY_ID=...
AWS_SECRET_ACCESS_KEY=...
```

Install dependencies and deploy website:

```sh
npm install
serverless
```

### Demo
[website](http://website-bvc89sl.s3-website.us-east-1.amazonaws.com)

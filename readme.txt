npm i -g serverless
serverless create --template aws-nodejs --path api-serverless-aws-nodejs

serverless invoke local --function hello
    serverless invoke --function hello
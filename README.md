# aws-lambda-serverless-crud
Udemy Course - AWS Lambda and the Serverless Framework - Hands On Learning!


#### Resources
- Serverless
- IAM
- Security Group
- API Gateway
- Lambda
- DynamoDB


#### Setup
npm install


#### Deploy
serverless deploy -v


#### Usage
You can create, retrieve, update, or delete todos with the following commands:


##### Create Todo
curl -X POST https://XXXXXXX.execute-api.us-east-1.amazonaws.com/dev/todos --data '{ "text": "Keep learning" }'


#####  Get all Todos
curl https://XXXXXXX.execute-api.us-east-1.amazonaws.com/dev/todos


##### Get one Todo
curl https://XXXXXXX.execute-api.us-east-1.amazonaws.com/dev/todos/{id}


##### Update one Todo
curl -X PUT https://XXXXXXX.execute-api.us-east-1.amazonaws.com/dev/todos/{id} --data '{"checked": true }'


##### Delete one Todo
curl -X DELETE https://XXXXXXX.execute-api.us-east-1.amazonaws.com/dev/todos/{id}
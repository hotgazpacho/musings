# Lessons Learn from a Year Operating a Serverless Service

- Abstractions provided by AWS-SDK are *almost always* more than sufficient
- Separate IAM Roles per function **from the start**
- Enable X-Ray Active tracing wherever possible
- Use an observability service 
  - DataDog
  - IOPipe
  - Serverless.com
  - Thundra
- Keep Lambda code concise
  - use [modclean](https://github.com/ModClean/modclean) as part of packaging step
- **Learn CloudFormation!!!!!**
- Emulating AWS services falls apart quickly once you move beyond API Gateway & DynamoDB
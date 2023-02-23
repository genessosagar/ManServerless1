* When to use serverless?
    - No administration of infrastructure
    - Scales Horizontally
    - Function as a Service can be triggered with events
    - No upfront costs
    - Pay per execution

* Can be used in the following usecases
    - Cron Tasks
    - IT automation
    - Data processing
    - Web Applications
    - Image / Video processing
    - Chat bots

* When to not use Serverless?
    - Vendor lock in
    - Stateful backends (Gaming)
    - Realtime need
    - Long executions
    - Complex compute
    - High Availability

* Demo
1. Create lambda function - with first_lambda.js code
2. Create a test event for post and get using apigateway-aws-proxy template
3. Create an APIGateway
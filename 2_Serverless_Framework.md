Serverless Framework
--------------------
* Provider Agnostic
* Extensible with plugins
* Multiple language supported
* Deploy your functions and resources

Serverless Framework prerequisites
----------------------------------
* AWS Account
* Node.js
node -v
npm install -g serverless
* Serverless CLI
* AWS credentials setup

Demo
----
```
mkdir my-first-serverless-framework-project
cd my-first-serverless-framework-project
npm init
serverless create --template aws-nodejs
sls deploy
sls remove
```
* The above serverless create command will create handler.js and serverless.yml files
* In serverless.yml always change the name of the service
* Add profile and region under provider block
* Observe the functions block in the serverless.yml file
* Add events section under the functions block
* Use sls deploy command to deploy the resources on the AWS console
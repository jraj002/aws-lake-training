Comprehend Medical Serverless Workflow Repository

## Pre-requisites
#### Create bucket in S3
* Create bucket using the cloudformation script. (Replace bucket name in the commented part.)
* Create folders:
    * athenaoutput
    * comprehendoutput
    * uploadsfolder

#### Install Serverless Framework
* Install nodejs from https://nodejs.org/en/download/
* Install serverless framework
    ```
    npm install -g serverless
    ```
* Check serverless version 
    ```
    serverless --version
    ```

Reference: https://serverless.com/framework/docs/providers/aws/guide/installation/

## Plugins
* change directory to comprehend-service folder in your terminal.
* install following plugins
```
npm install --save-dev serverless-step-functions

npm install serverless-pseudo-parameters
```


## Architecture

![alt text](images/architecture.png "Logo Title Text 1")
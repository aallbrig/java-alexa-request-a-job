### Technologies

1. AWS CloudFormation
1. Java
1. Alexa Java SDK

### Useful commands
* Validate that your yaml or json structure is indeed yaml or json.
    
    ```
    aws cloudformation validate-template --template-body file://aws/cloudformation.yml
    ```
* Use a more intelligent validator that doesn't suck
    ```
    npm run validate-cloudformation aws/cloudformation.yml 
    ```
    _(Ensure you've installed required packages from `package.json`)_


# CFN Template with a Lambda function and Custom Resource

## Description

Deploys a CFN template (accepting 1 parameter), which provisions a Python Lambda function and a Custom Resource to invoke
the Lambda Function. The single parameter is passed into the Lambda, and a response payload is returned, which is found
on the Output section of the template.
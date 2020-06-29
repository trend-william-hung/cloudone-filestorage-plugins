# cloudone-filestorage-plugins

This repository contains Cloud One File Storage Security post-scan actions reference code.

## How to use

### AWS users

1. Go to the [post-scan-actions](post-scan-actions/) or [scan-triggers](scan-triggers/) folder to view all the example Lambda functions.
2. Follow the instructions in the readme of the chosen example to deploy it.
3. Add the `ScanResultTopic` SNS topic of the File Storage Security storage stack as the trigger for the deployed Lambda function.

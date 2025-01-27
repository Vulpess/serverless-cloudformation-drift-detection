# Serverless Cloudformation Drift Detection
Automated Cloudformation Drift detection using Serverless framework

## Deployment
Install Serverless framework globally if you haven't installed yet. You will need `npm` for that. [How to install npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)

Configure `serverless.yaml` file

Set environment variables

```
export REGIONS="us-west-1,us-west-2,us-east-1,us-east-2"
export SLACK_URL="https://hooks.slack.com/services/replace/replace/replace"
```
Deploy

``` sls deploy --stage dev --region us-west-2 --profile my-profile```


 
You might see drift detection requests getting failed due to rate limits exceeded, create a support ticket to increase that limit.


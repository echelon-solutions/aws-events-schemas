# aws-events-schemas

Simple JSON Schemas for events on the AWS cloud platform.

## Introduction

This repository was created with the JSON objects provided in the 
Amazon Web Services documentation for sample events. Read more here:

[Sample Events Published by Event Sources](http://docs.aws.amazon.com/lambda/latest/dg/eventsources.html)

Each JSON for each sample event was turned into a JSON Schema using 
the free web-based JSON Schema Editor. Check it out here:

[JSON Schema Toolset, SDK and Documentation](https://jsonschema.net/#/editor)

## Updates

*The event schemas in this repository are current as of 
**Monday, September 4, 2017**.*

The AWS documentation will be periodically revisited and the contents 
of this repository will be updated to reflect new changes, until AWS 
starts releasing official JSON Schemas for events.

Use this repository with caution, as the schemas may not be applicable 
for your specific scenario.

## Events

- [AWS CloudFormation Create Request Sample Event](http://docs.aws.amazon.com/lambda/latest/dg/eventsources.html#eventsources-cloudformation-create-request)
- [Amazon SES Email Receiving Sample Event](http://docs.aws.amazon.com/lambda/latest/dg/eventsources.html#eventsources-ses-email-receiving)
- [Scheduled Event Sample Event](http://docs.aws.amazon.com/lambda/latest/dg/eventsources.html#eventsources-scheduled-event)
- [Amazon CloudWatch Logs Sample Event](http://docs.aws.amazon.com/lambda/latest/dg/eventsources.html#eventsources-cloudwatch-logs)
- [Amazon SNS Sample Event](http://docs.aws.amazon.com/lambda/latest/dg/eventsources.html#eventsources-sns)
- [Amazon DynamoDB Update Sample Event](http://docs.aws.amazon.com/lambda/latest/dg/eventsources.html#eventsources-ddb-update)
- [Amazon Cognito Sync Trigger Sample Event](http://docs.aws.amazon.com/lambda/latest/dg/eventsources.html#eventsources-cognito-sync-trigger)
- [Amazon Kinesis Streams Sample Event](http://docs.aws.amazon.com/lambda/latest/dg/eventsources.html#eventsources-kinesis-streams)
- [Amazon S3 Put Sample Event](http://docs.aws.amazon.com/lambda/latest/dg/eventsources.html#eventsources-s3-put)
- [Amazon S3 Delete Sample Event](http://docs.aws.amazon.com/lambda/latest/dg/eventsources.html#eventsources-s3-delete)
- [Mobile Backend Sample Event](http://docs.aws.amazon.com/lambda/latest/dg/eventsources.html#eventsources-mobile-backend)
- [Amazon Lex Sample Event](http://docs.aws.amazon.com/lambda/latest/dg/eventsources.html#eventsources-lex)

## Events Schemas

- CloudFormation event | [JSON Schema](./cloudformation.json)
- SES event | **NOT YET DEFINED**
- Scheduled event | [JSON Schema](./scheduled.json)
- CloudWatch Logs event | [JSON Schema](./logs.json)
- SNS event | [JSON Schema](./sns.json)
- DynamoDB event | [JSON Schema](./dynamodb.json)
- Cognito event | [JSON Schema](./cognito.json)
- Kinesis event | [JSON Schema](./kinesis.json)
- S3 Put event | [JSON Schema](./s3-put.json)
- S3 Delete event | [JSON Schema](./s3-delete.json)
- Mobile event | [JSON Schema](./mobile.json)
- Lex event | **NOT YET DEFINED**

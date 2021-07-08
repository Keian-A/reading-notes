# Read-19

1. Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server
  - AWS API Gateway and Lambda function can work in conjunction to resolve client HTTP requests, such as that a ExpressJS server can accomplish.
2. List the AWS Database offerings and talk about the pros and cons of each
  - Relational -> Amazon Aurora, Amazon RDS, Amazon Redshift
  - Key-value -> Amazon DynamoDB
  - In-memory -> Amazon ElastiCache for Memcached, Amazon ElastiCache for Redis
  - Document -> Amazon DocumentDB (with MongoDB compatibility)
  - Wide column -> Amazon Keyspaces (for Apache Cassandra)
  - Graph -> Amazon Neptune
  - Time series -> Amazon Timestream
  - Ledger -> Amazon QLDB

These taken from [here](https://aws.amazon.com/products/databases/)

3. What’s the difference between a FIFO and a standard queue?
  - FIFO (provide *exactly one processing*) compared to a standard queue (each message is delivered *at least once*)
4. How can the server be assured a message was properly received?
  - By sending data back to the client -> conformation

## Define:

1. Serverless API
  - AWS's API Gateway, which [creates a collection of Amazon API Gateway resources and methods that can be invoked through HTTPS endpoints](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/sam-resource-api.html)
2. Triggers
  - These create the events that are published
3. Dynamo vs Mongo
  - Mongo is noSQL, which means everything is stored in objects. Dynamo is key-value.
4. Dynamoose vs Mongoose
  - Dynamoose is a modeling tool for AWS's DynamoDB. Mongoose is a modeling tool for MongoDB.

- Which 3 things had you heard about previously and now have better clarity on?
  1. Serverless API
  2. Triggers
  3. Dynamoose
- Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
  1. Serverless API
  2. Triggers
  3. Dynamoose
- What are you most excited about trying to implement or see how it works?
  - Dynamoose

[<-- Back](ToC.md)
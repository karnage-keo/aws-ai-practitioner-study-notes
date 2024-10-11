# [Amazon Bedrock](https://aws.amazon.com/bedrock/)

## What is Amazon Bedrock?

Amazon Bedrock is a fully managed service that provides access to high-performing foundation models (FMs) from leading AI companies and Amazon via a unified API. It allows you to select models that fit your needs, offering tools to build generative AI applications with security and privacy in mind. Bedrock supports private customization of models using techniques like fine-tuning and [Retrieval Augmented Generation (RAG)](https://aws.amazon.com/what-is/retrieval-augmented-generation/), enabling the creation of AI agents that integrate with your enterprise systems. With its serverless experience, Bedrock simplifies customization and deployment without the need to manage infrastructure

## What can you do with Amazon Bedrock?

Experiment with prompts and configurations via API or console.
* Enhance responses by querying your data sources.
* Build AI agents that reason and perform tasks.
* Customize models with training data for specific tasks.
* Improve efficiency with Provisioned Throughput.
* Choose the best model for your needs and apply content safeguards.

Check AWS documentation for regional limitations.

## Access foundation models

Access to Amazon Bedrock foundation models isn't granted by default. You can request access, or modify access, to foundation models only by using the Amazon Bedrock console.

You will first need to have the [correct IAM permissions](https://aws.amazon.com/iam/). The minium required access level for access foundation models are as follows:

* aws-marketplace:Subscribe
* aws-marketplace:Unsubscribe
* aws-marketplace:ViewSubscriptions


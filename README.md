# Deploying a Multi-LLM and Multi-RAG Powered Chatbot Using AWS CDK on AWS

![sample](assets/sample.gif "AWS GenAI Chatbot")


## Modular, comprehensive and ready to use
This sample provides code ready to use so you can start **experimenting with a variety of Large Language Models, settings and prompts.**

Supported models providers:
- [Amazon Bedrock](https://aws.amazon.com/bedrock/) (_currently in preview_)
- [Amazon SageMaker](https://aws.amazon.com/sagemaker/) self hosted models from Foundation, Jumpstart and HuggingFace.
- Third party providers via API such as Anthropic, Cohere, AI21 Labs, OpenAI, etc. [See available langchain integrations](https://python.langchain.com/docs/integrations/llms/) for a comprehensive list.


## Experiment multiple RAG options with Workspaces
This sample provides comes with CDK constructs to allow you to optionally deploy one or more of:

- [Amazon Aurora Serverless with pgvector](https://aws.amazon.com/about-aws/whats-new/2023/07/amazon-aurora-postgresql-pgvector-vector-storage-similarity-search/)
- [Amazon OpenSearch VectorSearch](https://aws.amazon.com/blogs/big-data/amazon-opensearch-services-vector-database-capabilities-explained/)
- [Amazon Kendra](https://aws.amazon.com/kendra/)

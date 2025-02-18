# amazon-bedrock-workshop

The goal of this workshop is to give you hands-on experience in leveraging foundation models (FMs) through Amazon Bedrock. Amazon Bedrock is a fully managed service that provides access to FMs from third-party providers and Amazon; available via an API. With Bedrock, you can choose from a variety of models to find the one that’s best suited for your use case.

Within this series of labs, you will go through some of the most common Generative AI usage patterns we are seeing with our customers. You will explore techniques for generating text and images, and learn how to improve productivity by using foundation models to help in composing emails, summarizing text, answering questions, building chatbots, creating images, and generating code. You will gain hands-on experience using Bedrock APIs, SDKs, and open-source software, such as LangChain and FAISS, to implement these usage patterns.

What’s included in this workshop

Text Generation [Estimated time to complete - 30 mins]
KnowledgeBase and RAG [Estimated time to complete - 30 mins]
Model Customization [Estimated time to complete - 45 mins]
Images and Multimodal [Estimated time to complete - 45 mins]
Agents [Estimated time to complete - 30 mins]
Open Source [Estimated time to complete - 30 mins]


**Text Generation **

![image](https://github.com/user-attachments/assets/c5aefe3f-1821-4dfe-985a-2d28f7df91b2)

There are five sub-patterns that will be demonstrated on this module for text generation:

Zero-shot generation  - With zero-shot generation, the user will only provide an input request to generate an email without any context. We will explore zero-shot email generation using two approaches: Bedrock API (Boto3) and Bedrock integration with LangChain.

Code generation  - With zero-shot generation we can leverage the code generation capability of the model. This is based on the data learnt by the model during training.

Summarization  - In this sub-pattern, we will explore the summarization capability and leverage the Titan model for the same. This approach is dependent on the size of the document and the context length. Later on we will explore other patterns to summarize larger documents.

Simplified Question Answering  - The example will show how questions are sent to the model and will get answers from the base model with no modifications. Question Answering (QA) is an important task that involves extracting answers to factual queries posed in natural language. Typically, a QA system processes a query against a knowledge base containing structured or unstructured data and generates a response with accurate information. Ensuring high accuracy is key to developing a useful, reliable and trustworthy question answering system, especially for enterprise use cases.

Entity Extraction  - In this sub-pattern, we will Entity extraction is an NLP technique that allows us to automatically extract specific data from naturally written text, such as news, emails, books, etc. That data can then later be saved to a database, used for lookup or any other type of processing.

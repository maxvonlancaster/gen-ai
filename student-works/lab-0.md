# RAG System creation

Warning! This lab assignment is not compulsory, only do it if you fill like you do not want to do lab assignment 1.

Retrieval-augmented generation (RAG) is a technique that enables large language models (LLMs) to retrieve and incorporate new information from external data sources. With RAG, LLMs first refer to a specified set of documents, then respond to user queries. These documents supplement information from the LLM's pre-existing training data. This allows LLMs to use domain-specific and/or updated information that is not available in the training data. For example, this helps LLM-based chatbots access internal company data or generate responses based on authoritative sources.

## Choose topic

Choose the topic for your RAG. Some of the options (but not limited to these):
- Documentation for you open-source project
- Information about your hometown
- Helper for students
- Or anything you like

## Retrieve an Open AI key

Go to https://platform.openai.com/settings/organization/api-keys and generate a new api key for personal usage.

Other option: ask your teacher for key. In that case, use wisely, as running it out of limit might influence other students work.

You will also need langchain key. It is free here: http://docs.langchain.com/langsmith/create-account-api-key

## Gather data for you system

Code sample here: https://github.com/maxvonlancaster/gen-ai/blob/main/new/104-rag-systems.ipynb

## Train the model

Code sample here: https://github.com/maxvonlancaster/gen-ai/blob/main/new/104-rag-systems.ipynb

## Rag chunking

Try rag memory chunking. More about it here: https://community.databricks.com/t5/technical-blog/the-ultimate-guide-to-chunking-strategies-for-rag-applications/ba-p/113089

## Github and Moodle

Push to github and submit link to codebase in moodle.

## Additional: deploy

Additional points: deploy your project as an backend api system, and create a simple ui for working with it.

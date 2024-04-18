# [LangChain4j](https://github.com/langchain4j/langchain4j) Community Examples

<img src='images/langchain4j_logo_text.png' alt='LangChain4j Integrations' width="200">

## Awesome LangChain4j 🎉

This repository is a space to find and share more elaborate examples using the LangChain4j library.
The idea is to allow the community to inspire each other, to build on these examples or to use them for demo's. 
Please read the [usage conditions](#usage-conditions) at the end of this page, and check the license of the project in question before using the examples, and credit the creator.
For the official LangChain4j examples, tutorials and documentation, see [more information](#more-information-on-langchain4j).

We welcome all types of more elaborate examples, such as 
- interesting use cases
- elaborate examples with specific providers, frameworks or set-ups
- experimental programs that push the limits of what is possible with LLMs and AI integration.

| Title                                                                                                                                                                                                                                                | Short Description                                                                                                                                                                                                                                                                                                         | Contributor                 | Usage and Extension allowed | Usage for Demos allowed 
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------|-----------------------------|-------------------------| 
| [Customer Assistant in Spring Boot](https://github.com/langchain4j/langchain4j-examples/blob/cacef9854057f3017ee5405368cd27c446a5df3f/customer-support-agent-example/src/main/java/dev/langchain4j/example/CustomerSupportAgentApplication.java#L39) | Car rental service customer assistant with memory, access to terms of use, and tools to intervene on bookings. Powered by GPT-4.                                                                                                                                                                                          | Dmytro Liubarskyi           | ✅                           | ✅                       |  
| [Customer Assistant in Quarkus](https://github.com/geoand/langchain4j-quarkus-example)                                                                                                                                                               | Car rental service customer assistant with memory, access to terms of use, and tools to intervene on bookings. Powered by GPT-4. Including simple frontend.                                                                                                                                                               | Georgios Andrianakis        | ✅                           | ✅                       |
| [Feedback Analyser](https://github.com/LizeRaes/feedback-analyzer)                                                                                                                                                                                   | Example splitting and categorizing feedback with LLM + dashboard and ChatBot to explore the recieved feedback. Quarkus example with as many plain java parts as possible for demo purpose. Includes ChatBot, RAG, metadat filtering, persistence to SQLite database, frontend with form data post, chatbot and dashboard. | Lize Raes and Vincent Peres | ✅                           | ✅                       |  
| [RAG Genie](https://github.com/stephanj/rag-genie)                                                                                                                                                                                                   | LLM RAG prototype to test and evaluate your embeddings, chunk splitting strategies using Q&A and evaluations.                                                                                                                                                                                                             | Stephan Janssen             | ?                           | ?                       |
| [LLM Tree-of-Thought](https://github.com/ugwun/tree_of_thought_langchain4j)                                                                                                                                                                          | Explores the implementation of the Tree of Thought (ToT) approach (metacognition) with LLMs. More info [here](https://medium.com/aimonks/metacognition-experiments-with-ai-8ba10f284e4c).                                                                                                                                 | Cyril Sadovsky              | ?                           | ?                       |
| [Devoxx Genie IntelliJ Assistant](https://github.com/devoxx/DevoxxGenieIDEAPlugin)                                                                                                                                                                   | Using LangChain4j to build an AI Coding Assistant in IntelliJ that supports local models. Includes code for IntelliJ Plugins.                                                                                                                                                                                             | Devoxx                      | ?                           | ?                       |
| [Serverless Book Management App (Google Next 24)](https://github.com/GoogleCloudPlatform/serverless-production-readiness-java-gcp/tree/main/sessions/next24/books-genai-vertex-langchain4j)                                                                                                                                                   | Using LangChain4j to build a big serverless book / library manaegement app leveraging Google models and services.                                                                                                                                                                    | Dan Dobrin and Yanni Peng   | ?                           | ?                       | 
| [Build your own ChatGPT in Quarkus](https://github.com/Azure-Samples/azure-openai-rag-workshop) |  Workshop to build a chatbot, using Quarkus, LangChain4J and a website to test our chatbot.  | Yohan Lasorsa, Anontio Goncalves, Julien Dubois, Sandra Ahlgrimm                | ✅                           | ✅                       |
| [Add you example here](https://link.to.your.repo)                                                                                                                                                                                                    | Short description of your app and the interesting parts                                                                                                                                                                                                                                                                   | Your Name(s)                | ✅                           | ✅                       |

## Usage Conditions

**For users:**
Please check the README of the example and make sure you use it only as allowed by the permissions

**For contributors:**
If you have an inspiring application that you want to share with the community, you're very welcome to add it here, either by committing the code or by adding a link in the table below.
Please make sure your project compiles and runs correctly. Please provide a README explaining what your example does, how to run it, and which of the following permissions you grant:
- permission to get inspired and make a similar app
- permission to use the example for demos, while crediting you
- permission to use and extend the application

## More information on LangChain4J
- [Repository](https://github.com/langchain4j/langchain4j)
- [Documentation](https://docs.langchain4j.dev/)
- [Standard Examples](https://github.com/langchain4j/langchain4j-examples)
- [Tutorials](https://github.com/langchain4j/langchain4j-examples/tree/main/tutorials/src/main/java)
